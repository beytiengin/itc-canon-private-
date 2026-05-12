# Spine v1.5 → v1.6 Güncellemesi — Workshop Geri Besleme Paketi

**Hedef:** Spine sürümü v1.5 → v1.6
**Tarih:** 12 Mayıs 2026
**Karar referansları:** `01-decision-log-eklentisi.md` Karar 11, 12, 13, 14

Bu dosya Spine'a yedirilecek tüm değişiklikleri toplar. Beş ayrı müdahale içerir:
1. Spine üst meta + intro bölümü güncellemesi (kozmetik temizlik)
2. §3.13, §3.14, §3.15, §3.16 yeni alt-bölümler (dört karar)
3. Mevcut §3.1, §3.3, §3.4, §3.5, §3.7, §3.11'e çapraz atıflar
4. §4 (Çapraz Geçişler) Workshop bölümlerinde minimal güncellemeler
5. §6 Sürüm Geçmişi'ne v1.6 satırı + footer düzeltmesi

---

## 1. Üst Meta + Intro Bölümü Güncellemesi

### Mevcut (Spine v1.5 üst satırlar)

```markdown
# ITC EKOSİSTEM — SPINE

**Dört projenin paylaştığı omurga**
**v1.5 · 12 Mayıs 2026 · Beyti Engin × Claude**

---

## v1.3'te neler değişti?

v1.2'ye göre iki büyük yapısal güncelleme yapıldı:

1. **Workshop dördüncü katman olarak ekosisteme eklendi.** [...]
2. **Method Book ana yapı oturumunda 8 stratejik karar alındı.** [...]

v1.2'nin geri kalan içeriği aynen korundu. §6 ve §7 değişmedi.
```

### Yeni (Spine v1.6 üst satırlar)

```markdown
# ITC EKOSİSTEM — SPINE

**Dört projenin paylaştığı omurga**
**v1.6 · 12 Mayıs 2026 · Beyti Engin × Claude**

---

## v1.6'da neler değişti? (Workshop Geri Besleme Paketi)

12 Mayıs 2026 oturumunda Workshop projesinden ana Spine'a dört kanon genişlemesi yedirildi:

1. **§3.13 — Transmisyon Mimarisi: BE × FKA Eş Eğitmenlik** (Karar 11). Atölye/eğitim ortamında beş katmanlı eğitmen dağılımı: teorik bloklar paylaşımlı; Modül I birlikte; Modül II BE önder/FKA eşlikçi; Modül III BE solo/FKA klinik on-call; etik bloklar FKA imzalı.

2. **§3.14 — Tek Karakter İlkesi** (Karar 12). Grup transmisyonunda kohort tek karakter etrafında toplanır. Pedagojik · operasyonel · etik gerekçelerle kanonik. B1 (Kendi Karakterin) istisnadır, A2 mezunu önkoşulu.

3. **§3.15 — Karakter Haritası Taksonomisi** (Karar 13). Her karakter dosyası üçlü taksonomiyle haritalanır: Yolculuk Bölüm Yapısı × Çapa Noktaları × Bölüm Tipleri (A/B/C/D). §3.3 Travma Matrisi ile karışmamalıdır.

4. **§3.16 — Yolculuk Geometrisi: Sahne · Tanıklık · Çift Geri Bildirim** (Karar 14, **Filiz klinik onayı bekleniyor**). Yolculuk Modu grup transmisyonunun üç değişmez bileşeni: sahnede yapılır (kapalı oda yasak), grup tanıklığında, çift geri bildirim sırası sabit (önce grup, sonra oyuncu).

Bu paket dışında: §3.1, §3.3, §3.4, §3.5, §3.7, §3.11'e çapraz atıflar eklendi; v1.3–v1.5'in intro/footer kozmetik tutarsızlıkları temizlendi. Spine'ın 1.3, 1.4, 1.5 sürümlerinden gelen tüm içerik aynen korundu.

---

## v1.3–v1.5 Tarihçesi (sıkıştırılmış)

- **v1.3 (8 Mayıs 2026):** Workshop dördüncü katman olarak ekosisteme eklendi (Karar 6); Method Book ana yapı oturumunda 8 stratejik karar alındı (Karar 1–8). §3'e üç yeni alt-bölüm: §3.9 Modül I'in Üç Testi, §3.10 Doğrular Üç Kaynak Yapısı, §3.11 Dijital Araç Sınırı İlkesi. §2 Method Book yapısı güncellendi (C-Ek eklendi).

- **v1.4 (8 Mayıs 2026):** §3.10 yeniden tanımlandı — Çift Üçlü İlkesi ve 3×3 Matris (VAK × Giriş Kapıları, Karar 9). Eski §3.10 (Doğrular Üç Kaynak) → §3.11; eski §3.11 (Dijital Araç Sınırı) → §3.12.

- **v1.5 (12 Mayıs 2026):** §3.11 (Doğrular) "Çift Üçlü ve 3×3 Matris" olarak genişletildi (Karar 10) — Kaynak × Katman matrisi.

Detaylı sürüm geçmişi §6'da.
```

