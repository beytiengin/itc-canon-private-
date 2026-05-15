# Karar 21 — Yıldız Oyuncu Matrisi ve Travma Sistemi Ayrılması

**Bu dosya decision-log.md'ye yedirilen ana karar metninin arşiv kopyasıdır.**

---

## 15 Mayıs 2026 — Yıldız Oyuncu Matrisi ve Travma Sistemi Ayrılması (Karar 21)

**Tip:** Tip 1 — Kanon Değişikliği
**Etkilenen katmanlar:** Tüm ekosistem (Method Book + Workbook + App + Workshop + Etik Çerçeve)
**Spine sürümü:** v1.8 → v1.9 (§3.3 yeniden tanımı + §3.4 tetikleyici güncellemesi + §3.9 pedagojik genişleme)
**Karar veren:** Beyti Engin + Filiz Kaya Ataklı (eş onaylı)
**Tasarım eş yazımı:** Claude (Anthropic)
**Tetikleyici:** App'in temel yapısı incelendiğinde Yıldız Oyuncu Matrisi'nin yalnızca psikolojik boyutunun travma erişim eşiği olarak kullanıldığı, matrisin 6 boyutlu pedagojik amacının sistemde karşılığı olmadığı tespit edildi.

### Karar

Yıldız Oyuncu Matrisi ile Travma Sistemi arasındaki bağ **tamamen koparılır**. Mevcut "Yıldız Profil Eşleşme Matrisi" (Spine §3.3 alt-bölümü, v1.0'dan beri kanonik FKA klinik tasarımı) ekosistemden geri çekilir. Yeni mimari üç bağımsız sistem üzerine kurulur:

1. **Yıldız Oyuncu Matrisi (§3.9):** Sadece *pedagojik* araç. 6 boyutlu öz-farkındalık haritası + karaktere yaklaşım önerileri katmanı (VAK'ın `vakDili` örüntüsünde). Travma sistemi üzerinde hiçbir etkisi yok.

2. **Travma Matrisi (§3.3, yeni tanım):** 8 kategori × 4 yoğunluk; sahne-level etiketleme ve oyuncuya **uyarı** sistemi. Oyuncu profilini hesaba katmaz; karakter verisi olarak metinden çıkarılır.

3. **Topraklanma Protokolü (§3.4):** Yoğunluk 2 (Tanıklık) ve 3 (İcra) seviyesindeki sahneler sonrası otomatik önerilir/tetiklenir. Tetikleyici sahne-içeriği temellidir; oyuncu profili etkilemez.

### Gerekçe

ITC çekirdek ilkesi (§3.1 Substitution Yasağı): *"Karakter senin kişisel travmalarınla inşa edilmez. Karakterin kendi verisi vardır. Sahip değil — misafir."*

Mevcut Yıldız Profil Eşleşme Matrisi dolaylı olarak şu yapıyı kuruyordu: *Oyuncunun psikolojik kapasitesi karaktere erişimini belirler*. Bu yapı Substitution Yasağı ile gerilim içindeydi — oyuncu profili karakter verisinin önüne geçiyordu. App tarafında bu, "psikolojik boyuta 5 veren herkesi 'açık' diye işaretleyen" bir tek-eksen gate'e indirgenmişti; yıldız matrisinin asıl pedagojik amacı (öz-farkındalık + karaktere çoklu eksenden yaklaşım) eclipse oluyordu.

Yeni mimari iki kapıyı birden açar:

- **Karakter, oyuncudan bağımsız bir veri yapısıdır.** Travma kategorileri ve yoğunluklar metinden saptanır; oyuncuya uyarı olarak gösterilir, kilit olarak değil.
- **Yıldız, karakteri çalışma biçimini şekillendirir, karaktere erişim hakkını değil.** VAK gibi: dominant kanal bilgisi çalışma yöntemini seçer, kapı açıp kapamaz. Yıldız 6 boyutu da aynı şekilde çalışır — güçlü eksenler "açık kapı", zayıf eksenler "destek önerisi" üretir.
- **Klinik güvenlik (topraklanma) sahne içeriğinin doğal sonucu olarak ortaya çıkar.** Profile bakmaksızın yoğunluk 2-3 sahneler sonrası tetiklenir.

Bu konumlandırma ITC felsefesine daha sadık. Filiz Kaya Ataklı'nın 2005'ten beri kanonik klinik tasarımı olan Yıldız Profil Eşleşme Matrisi'nin geri çekilmesi **kendi eş kurucu onayıyla** yapılmaktadır.

### Uygulama Detayları

**Spine (v1.8 → v1.9):**

- §3.3 başlığı ve içeriği yeniden yazıldı — eski "Yıldız Profil Eşleşme Matrisi" alt-başlığı kaldırıldı; yeni başlık "Sahne-Level Etik Uyarı". Travma Matrisi 8×4 sahne-level uyarı sistemi olarak ifade edildi; psikolojik puan eşikleri silindi
- §3.4 Topraklanma Protokolü — tetikleyici "yoğunluk 2 (Tanıklık) ve 3 (İcra) sahneler sonrası otomatik" olarak güncellendi (kategori-bağımsız, profil-bağımsız)
- §3.9 Yıldız Oyuncu — "psikolojik boyut travma erişim eşiğini belirler" atıfı kaldırıldı; pedagojik vurgu güçlendirildi; **"Karaktere Yaklaşım Katmanı"** yeni alt-katman olarak eklendi
- §1 ekosistem haritası eş kurucu paragrafından "Yıldız Profil Eşleşme §3.3" atıfı kaldırıldı
- §3.12 Dijital Araç Sınırı tablosunda Yıldız satırının gerekçesi güncellendi
- §3.13 Modül I birlikte yorumlama paragrafı: psikolojik puan-travma erişim eşiği atıfı kaldırıldı
- §3.17 Yöntem Tarihsel Çizgisi: Filiz klinik altyapı listesinden "Yıldız Profil Eşleşme" çıkarıldı
- v1.9 değişiklik bloğu + sürüm geçmişi satırı

**Etik Çerçeve (`.claude/rules/etik-cerceve.md`):**

- §3 "Yıldız Profil Eşleşme Matrisi" maddesi kaldırıldı
- §2 Travma Matrisi: gate işlevi açıklaması kaldırıldı, uyarı sistemi olarak yeniden ifade edildi
- §4 Topraklanma Protokolü: tetikleyici "yoğunluk 2-3 sahneler" olarak güncellendi

**Terminoloji (`.claude/rules/terminoloji.md`):**

- Yıldız Oyuncu Matrisi satırına kısa açıklama eklendi (pedagojik araç vurgusu + Karar 21 atfı)

**App (sonraki iş paketinde — bu kararla uygulanmadı):**

- `app/app/lib/travma.js` `sahneErisimi()` fonksiyonu `sahneUyarisi()` ve `topraklanmaGerekli(yogunluk)` olarak ikiye ayrılır; yıldız parametresi kaldırılır
- Karakter sayfalarında (willy/macbeth/biff) `psikolojikPuan` props'u kaldırılır; karakter sayfaları doğrudan tüm `yildiz` objesi alır
- `app/app/lib/kalibrasyon.js`: yeni `yildizYaklasimi(yildiz, karakter)` fonksiyonu — VAK'ın `vakDili` örüntüsünde 6 eksen için karaktere yaklaşım önerileri üretir
- `components/ZihinselAntrenman.js`, `components/SeninCerceven.js`: gate mantığı kaldırılır
- UX metinleri (kalibrasyon/yildiz sayfaları): "psikolojik kapasiten travma erişimini belirler" çerçevelemesi kaldırılır

**Workbook (2. baskı):**

- Errata listesine: Yıldız Profil Eşleşme atıflarının revize edilmesi (1. baskıda varsa)

**Workshop:**

- HMDK Stuttgart ve Berlin pilot paketlerinde Yıldız sunumu güncellenir (gate öncesi pedagojik harita olarak)

### Notlar

- Filiz Kaya Ataklı'nın 2005'ten beri kanonik klinik tasarımının bir parçasının geri çekilmesi, kendi eş kurucu onayıyla yapılmaktadır.
- Topraklanma protokolü yoğunluk 0 (Yok) ve 1 (Atıf) sahneler sonrası **otomatik tetiklenmez** — atıf seviyesi etik koruma gerektirmez (oyuncu istediği zaman manuel başlatabilir).
- Yıldız 6 boyutu Modül I'in canlı kanonik testi olarak korunur (§3.9). Yalnızca **kullanım amacı** değişti: gate değil, pedagojik yaklaşım.
- Karar 20 (Tarihsel Çizgi) decision-log girişi içindeki Filiz klinik altyapı listesi **tarihsel kayıt** olarak değiştirilmez — o tarihteki kanon durumu doğrudur. Güncel kanonu yansıtan Spine §3.17 metni Karar 21'i içerecek şekilde güncellenir.
