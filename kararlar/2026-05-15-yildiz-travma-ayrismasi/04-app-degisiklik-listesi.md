# App Değişiklik Listesi — Karar 21

Bu liste Karar 21'in app tarafında uygulanacak refactor kapsamını tarif eder. **Bu pakette kanon değişikliği yapıldı; app kodu henüz değiştirilmedi.** Aşağıdaki iş ayrı bir iş paketi olarak kuyrukta.

## Sıra (kullanıcıyla kararlaştırılan)

1. UX framing metinleri (önce — kullanıcı algısını hizala)
2. Karakter sayfası entegrasyonu (sonra — kod kritik yer)
3. Travma sistemi refactor (sonra — gate mantığı kaldırma)

---

## 1. UX Framing Metinleri

### `app/app/kalibrasyon/yildiz/page.js`

- Line 144-149 (giriş ekranı akademik not): "Eşik değerleri travma sistemi içinde etik koruma için kullanılır" cümlesi **kaldırılır**
- Yerine: yıldız matrisinin pedagojik amacı + karaktere yaklaşım katmanı önerileri

### `app/app/kalibrasyon/page.js`

- Line 314, 368, 415 — "psikolojik kapasiten" eksenli framing
- "Karakter çalışırken oyuncuyu kendi sınırlarından koruruz" cümlesi yeniden yazılır: koruma sahne-level (travma uyarı + topraklanma), profil-level değil
- "Senin psikolojik kapasiten bu derinliklere hangi sırayla, hangi yoğunlukta erişeceğini belirler" cümlesi **kaldırılır**

### `app/app/profil/page.js`

- 6 boyut görünümü (line 119-124) zaten var — bunun yanına/üstüne pedagojik bir "gelişim rotası" bölümü eklenir
- Parlayan / Gelişim / Plan bölgeleri (Yıldız sonuç ekranındaki mantık) profilde kalıcılaşır
- Karaktere yaklaşım önerileri seçili karaktere göre buradan da gösterilebilir

---

## 2. Karakter Sayfası Entegrasyonu

### `app/app/antrenman/karakter/willy/page.js`, `macbeth/page.js`, `biff/page.js`

- Line 48 civarı: `const psikolojikPuan = kalibrasyon?.yildiz?.psikolojik ?? null;` **kaldırılır**
- Yerine: `const yildiz = kalibrasyon?.yildiz ?? null;` — tüm 6 boyut taşınır
- Line 129 civarı: `travmaProfili={psikolojikPuan}` prop'u **kaldırılır**
- Yerine: Karaktere yaklaşım önerileri için `yildiz` objesi ZihinselAntrenman / SeninCerceven componentlerine taşınır

### `components/ZihinselAntrenman.js`

- Line 81: `const yildizBenzeri = travmaProfili != null ? { psikolojik: travmaProfili } : null;` **kaldırılır**
- `sahneErisimi` çağrısı `sahneUyarisi` ve `topraklanmaGerekli` olarak ayrılır
- Yıldız 6 boyutu çalışma yaklaşımı önerilerinde kullanılır (yeni)

### `components/SeninCerceven.js`

- Line 132: `sahneErisimi(sahneBenzeri, kalibrasyon?.yildiz)` çağrısı `sahneUyarisi(sahneBenzeri)` olarak güncellenir
- Topraklanma tetikleyicisi ayrı çağrılır: `topraklanmaGerekli(sahneBenzeri.travmaSeviyesi)`

---

## 3. Travma Sistemi Refactor

### `app/app/lib/travma.js`

**Kaldırılır:**
- `sahneErisimi(sahne, yildiz)` fonksiyonu (line 68-138)
- Yıldız parametresi ile gate mantığı (line 94-138)

**Eklenir / yeniden yazılır:**

```javascript
// Travma uyarı bilgisi — gate değil, oyuncuya gösterilen uyarı
export function sahneUyarisi(sahne) {
  const seviye = sahne?.travmaSeviyesi || 0;
  const kategoriler = sahne?.travmaKategorileri || [];

  if (seviye === 0) return { uyari: false, mesaj: null };
  if (seviye === 1) return {
    uyari: true,
    mesaj: 'Bu sahne şu temalara atıfta bulunuyor: ' + travmaEtiketleri(kategoriler).join(', ') + '.',
  };
  if (seviye === 2) return {
    uyari: true,
    mesaj: 'Bu sahne şu temalara tanıklık ediyor: ' + travmaEtiketleri(kategoriler).join(', ') + '. Sahne sonrası topraklanma adımı önerilir.',
  };
  if (seviye === 3) return {
    uyari: true,
    mesaj: 'Bu sahne yoğun bir derinlikte işliyor — şu temalar icra ediliyor: ' + travmaEtiketleri(kategoriler).join(', ') + '. Sessiz bir alan, hazırlık zamanı; sahne sonrası topraklanma adımı önerilir.',
  };
}

// Topraklanma tetikleyicisi — sahne yoğunluğuna bağlı, profil-bağımsız
export function topraklanmaGerekli(yogunluk) {
  return yogunluk >= 2;
}
```

### `app/app/lib/kalibrasyon.js`

**Eklenir:** `yildizYaklasimi(yildiz, karakter)` fonksiyonu. VAK'ın `vakDili` örüntüsünde, 6 boyut için karaktere yaklaşım önerileri üretir.

Taslak yapı:

```javascript
export function yildizYaklasimi(yildiz, karakter) {
  if (!yildiz) return null;

  const { guclu, zayif } = yildizGucluZayif(yildiz); // mevcut fonksiyon

  return {
    gucluEksen: guclu,    // örn. { id: 'entelektuel', deger: 6.2 }
    zayifEksen: zayif,
    aciKapi: yaklaşımÖnerisi(guclu.id, karakter, 'guclu'),
    destekÖnerisi: yaklaşımÖnerisi(zayif.id, karakter, 'zayif'),
  };
}

// 6 boyut × {güçlü/zayıf} = 12 öneri matrisi (sözlük)
```

Öneri sözlüğü 6 boyut × {güçlü, zayıf} = 12 mesaj. Sözlük içeriği Method Book Bölüm C/Modül I yapısıyla hizalı yazılır.

---

## Test edilecek

- Karakter sayfalarına girişte yıldız datası taşınıyor mu (6 boyut)
- Sahne uyarıları görüntüleniyor mu (kategori adlarıyla, gate olmaksızın)
- Topraklanma sahne sonrası yoğunluk 2-3 için tetikleniyor mu (kategori bağımsız)
- Karaktere yaklaşım önerileri profile göre değişiyor mu
- Eski sahneErisimi çağrıları kalmadı mı (grep ile temizlik kontrolü)

## Sonraki iş paketi açma zamanı

Bu refactor kanon değişikliğinin "kanon → app" tetiklemesidir. UX framing metinleri ilk parça olarak başlatılır (kullanıcı önceliği). Sonraki tur açıldığında 1 → 2 → 3 sırasıyla gidilir.