---

## 2. Yeni §3.13 — Transmisyon Mimarisi

§3.12'den sonra eklenir.

```markdown
### 3.13 · Transmisyon Mimarisi: BE × FKA Eş Eğitmenlik (YENİ — v1.6, Karar 11)

ITC transmisyonu (atölye, akademik eğitim, kurumsal pilot) Beyti Engin (pedagojik lider) × Filiz Kaya Ataklı (klinik gözetim) eş eğitmenlik modeliyle çalışır. Beş katmanlı dağılım:

**1. Teorik bloklar — paylaşımlı.** Felsefe, Kabuller, Manifesto, kuramsal zemin, Çift Üçlü matrisleri (§3.10 ve §3.11) iki ses olarak birlikte sunulur.

**2. Modül I (Kalibrasyon) — birlikte.** VAK, MBTI, Yıldız Oyuncu yorumlamaları her zaman eş eğitmenlidir. Yıldız Oyuncu psikolojik puanı klinik perspektifle (FKA) ve pedagojik çerçeveyle (BE) birlikte okunur.

**3. Modül II (Karakter Dramaturjisi) — BE önder, FKA eşlikçi.** Karaktere Hazırlık Soruları, Doğrular, Timeline, Çerçeveler çalışması BE'nin pedagojik liderliğindedir. FKA arka planda gözlemci — etik kayma, kişisel travmaya kayma, dissosiyatif belirti gözetir. Müdahale eder ama merkeze çıkmaz.

**4. Modül III (Yolculuk + Sahneleme) — BE solo, FKA klinik on-call.** Yolculuk Modu ve sahne çalışması BE solo yürütür. FKA atölye odasında bulunur ama yönlendirme yapmaz; aşağıdaki tetikleyiciler aktive olduğunda devreye girer:

- **3+ dakika dissosiyatif belirti** (göz teması kaybı, "burada değilim" ifadesi, bedensel donma)
- **Anı geçişi** (oyuncu karakter sahnesinden kendi geçmişine geçer)
- **BE sezgisi durdurma** (BE eğitmenlik anlamlandıramadığında FKA'ya işaret verir)

Tetikleyici aktive olduğunda BE atölyeyi geçici duraklatır; FKA topraklanma protokolünü (§3.4) ya da klinik geçişi yönetir. Sonrasında devam ya da kapatma kararı FKA klinik değerlendirmesine göre alınır.

**5. Etik bloklar — FKA imzalı.** Travma Matrisi (§3.3, 8×4), Substitution kullanılmaz ilkesi (§3.1), Topraklanma Protokolü (§3.4), Yıldız Profil Eşleşme Matrisi (§3.3), Yolculuk Geometrisi'nin klinik koruma katmanı (§3.16) bloklarının klinik içeriği FKA tarafından sunulur. Dokümantasyona "Bu bölüm Filiz Kaya Ataklı tarafından imzalanmıştır" işareti taşır.

**Operasyonel maliyet ve sonuçlar**

İki eğitmen tüm atölyede bulunmalı — fiyatlandırma iki eğitmen ücretini taşır. Filiz'in klinik takvimi atölye takvimiyle çatışabilir — planlama önkoşul olarak Filiz onayı içerir.

Atölye fiyatlandırması solo eğitmen × eş eğitmen olarak iki katmanlı olabilir. Kurumsal pilotlar (HMDK Stuttgart, Royal Central, vb.) için eş eğitmenlik standarttır. Bireysel oyuncu pilotları için solo eğitmen seçeneği açılabilir — ancak solo eğitmen Modül III'ü tek başına yapmamalıdır; ya FKA on-call (uzaktan video) ya da Modül III bloğu programdan çıkar (henüz açık karar — Spine §5).

**Sertifikasyon karşılığı**

E1 (Train-the-Trainer) sertifikasyonu pedagojik eğitmen × klinik gözetim çifti olarak verilir. Tek eğitmen sertifikası yoktur. Bu yapı klinik güvenliği eğitmen ölçeğinde de korur.
```

---

## 3. Yeni §3.14 — Tek Karakter İlkesi

§3.13'ten sonra eklenir.

```markdown
### 3.14 · Tek Karakter İlkesi (Grup Transmisyonunda) (YENİ — v1.6, Karar 12)

ITC grup transmisyonunda kohort tek bir karakter etrafında toplanır. 8–14 kişilik bir kohortta her katılımcı farklı karakter çalıştığında ITC operasyonel olarak çalışmaz.

İlke üç düzeyde gerekçelidir:

**A. Pedagojik düzey — Kabul 1'in operasyonel görünürlüğü.** §3.7 Kabul 1 ("Karakter analiz edilmelidir") kohort ölçeğinde grup aynı karakteri farklı kapılardan analiz ederek **canlı** görür. Farklı karakterlerle çalışılırsa analiz örnekleri karşılaştırılamaz; kohort birbirinden öğrenemez.

**B. Operasyonel düzey — eğitmen bilişsel yükü.** Eğitmen bir atölye günü boyunca bir karakterin haritasını taşır. 12 farklı karakter taşımak yapısal olarak mümkün değil — eğitmen yüzeyselleşir ya da bazı katılımcıları ihmal eder. Tek karakter eğitmen dikkatini derinleştirir.

**C. Etik düzey — klinik konteyner.** FKA klinik gözetim mantığı (§3.13) kohortun aynı yoğunluk topografyasında olmasını gerektirir. Hamlet kohortunda Çapa No 3 (Bölüm IX) önceden bilinen en hassas an; klinik on-call protokolü o nokta etrafında planlanır. 12 farklı karakter = 12 farklı topografya = klinik gözetim imkânsız.

**Format Uygulaması**

| Format | Tek Karakter | Karakter |
|---|---|---|
| A1 (Tanıtım) | ✅ Zorunlu | Hamlet (varsayılan) |
| A2 (Tam Modül) | ✅ Zorunlu | Programla belirlenir |
| **B1 (Kendi Karakterin)** | **❌ İstisna** | Her katılımcı kendi rolü |
| C1 (Metin Çözümleme) | ✅ Zorunlu | Atölye konusuyla |
| C2 (Karakter Sayfası Mimarisi) | ✅ Zorunlu | Hamlet veya Macbeth |
| C3 (Akış & Performans) | ✅ Zorunlu | Programla belirlenir |
| D1 (Etik & Klinik Güvenlik) | ✅ Zorunlu | Hamlet (Çapa No 3 etik örneği) |
| D2 (Kuramsal Çerçeve) | ✅ Zorunlu | Hamlet (Çift Üçlü uygulaması) |
| E1 (Train-the-Trainer) | ✅ Zorunlu | Adaylara verilen karakter |

**B1 İstisnası — "Kendi Karakterin"**

B1 katılımcıların prova ettikleri/edecekleri karakterlerle çalıştıkları formattır. Tek karakter ilkesi uygulanmaz çünkü atölyenin amacı her katılımcının kendi yaratım sürecine ITC çerçevesini taşımasıdır.

**Ön koşul:** B1 katılımcısı **A2 mezunu** olmalı. ITC çerçevesini önce ortak bir karakter üzerinde edinmeden kendi karakterine taşıyamaz. Bu ön koşul A2 → B1 sıralamasını kanonlaştırır.

**Karakter tanımı**

"Karakter" derken kanonik ITC karakterleri (Hamlet, Macbeth, Willy Loman, Biff Loman) veya gelecek karakterler kastedilir. Kohort karakterinin Workbook benzeri kanonik veriye (Doğrular, Timeline, Çerçeveler) sahip olması şart. Macbeth ITC kanonuna giriyor ancak Workbook'u henüz yok — Macbeth atölyesi açılmadan önce Workbook benzeri bir kanon dokümanı gerekli (Macbeth Timeline temel alınabilir).
```

---

## 4. Yeni §3.15 — Karakter Haritası Taksonomisi

§3.14'ten sonra eklenir.

```markdown
### 3.15 · Karakter Haritası Taksonomisi: Yolculuk × Çapa × Tip (YENİ — v1.6, Karar 13)

> **Not:** Bu taksonomi **§3.3 Travma Matrisi'nden (8 kategori × 4 yoğunluk) farklı bir eksendir** — karışmamalıdır. §3.3 içeriğin etik yoğunluğunu, §3.15 yolculuk içindeki yapısal konumu sınıflar.

Her ITC karakterinin yolculuk yapısı üç eksende işaretlenir. Bu üçlü işaretleme bir taksonomi olarak kanondur; her karakter dosyası bu üçlüyle haritalanır.

**A. Yolculuk Bölüm Yapısı — kaç bölüm**

Karakterin yolculuğu kaç kanonik bölüme ayrılır. Hamlet için **13 bölüm** (Workbook s.126–289'da kanon). Macbeth için sayısal kanon ayrı tartışılır (Macbeth Timeline'da 12 bölüm önerisi var, kanon onayı bekliyor).

**B. Çapa Noktaları — hassas yoğunluk anları**

Yolculuk içinde belirli sayıda çapa noktası vardır. Çapa, oyuncunun karakterin yoğunluğuyla bedensel olarak tutulduğu ankordur — Topraklanma Protokolü'nün (§3.4) karşı kutbu. Hamlet için **5 çapa**:

- **Çapa No 1** — Babanın hayaleti (Bölüm IV)
- **Çapa No 2** — Aktörlerin gelişi
- **Çapa No 3** — "Olmak ya da olmamak" (Bölüm IX) — **EN HASSAS** (FKA klinik koruma katmanı zorunlu, bkz. Workbook 2. baskı erratası D.5)
- **Çapa No 4** — Ophelia'nın mezarı
- **Çapa No 5** — Düello (Bölüm XIII)

Çapa numarası bölüm numarasıyla aynı değildir; çapa **bölüm içindeki tekil hassas an**, bölüm **yolculuk dilimi**.

**C. Bölüm Tipleri — pedagojik fonksiyon**

Her bölüm dört tipten birine girer:

- **Tip A — Çapa bölümü:** Bir çapa noktası içerir; yoğunluk doruğu burada.
- **Tip B — Geçiş bölümü:** İki çapa arası dramaturjik geçiş; bedensel yoğunluk düşük, anlatı katmanı yüksek.
- **Tip C — Derin yüzleşme bölümü:** Çapa yok ama birikimli yoğunluk var. **Özel statü** — açıklama aşağıda.
- **Tip D — Kapanış bölümü:** Yolculuğun çözüldüğü, çıkış geometrisinin hazırlandığı bölüm.

**Tip C — özel statü**

Tip C bölümleri ITC pedagojisinde özel önemdedir. Çapa noktası içermez (belirgin doruk yok), ama oyuncunun bir önceki bölümlerin birikiminden dolayı bedensel olarak yüklü hâlde girdiği bölümdür. Tip A daha öngörülebilir bir yoğunluk taşır; Tip C ise **sinsi yoğunluktur** — eğitmen Tip C'lerde birikimli yorgunluk ve gizli dissosiyatif belirtiler için ek dikkat tutar.

Hamlet'te Tip C bölümler özellikle Bölüm VII–VIII civarındadır (Polonius öldürme ve sonrası).

**§3.3 Travma Matrisi ile Ayrım (kritik)**

| Boyut | Karakter Haritası (§3.15) | Travma Matrisi (§3.3) |
|---|---|---|
| Birim | Yolculuk bölümü | Sahnedeki travmatik içerik |
| Ölçtüğü | Yolculuk içindeki yapısal konum | İçeriğin etik yoğunluğu |
| Sınıflama | A/B/C/D bölüm tipi + çapa numarası | 8 kategori × 4 yoğunluk |
| Kim kullanır | Eğitmen — sahne ritmi için | Oyuncu × Eğitmen — etik filtre için |
| Pedagojik soru | "Şu an yolculuğun neresindeyiz?" | "Bu içerik oyuncu için güvenli mi?" |

İki sınıflama birbirine bağımlı çalışır ama farklı sorular sorar. Tip A bir bölüm aynı anda Travma Matrisi'nde "Kayıp × Tanıklık" (2 yoğunluk) olabilir; iki ayrı işarettir, biri konum diğeri içerik. E1 sertifikasyonu kriteri: aday her iki sınıflamayı bir karakter üzerinde ayrı doldurabilmeli.

**Kanonik Atıf Formatı**

```
Hamlet · Bölüm IX · Tip A · Çapa No 3
```

Bu format Workshop dokümantasyonunda, Method Book Bölüm E vakalarında, App Modül III navigasyon etiketlerinde, Workbook 2. baskı TOC eşleştirmesinde tutarlı kullanılır.
```

---

## 5. Yeni §3.16 — Yolculuk Geometrisi

§3.15'ten sonra eklenir.

```markdown
### 3.16 · Yolculuk Geometrisi: Sahne · Tanıklık · Çift Geri Bildirim (YENİ — v1.6, Karar 14)

> **⚠ Provisional:** Bu alt-bölüm Filiz klinik onayı bekliyor. Onay sonrası flag kaldırılır; sürüm v1.6 → v1.6.1 patch'i atılır. Klinik koruma protokolü (özellikle çift geri bildirim sırasında dissosiyatif risk) FKA tarafından detaylandırılacak.

Yolculuk Modu'nun grup transmisyonu üç değişmez geometrik bileşenle çalışır. Bileşenler birbirinden ayrılmaz — biri eksikse Yolculuk Modu olmaz, başka bir şey olur. Bu yüzden "geometri" denir, "öneri" değil.

**A. Sahnede yapılır**

Yolculuk her zaman fiziksel sahne alanında — atölye odasının ortasında, ışık altında, görünür konumda — gerçekleştirilir. **Kapalı oda, kabin, izolasyon mekânı YASAK.**

Bu yasak etik bir kural değildir, geometrinin kendisidir: kapalı oda Yolculuk Modu'nun diğer bileşenlerini (B ve C) fiziksel olarak imkânsız kılar. İhlali pedagojik hata değil, **klinik tehlike** üretir — Yolculuk'u panik atağa ya da dissosiyatif epizoda dönüştürme potansiyeli taşır.

**B. Grup tanıklığında**

Yolculuk yalnız değil — sessiz, dikkatli, müdahalesiz bir kohort önünde yapılır. Tanıklık iki yönlü çalışır: oyuncuyu güvenceye alır (yalnız bırakılmıyor) ve hesap verir kılar (kendi içine kaybolmuyor).

**C. Çift geri bildirim — sıra sabit**

Yolculuk tamamlandığında geri bildirim iki turda alınır ve sıra **ters çevrilemez**:

1. **Önce grup — "ne gördük"** — Yazarın Çerçevesi'nin canlı tezahürü; oyuncunun ne yapmaya çalıştığı değil, ne yaptığı. Dışarıdan görülen, nesnel, yorumdan önceki. (Örn. "Hamlet ayağa kalkarken nefesini tuttu, üç adım attı, sonra döndü.")

2. **Sonra oyuncu — "ne yaşadın"** — Senin Çerçeven'in canlı tezahürü; içeriden ne hissedildiği. Öznel, yorumla yüklü. (Örn. "Ayağa kalkarken babamı düşündüm, üç adım Wittenberg'di.")

Sıra ters çevrildiğinde oyuncu önce kendi deneyimini sözle kapatır, sonra grup gözlemi o kapanışa hizmet eden bir okuma haline gelir — bu Yazarın Çerçevesi / Senin Çerçeven ayrımını çökertir (§3.5 ve §3.11 ile çelişir).

**Yazarın Çerçevesi vs Senin Çerçeven ile Bağ**

Çift geri bildirim Yolculuk'un sahne üzerinde **§3.5 Karakter Sayfası Mimarisi'nin ve §3.11 Doğrular Çift Üçlü'nün ayrımının yeniden kurulması** olarak işler:

- **Grup turu = Yazarın Çerçevesi** — dışarıdan görülen veri
- **Oyuncu turu = Senin Çerçeven** — içeriden yaşanan veri

İki çerçeve farklı veridir, birbirinin yerine geçmez. §3.11 bu ayrımı Method Book'ta kuramsal işliyordu; §3.16 sahne geometrisinde operasyonelleştirir.

**Klinik Koruma Protokolü (FKA — onay sonrası detaylanacak)**

Çift geri bildirim sırasında oyuncu, grup turundan sonra "kendi deneyimini" anlatırken **dissosiyatif anı geçişi** riski taşır. Yolculuk yoğunsa, oyuncu "ben Hamlet'ken bunu yaptım" derken karakterle kendisi arasındaki sınırı kaybedebilir.

Olası koruma unsurları (Filiz tarafından şekillendirilecek):
- Oyuncu turundan önce zorunlu topraklanma adımı (en az 2–3 nefes, isim teyidi)
- Eğitmenin "şimdi sen anlat — Hamlet değil, oyuncu" formülasyonu (üçüncü kişi geçişi)
- FKA klinik on-call eşiklerinin (§3.13) bu noktada devreye girmesi

**App Modül III ile İlişki**

App'in Yolculuk Modu **bireysel** kullanımda kalır — oyuncu tek başına, kulaklıkla, kendi alanında. App'in grup transmisyonu yoktur; Karar 14 doğrudan App'i etkilemez. Method Book Bölüm D'de "App'in tek başına kullanımı vs Workshop grup transmisyonu" ayrımı netleşir.
```

---

## 6. Mevcut Alt-Bölümlere Çapraz Atıf Eklemeleri

### 6.1 — §3.1 (Substitution kullanılmaz) sonuna

Mevcut metnin sonunda ("ITC ile ilgili tüm sorular ve materyaller oyuncuyu karakterin dünyasına davet eder — kendi hayatına geri değil.") satırından sonra eklenir:

```markdown
**Atölye/grup transmisyonunda** bu ilkenin canlı koruyucusu §3.13 (Transmisyon Mimarisi) — FKA klinik on-call tetikleyicilerinden biri oyuncunun kendi yarasına kaymasıdır.
```

### 6.2 — §3.3 (Yıldız Profil Eşleşme Matrisi) sonuna

Mevcut "<3: 'Hazır olduğunda' — kilit değil bekleyiş" satırından sonra eklenir:

```markdown
**Travma Matrisi'nin (8×4) §3.15 Karakter Haritası Taksonomisi (yolculuk × çapa × tip) ile karışmadığına dikkat:** Birincisi sahnedeki içeriğin etik yoğunluğunu, ikincisi yolculuk içindeki yapısal konumu sınıflar. Eğitmen sertifikasyonunda (E1) bu ayrımı açıklayabilmek bir kriterdir.
```

### 6.3 — §3.4 (Topraklanma Protokolü) sonuna

Mevcut "Kapanış cümlesi: 'Karakter orada — ben buradayım.'" satırından sonra eklenir:

```markdown
**Atölye ortamında** bu protokol §3.13 (Transmisyon Mimarisi) klinik on-call pozisyonundan uygulanır — FKA tetikleyici (3+ dk dissosiyatif belirti, anı geçişi, BE sezgisi durdurma) aktive olduğunda devreye girer. Bireysel App kullanımında ise §3.4 doğrudan oyuncuya kullanılır.
```

### 6.4 — §3.5 (Karakter Sayfası Mimarisi) sonuna

Mevcut "**Not:** Modül II Hamlet refactor sonrası..." paragrafından sonra eklenir:

```markdown
**Mimarinin sahne karşılığı:** Yazarın Çerçevesi / Senin Çerçeven ayrımı sahne üzerinde §3.16 Yolculuk Geometrisi'nin çift geri bildirim turlarında canlanır.
```

### 6.5 — §3.7 (Altı Kabul) sonuna

Mevcut "6. Zihin-beden bütünlüğü." satırından sonra eklenir:

```markdown
**Kabul 1'in operasyonel görünürlüğü:** Grup transmisyonunda Kabul 1'in kohort ölçeğindeki karşılığı §3.14 Tek Karakter İlkesi'dir — kohort aynı karakteri farklı kapılardan analiz ederek Kabul 1'i + Kabul 5'i (kişiye özel kapılar) canlı görür.
```

### 6.6 — §3.11 (Doğrular Çift Üçlü) sonuna

Mevcut "#### G. Çapraz Etki" bölümünün altındaki son madde (Workshop) sonuna eklenir:

```markdown
**Sahne karşılığı:** Yazarın Çerçevesi / Senin Çerçeven ayrımı §3.16 Yolculuk Geometrisi'nin çift geri bildirim turlarında sahne üzerinde canlanır.
```

---

## 7. §4 (Çapraz Geçişler) — Workshop Bölümlerinde Minimal Güncelleme

### 7.1 — §4.5 (Method Book ↔ Workshop) tablosunun en altına ekleme

Mevcut tablonun son satırı ("F (Ekler — Karaktere Hazırlık Soruları) | Atölye katılımcı çalışma kitabı (kâğıt formunda)") altına eklenir:

```markdown
| D (Etik & Eğitmen) — Transmisyon mimarisi | §3.13 üzerine kurulu; klinik on-call tetikleyicileri akademik dille açar (FKA imzalı) |
| C (Modül III) — sahne geometrisi | §3.16 üzerine kurulu; klinik koruma protokolü akademik dille (FKA imzalı, onay sonrası) |
```

### 7.2 — §4.6 (Workshop ↔ ITC App) sonuna ek paragraf

Mevcut "**B2B/Kurumsal pilot:** Workshop kit + App lisansı paket olarak satılabilir." satırından sonra eklenir:

```markdown
**Geometri farkı:** App Modül III bireysel kullanım — kulaklıkla, kendi alanında. Workshop Modül III grup transmisyonu — sahnede, tanıklıkta, çift geri bildirimde (§3.16). İki kullanım birbirini tamamlar, birbirinin yerine geçmez. Method Book Bölüm D bu ayrımı açıkça işler.
```

### 7.3 — §4.7 (Workshop ↔ Hamlet Workbook) sonuna ek satır

Mevcut listenin son maddesinden ("A2 amiral gemisi atölyesi: Hamlet veya Macbeth vakası işlenirken Workbook bir 'yayımlanmış vaka' referansı olarak kullanılır") sonra eklenir:

```markdown
- **Karakter haritası tutarlılığı:** Workbook'taki 13 bölüm · 5 çapa · A/B/C/D tipler yapısı §3.15 ile kanon olarak teyit edildi. Workshop dokümantasyonu bu yapıyı `Hamlet · Bölüm IX · Tip A · Çapa No 3` formatında atıflarla kullanır. 2. baskıda TOC eşleştirmesi yapılırken bu işaretler görünür hâle gelir.
```

---

## 8. §5 (Açık Karar Noktaları) Güncellemesi

### 8.1 — "v1.3'te çözülen kararlar" başlığı güncellenir

Mevcut:
```markdown
### ✓ v1.3'te çözülen kararlar (artık §3 ve §4'e taşındı)
```

Yeni:
```markdown
### ✓ v1.3 – v1.6'da çözülen kararlar (artık §3 ve §4'e taşındı)
```

### 8.2 — Çözülen kararlar listesine ek satırlar

Mevcut son maddeden ("Karaktere Hazırlık Soruları yapısı: ✓ 9 adım × 3 Giriş Kapısı haritası") sonra eklenir:

```markdown
- Workshop atölye eğitmen modeli: ✓ BE × FKA eş eğitmenlik beş katmanlı (§3.13, Karar 11, v1.6)
- Workshop grup kohort yapısı: ✓ Tek karakter ilkesi, B1 istisnası A2 mezunu önkoşulu (§3.14, Karar 12, v1.6)
- Karakter haritası taksonomisi: ✓ Yolculuk × Çapa × Tip kanon (§3.15, Karar 13, v1.6)
- Yolculuk Modu sahne geometrisi: ✓ Sahnede · tanıklıkta · çift geri bildirim sıra sabit (§3.16, Karar 14, v1.6, Filiz onayı bekleniyor)
```

### 8.3 — Workshop açık kararlarına yeni madde

Mevcut Workshop açık kararları listesinin altına eklenir:

```markdown
- **Solo eğitmen senaryosu** (bireysel pilotlar için): Karar 11 BE × FKA eş eğitmenliği standartlaştırdı. Bireysel oyuncu pilotları için solo eğitmen seçeneği nasıl yapılandırılır — FKA on-call uzaktan video mu, yoksa Modül III bloğu kaldırılır mı?
- **Macbeth Workbook benzeri kanon dokümanı:** Macbeth atölyesi açılmadan önce Doğrular + Timeline + Çerçeveler + Yolculuk × Çapa × Tip (§3.15) içeren bir kanon dokümanı yazılmalı (Macbeth Timeline temel alınabilir)
- **§3.16 Filiz klinik onayı:** Yolculuk Geometrisi çift geri bildirim sırasındaki klinik koruma protokolü Filiz tarafından detaylandırılacak — onay sonrası §3.16 provisional flag'i kalkar
```

---

## 9. §6 Sürüm Geçmişi'ne v1.6 Satırı

Mevcut v1.5 satırının **üstüne** (en yeni en üstte) eklenir:

```markdown
- **v1.6** — 12 Mayıs 2026 — Workshop Geri Besleme Paketi: dört yeni alt-bölüm eklendi. §3.13 Transmisyon Mimarisi (BE × FKA eş eğitmenlik, Karar 11). §3.14 Tek Karakter İlkesi (Karar 12). §3.15 Karakter Haritası Taksonomisi (Yolculuk × Çapa × Tip, Karar 13). §3.16 Yolculuk Geometrisi (sahne · tanıklık · çift geri bildirim, Karar 14 — **Filiz klinik onayı bekleniyor, provisional**). §3.1, §3.3, §3.4, §3.5, §3.7, §3.11'e çapraz atıflar. §4.5, §4.6, §4.7'ye Workshop güncellemeleri. v1.3–v1.5 intro/footer kozmetik temizlik. Decision Log Karar 11–14 kayıtları.
```

---

## 10. Footer Düzeltmesi

### Mevcut (Spine son satırlar)

```markdown
*— ITC Ekosistem Spine v1.3 sonu —*
*Inside The Character · Beyti Engin × Filiz Kaya Ataklı · Mayıs 2026*
```

### Yeni

```markdown
*— ITC Ekosistem Spine v1.6 sonu —*
*Inside The Character · Beyti Engin × Filiz Kaya Ataklı · Mayıs 2026*
```

---

## Yedirme Sırası ve Commit Stratejisi

Aşağıdaki sıralama önerilir (karar-yedirme skill'inin "her dosya ayrı commit" desenine uyar):

1. **Commit 1:** `kararlar/2026-05-12-workshop-geri-besleme-paketi/` klasörü oluşturulur, içine `00-README.md`, `01-decision-log-eklentisi.md`, `02-spine-guncellemesi.md`, `03-brief-v2-guncellemesi.md` dosyaları konur.
   `git commit -m "kararlar: 12 Mayıs 2026 Workshop geri besleme paketi eklendi (Karar 11–15)"`

2. **Commit 2:** `decision-log.md` güncellenir — dört yeni kayıt en üste yapıştırılır, "Son güncelleme: 12 Mayıs 2026" üst meta, ÖNEMLİ TARİHLER tablosuna iki satır.
   `git commit -m "decision-log: Workshop geri besleme paketi Karar 11–14 eklendi"`

3. **Commit 3:** `spine.md` güncellenir — bu dosyadaki 1–10 numaralı bütün müdahaleler tek seferde uygulanır (intro, §3.13–3.16, çapraz atıflar, §4 güncellemeleri, §5, §6, footer).
   `git commit -m "spine: v1.5 → v1.6, §3.13–3.16 eklendi, çapraz atıflar + footer temizlik (Workshop geri besleme)"`

4. **Commit 4:** `brief-v2.md` güncellenir — `03-brief-v2-guncellemesi.md`'deki HMDK tarih düzeltmesi (Karar 15) uygulanır, sürüm v2.0 → v2.1.
   `git commit -m "brief: v2.0 → v2.1, HMDK Stuttgart pilotu Faz 3 → Faz 2 (25-29 Ocak 2027)"`

5. `git push`

Bu sıralama her commit'i atomik tutar — biri başarısız olursa diğerlerini geri çekmek gerekmez.

---

*Spine güncellemesi sonu. Filiz onay paketi ayrıca hazırlanacak — Karar 11/12/13/14 dört maddesi birlikte tek bir klinik teyit turunda sunulur.*
