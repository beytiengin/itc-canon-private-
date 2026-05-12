# ITC EKOSİSTEM — DECISION LOG

**Sahibi:** Beyti Engin
**Klinik & Akademik Eş Sahip:** Filiz Kaya Ataklı
**Operasyonel Eş Yazar:** Claude (Anthropic)
**Başlangıç:** 6 Mayıs 2026
**Son güncelleme:** 8 Mayıs 2026

---

## Bu Dosyanın Amacı

Brief v2 §6.5'te tanımlandığı gibi, ITC ekosisteminde verilen **her stratejik karar** burada loglanır. Yapısal kararlar, kanon değişiklikleri, içerik güncellemeleri, açık kararların çözümü — hepsi.

Amaç:
- Beyti yalnız çalışırken kararların **kayda geçmesi**
- Dört katmanın (Method Book / Workbook / App / Workshop) **birbirini güncellemesi** için tetikleyici sistemler
- Filiz onayı gereken kararların **dökümante edilmesi**
- Geriye dönük "ne zaman, niçin" sorularının **cevaplanabilmesi**

## Format

Her kayıt şu yapıda olur:

```markdown
## [Tarih] — [Kısa başlık]

**Tip:** Kanon Değişikliği / Yapısal Karar / İçerik Güncellemesi / Açık Karar Çözüldü
**Etkilenen katmanlar:** Method Book / Workbook / App / Workshop
**Spine sürümü:** vX.Y → vX.Z
**Karar veren:** Beyti / Filiz / Beyti+Filiz
**Karar:** [karar metni]
**Uygulama tarihi:** [hangi milestone'da uygulanır]
**Notlar:** [varsa ek not]
```

## Tip Tanımları (Brief v2 §6.2)

- **Tip 1 — Kanon Değişikliği** (Yüksek Öncelik): Spine §3'teki sabit ilkeler değişti
- **Tip 2 — Yapısal Karar** (Orta Öncelik): Bir projede yapısal karar verildi
- **Tip 3 — İçerik Güncellemesi** (Düşük Öncelik): İçerik değişti, yapı aynı kaldı
- **Tip 4 — Açık Karar Çözüldü** (Orta Öncelik): Spine §5'teki açık kararlardan biri çözüldü

---

# KARARLAR

---

## 8 Mayıs 2026 — Doğrular Çift Üçlü Yapısı: Kaynak × Katman (Karar 10)

**Tip:** Kanon Genişlemesi (Tip 1)
**Etkilenen katmanlar:** Method Book + Workbook + App + Workshop
**Spine sürümü:** v1.4 → v1.5
**Karar veren:** Beyti
**Tasarım eş yazımı:** Claude (Anthropic)
**Etkili §:** §3.11 (genişletiliyor — eski "Doğrular Üç Kaynak" tek üçlüden iki üçlüye çıkar)

### Karar

Değiştirilemez Doğrular tek üçlüyle değil, **iki ayrı eksende duran iki üçlü** ve onları birleştiren bir matrisle çalışılır. Tek üçlü, doğrunun çift karakterini gizler.

**A. Kaynak Üçlüsü** — *Doğru nereden geliyor?* (oyuncuya **tartışma alanını** verir)
1. **Metin içi · doğrudan** — yazarın açıkça yazdığı, yoruma kapalı
2. **Süreç içi · örtük** — metnin akışından çıkan, sözle ifade edilmeyen
3. **Yaratımsal · sahnelemeye bağlı** — yönetmen/dramaturg/oyuncu ortak kararıyla kurulan

**B. Katman Üçlüsü** — *Doğru neye dair?* (oyuncuya **çalışma yerini** verir)
1. **Metinsel** — replikte, sahne yönergesinde yaşar
2. **Dramaturjik** — dünyanın yapısında: olay örgüsü, tarih, mekân, sosyal bağlam
3. **Zihinsel Sabit** — karakterin iç inanç sisteminde: kararlar, ilkeler, gramer

İki üçlü çapraz eksenlerde durur — biri kaynak otoritesini, diğeri ontolojik katmanı sınıflar. Birlikte 3×3 matris oluştururlar.

### Çift Üçlü Matrisleri Arasındaki Ayrım (kritik)

ITC içinde artık iki ayrı 3×3 matris kanondur ve **karışmamalıdır**:

- **Spine §3.10 — VAK × Giriş Kapıları (Karar 9):** oyuncunun kalibrasyon × karaktere erişim ekseni
- **Spine §3.11 — Kaynak × Katman (bu karar):** doğrunun kaynağı × ontolojik düzeyi ekseni

İlk matris "oyuncu nasıl çalışır", ikinci matris "doğru neye benziyor" sorusuna cevap verir. İkisi farklı modüllerde, farklı pedagojik amaçlarla işler.

### Gerekçe

Karar 3 (8 Mayıs sabah, Spine §3.10 → şimdi §3.11) Doğruları üç katmana ayırmıştı: Metinsel · Dramaturjik · Zihinsel Sabit. Bu kanon Macbeth ve Willy gibi karakterler için iç inanç sistemlerinin (Zihinsel Sabit) belirleyiciliğini doğru yakalıyordu.

Hamlet Workbook v1.0 s.50-57'de ise farklı bir üçlü kullanılıyordu: Metin içi · Süreç içi · Yaratımsal. İlk bakışta bu iki üçlü çatışıyor sanıldı; tartışmada keşfedildi ki **farklı sorulara cevap veriyorlar**. Workbook'unki "doğru nereden geliyor" (kaynak otoritesi), Karar 3'ünki "doğru neye dair" (ontolojik katman) sorusunu sınıflıyor.

İkisi çapraz eksenler. Birlikte 3×3 matris oluşturuyorlar. Tek üçlü bilgi kaybıdır — oyuncu hem *tartışma alanını* (kaynak) hem *çalışma yerini* (katman) bilmek zorundadır.

### Hamlet Çapraz Okuma Örnekleri

|                                  | **Metinsel** | **Dramaturjik** | **Zihinsel Sabit** |
|----------------------------------|--------------|-----------------|---------------------|
| **Metin içi · doğrudan**         | Hamlet prens; Wittenberg mektubu | Cenaze ve düğün arasında 2 ay | "Bana düşmez olaydı dünyayı düzeltmek" |
| **Süreç içi · örtük**            | Polonius'un kontrol dili | Saray Wittenberg'i geride bıraktı | Hamlet için intikam ahlaken muğlak |
| **Yaratımsal · sahnelemeye bağlı** | "Olmak ya da olmamak"ın yeri | Modern dönem mi, Rönesans mı? | Hamlet ateist mi, dindar mı? |

### Macbeth Çapraz Okuma Örnekleri

- "Kader yazılmıştır" inancı → Kaynak: **Süreç içi · örtük** × Katman: **Zihinsel Sabit**
- Cawdor beyliğinin verilmesi → Kaynak: **Metin içi · doğrudan** × Katman: **Dramaturjik**

### Pedagojik Sıralama (kademeli öğretim)

İki üçlü aynı anda öğretilmez:

1. **Başlangıç** (Workbook, atölye D1): Kaynak Üçlüsü tek başına çalışılır
2. **Orta-seviye** (Method Book §III/Aşama 1, atölye D2): Katman Üçlüsü tanıtılır, Kaynak ile ilişkisi açıklanır
3. **İleri** (Method Book §III/Aşama 1 derinleşmesi, atölye C2): Matris bütünüyle uygulanır

### Uygulama

- **Spine v1.4 → v1.5:**
  - §3.11 yeniden tanımlanır: "Doğrular Çift Üçlü ve 3×3 Matris" (Kaynak Üçlüsü eklenir, Katman Üçlüsü korunur, matris formüle edilir)
  - Spine §3.11 başlığına "**Karar 9'daki VAK × Giriş Kapıları matrisinden farklı bir eksen — karışmamalıdır**" notu eklenir
  - Sürüm Geçmişi'ne v1.5 satırı

- **Method Book Master Outline v3:**
  - Bölüm III/Aşama 1 (Doğrular bölümü) bu çift üçlüyü merkez kavram olarak işler
  - Hamlet ve Macbeth vakaları matrisle gösterilir
  - Tahmini boyut: ~8-10 sayfa

- **Workbook v1.0 s.51:**
  - Kaynak Üçlüsü **olduğu gibi korunur** (kavramsal kayıp yok)
  - 2. baskıda yan kutu/sayfa eklenir: "Bu doğruları çalışırken her birinin **neye dair** olduğunu da düşün — Method Book §III/Aşama 1, Katman Üçlüsü." Çapraz referans kurulur.
  - Bu Workbook 2. baskı errata listesine işlenir (önceki "terminoloji uyumlama" maddesi iptal — kanon zaten uyumlu, sadece çapraz referans gerekli)

- **App:**
  - Hamlet Doğrular sayfası mimarisi yeniden değerlendirilir (Karar 9'la birlikte düşünülecek — App'te bir sayfa iki matrisi nasıl gösterir, ya da iki ayrı sayfa mı olur)
  - Tasarım kararı Faz 1 küçük revizyonda alınır

- **Workshop Spine v1.2 → v1.3:**
  - D2 (Kuramsal Çerçeve) atölyesinde Çift Üçlü ve Matris bir saat işlenir (Karar 9'un VAK × Giriş Kapıları matrisinden hemen sonra, ayrım netleştirilerek)
  - C2 (Karakter Sayfası Mimarisi) atölyesinde uygulanır
  - E1 sertifikasyonu için: katılımcı bir karakterde her iki matrisi de doldurabilmeli — ve aralarındaki farkı açıklayabilmeli

### Filiz Klinik Onayı

Zihinsel Sabit kategorisinin travma-duyarlı sınırı için Filiz onayı gerekli. Method Book Bölüm III prototip yazımı sırasında alınacak.

Özellikle: Bir karakterin Zihinsel Sabit'i (örn. Macbeth'in "kader yazılmıştır"ı) oyuncu için çalışılırken, oyuncunun kendi inanç sistemine yansıma riski var. Substitution kullanılmaz ilkesiyle (§3.1) tutarlı yapılandırılması Filiz denetiminden geçmeli.

### Notlar

- Bu karar Karar 3'ü **çürütmez, genişletir**. Karar 3'ün metni (Metinsel · Dramaturjik · Zihinsel Sabit) bu kararda Katman Üçlüsü olarak yaşıyor.
- "Yaratımsal · sahnelemeye bağlı" kategorisi (Workbook'un üçüncüsü) Spine'a bu kararla giriyor. Bu kategori Macbeth/Willy/Biff çalışmalarında da kullanılacak.
- Karar 9 (VAK × Giriş Kapıları) ve Karar 10 (Kaynak × Katman) **iki ayrı matristir**. Birinde oyuncu/karakter eksenleri, diğerinde doğrunun yapı eksenleri. Method Book yazımında ve eğitmen sertifikasyonunda bu ayrım defalarca vurgulanmalı.
- Bu karar 8 Mayıs 2026 oturumunun 10. kararıdır. Resmi olarak 12 Mayıs'ta Decision Log'a yedirildi (4 günlük gecikme — Beyti'nin set ve çocuk kitabı çalışması nedeniyle).

---

## 8 Mayıs 2026 — MBTI Modül I'in Kanonik Üç Testinden Biri (3. Test) Olarak (Karar 1)

**Tip:** Kanon Değişikliği (Tip 1)
**Etkilenen katmanlar:** Method Book + App + Workbook (2. baskı) + Workshop
**Spine sürümü:** v1.2 → v1.3
**Karar veren:** Beyti

### Karar

Modül I (Kalibrasyon) artık **üç bağımsız test** üzerine kurulur:
1. VAK — Öğrenme Stili Analizi (27 soru, ~5 dk)
2. MBTI — Kişilik Tipi Analizi (12 senaryo, ~5 dk) **YENİ kanonik konum**
3. Yıldız Oyuncu — 6 Boyut Profili (37 soru, ~7 dk)

MBTI daha önce App Şema'da var olan ama kanonik yeri belirsizdi; bu kararla Modül I'in çekirdek üçlüsünden biri olarak kanonlanır.

### Uygulama

- **Spine v1.3** — §3.9 olarak "Modül I'in Üç Testi" alt-bölümü eklendi
- **Method Book Master Outline v3** — Bölüm C/Modül I üç testle yazılır (her test için yarım sayfa açıklama + pedagojik kullanım)
- **App** — Modül I sayfası üç testi üst düzey içerik olarak gösterir (zaten teknik altyapı hazır, sadece konumlandırma küçük geliştirme)
- **Workbook 2. baskı** — s.31-45 sezgisel temas bölümünün başına "MBTI sonucunu App'ten getir" QR kutusu
- **Workshop** — A2 (Tam Modül atölyesi) Modül I kalibrasyonu üç testle anılır; eğitmen el kitabında her testin amacı ve yorumlaması yer alır

### Notlar

- 2023 Berlin sunumunda MBTI yoktu, 2025 ITC sunumunda merkez kavram. Bu karar 2025 sunumunun kanonlaştırılmasıdır.
- App Şema Bölüm 4.2'deki 12 senaryolu test zaten hazır — MBTI hesaplama altyapısı mevcut.

---

## 8 Mayıs 2026 — Travma Yoğunluğu Kanonik Olarak 4 Seviye (Karar 2)

**Tip:** Kanon Netleştirmesi (Tip 1)
**Etkilenen katmanlar:** Method Book + Workbook (2. baskı) + Workshop
**Spine sürümü:** v1.2 zaten doğru, türev dokümanlar senkronlanacak
**Karar veren:** Beyti (Filiz klinik onayı App Şema Bölüm 6'da zaten alınmış)

### Karar

Travma matrisi formülasyonu **8 kategori × 4 yoğunluk** olarak sabittir.

**Yoğunluk seviyeleri:** 0 Yok · 1 Atıf · 2 Tanıklık · 3 İcra
**Kategoriler:** Şiddet · Kayıp · İhanet · Cinsel · Zihinsel Kırılma · Çocukluk · Ahlaki Yara · Varoluşsal

Önceki dokümanlardaki yanlış formülasyonlar:
- ❌ Method Book Project Instructions §12 — "8 kategori × 3 yoğunluk"
- ❌ Workbook s.20 — "3 düzey"
- ❌ Workshop Spine §4 D1 — "8×3"

Bunlar tek tek düzeltilecek.

### Uygulama

- **Spine v1.3** — §3.2 zaten doğru, dokümante teyit
- **Method Book Master Outline v3** — Bölüm D'de 4 yoğunlukla yazılır; Project Instructions'taki "3 yoğunluk" ifadesi düzeltilir
- **Workbook 2. baskı** — s.20 "4 yoğunluk" olarak güncellenir (tek satır değişikliği)
- **App** — değişiklik yok (zaten 4 seviye kullanıyor)
- **Workshop Spine v1.1** — §4 D1 kart "8×4" olarak güncellenir; §2 omurga listesinde sayı açıkça yazılır

### Notlar

- "0 Yok" seviyesi etik altyapının önemli bir parçası — bazı antrenmanların travmatik içermediğini açıkça işaretlemek için. 0'ı saymadan "3 aktif seviye" demek bu işaretlemeyi kaybeder.
- Klinik gerekçe: Filiz onayı zaten 4 seviyede alınmıştı (App Şema Bölüm 6).

---

## 8 Mayıs 2026 — Doğrular Üç Kaynak Yapısı Kanon (Karar 3)

**Tip:** Kanon Değişikliği (Tip 1)
**Etkilenen katmanlar:** Method Book + App + Workbook + Workshop
**Spine sürümü:** v1.2 → v1.3
**Karar veren:** Beyti

### Karar

Değiştirilemez Doğrular her zaman üç kaynaktan çıkarılır:

1. **Metinsel Doğrular** — yazarın doğrudan verdiği bilgiler (replikler, sahne yönergeleri, açık karakter tanımları)
2. **Dramaturjik Doğrular** — olay örgüsü, tarih, mekân, sosyal bağlam gibi verilerden çıkarılan sabitler
3. **Zihinsel Sabitler** — karakterin kendi iç dünyasında taşıdığı inançlar, kararlar, ilkeler (örn. Macbeth'in "kader yazılmıştır" inancı)

Spine §3'e §3.10 olarak eklenir. 2025 ITC sunumunda yapılaştırılmış olan bu üçlü, ITC'nin omurga kavramlarından biri olarak kanonlaşır.

### Uygulama

- **Spine v1.3** — §3.10 olarak eklendi; Workbook s.50-57 zaten bu yapıyı kullanıyor, kanon teyidi
- **Method Book Master Outline v3** — Modül II/Aşama 2 bu üçlü etrafında yazılır
- **App** — Hamlet Doğrular sayfası 3 sütun/sekme yapısıyla yeniden tasarlanır (Faz 1 küçük geliştirme)
- **Workshop** — A2 ve C2 atölyelerinde Doğrular bölümü bu üçlü ile öğretilir

### Notlar

- "Zihinsel Sabitler" terimi karışıklık yaratabilir: oyuncunun değil, karakterin zihninde sabit olan ilkeleri ifade ediyor.

---

## 8 Mayıs 2026 — Modül III Yapısı: Tek Modül + Performans Blokajları Ek Bölüm (Karar 4)

**Tip:** Yapısal Karar (Tip 2)
**Etkilenen katmanlar:** Method Book + App + Workshop
**Spine sürümü:** v1.2 → v1.3
**Karar veren:** Beyti

### Karar

Modül III tek bir modüldür: **Zihinsel Canlandırma + Akış + Güvenli Çıkış** kapsar. Akış kendi başına bir modül değil, Modül III'ün bir katmanıdır (Csikszentmihalyi referansı).

Performans Blokajları, Modül III'ün **dışında** bir ek bölüm olarak konumlanır — Method Book'ta C-Ek olarak. Eğitmen bağlamsal olarak işler.

### Yapı

```
A. Giriş
B. Birinci Bölüm: Felsefe
C. İkinci Bölüm: Üç Modüllü Sistem
   ├── Modül I — Kendini Tanı (Kalibrasyon)
   ├── Modül II — Karakter Dramaturjisi
   └── Modül III — Zihinsel Canlandırma, Akış ve Güvenli Çıkış
C-Ek. Performans Blokajları ve Çözümleri ← yeni ek bölüm
D. Üçüncü Bölüm: Etik Altyapı ve Eğitmen Rehberliği
E. Dördüncü Bölüm: Uygulama Vakaları
F. Ekler
```

C-Ek içeriği: Tıkanma türleri (zihinsel/bedensel) · belirtiler · tetikleyiciler · kas belleği · merkezleme egzersizi · eğitmenin müdahale rehberi.

### Uygulama

- **Spine v1.3** — §2 Method Book yapı bölümü güncellenir (C-Ek eklenir)
- **Method Book Master Outline v3** — yeni yapı yansıtılır
- **App** — eğer Blokajlar bir araç olarak App'e gelecekse Modül III dışında, Profil/Kalibrasyon yanında bir "Blokaj Aşma" sekmesi olarak konumlanır (henüz tasarım kararı yok, açık)
- **Workshop Spine v1.1** —
  - A2 (Tam Modül atölyesi) "Modül III (Akış, Topraklanma, Sahneleme)" → "Modül III (Canlandırma, Akış, Güvenli Çıkış)" olarak düzeltilir
  - C3 (Akış & Performans Atölyesi) konumlandırma cümlesi yenilenir: "Modül III'ün Akış katmanı + dışarıdaki Performans Blokajları bölümünün ortak atölyesi"
  - §8 üretim sırası gerekçesi: "C3, Modül III'ün Akış kısmından + ek bölümden türetilebilir"

### Notlar

- Bu karar 2025 ITC sunumunun "iki ayrı bölüm" sunumunun yanlış okunmasını engeller — Modül III bütündür, sadece Blokajlar bağımsız bir araç olarak ayrılır.
- Workshop projesindeki `Inside_The_Character_Akis_Modulu_FINAL.docx` Akış'ı bağımsız modül gibi ele alıyordu — bu doküman Modül III alt-bölümü olarak yeniden konumlanır, ayrı modül değildir.

---

## 8 Mayıs 2026 — Yıldız Oyuncu 6 Boyut Kanon (Karar 5)

**Tip:** Kanon Değişikliği (Tip 1)
**Etkilenen katmanlar:** Method Book + App + Workshop
**Spine sürümü:** v1.2 → v1.3
**Karar veren:** Beyti

### Karar

Yıldız Oyuncu profili 6 boyut üzerinden ölçülür:

1. **Teknik** — beden, ses, hareket, sahne becerileri
2. **Psikolojik** — duygusal regülasyon, travma erişim eşiği (§3.3 ile bağlı)
3. **Mesleki** — kariyer, ağ, ekonomik dayanıklılık
4. **Yaratıcı** — özgün ses, sanatsal cesaret
5. **Entelektüel** — okuma, analiz, dramaturji
6. **İlişkisel** — yönetmen-oyuncu, ekip içi çalışma

App'teki 37 soruluk testle ölçülür. Psikolojik puan §3.3 Yıldız Profil Eşleşme Matrisi'nin eşik mekanizmasını besler.

### Uygulama

- **Spine v1.3** — §3.9 altında Yıldız Oyuncu 6 boyut olarak işlenir
- **Method Book Bölüm F** — Yıldız Oyuncu kavramsal açıklama + 6 boyut tanımları + App QR kodu (test formu App-only)
- **App** — sonuç ekranı 6 boyut radar grafiğiyle gösterir
- **Workshop A2** — Modül I bloğunda 6 boyut eğitmen el kitabıyla yorumlanır

---

## 8 Mayıs 2026 — Workshop Dördüncü Katman Olarak Ekosisteme Eklendi (Karar 6)

**Tip:** Kanon Değişikliği (Tip 1) + Yapısal Karar (Tip 2)
**Etkilenen katmanlar:** Tüm ekosistem (Spine §1)
**Spine sürümü:** v1.2 → v1.3
**Karar veren:** Beyti

### Karar

ITC ekosistemi artık dört katmandan oluşur:

1. **Method Kitabı** — kavramsal otorite (akademi, eğitmenler)
2. **Hamlet Workbook** — derin pratik (tek karaktere)
3. **ITC App** — günlük dijital pratik (bireysel)
4. **Workshop** — yöntemin operasyonel mimarisi (eğitmen, kurum)

Workshop, Method Book'un D bölümünden (Eğitmen Rehberliği) türeyen bir uygulama katmanıdır. D bölümü kavramsal, Workshop operasyonel — eğitmenin elinde fiilen kullandığı program kiti.

### Konumlandırma

"Ticari ama akademik duran" üç katmandı; dördüncü katman (Workshop) kurumsal ölçeklenmenin omurgasını ekler. HMDK Stuttgart, Royal Central, Berlin Chubbuck, Stella Adler, USC, İstanbul Bilgi gibi kurumsal pilotlar Workshop katmanı üzerinden yürür.

### Uygulama

**Spine v1.3:**
- §1 (Ekosistemin Haritası) "üç katman" → "dört katman" olarak güncellenir
- §2 (Üç Projenin Güncel Durumu) → "Dört Projenin Güncel Durumu" olur, Workshop için bir blok eklenir
- §4 (Çapraz Geçişler) yeni alt bölümler eklenir:
  - §4.5 Method Book ↔ Workshop
  - §4.6 Workshop ↔ App
  - §4.7 Workshop ↔ Workbook

**Workshop Spine v1.0 → v1.1** — Ekosistem Spine v1.3'ten omurga miras alır.

### Notlar

- Brief v2'nin §10.4 (Akademik) hedefleri Workshop ile güçlenir: HMDK Stuttgart pilotu Workshop A2 + B1 atölyeleriyle yürütülebilir; kurumsal müşteri ($5K+/yıl) Workshop ürünüdür.
- Workshop'un kendi açık kararları (program süreleri, eğitmen sertifikasyonu, vs.) Workshop sohbetinde ayrı yönetilir — bu Decision Log'a Workshop'a özel kararlar Workshop sohbetinde verilince eklenir.

---

## 8 Mayıs 2026 — Dijital Araç Sınırı İlkesi + İkinci Uygulama (Karar 7)

**Tip:** Yapısal Karar (Tip 2) + Açık Karar Çözüldü (Tip 4)
**Etkilenen katmanlar:** Method Book (Bölüm F) + Workshop
**Spine sürümü:** v1.2 → v1.3
**Karar veren:** Beyti

### Karar

İki dijital ek için karar verildi:

- **Karaktere Hazırlık Soruları** (Filiz Kaya 2016 belgesi temelli + 2023 Berlin 9 adımlık akış katmanı) → Method Book Bölüm F'de yer alır.
- **Öğrenci Defteri (4 Aşama)** → Method Book Bölüm F'de yer alır.

Bu kararlarla birlikte genel ilke ortaya çıktı:

**Dijital Araç Sınırı İlkesi:** Yalnızca dijital ortamda anlamlı çalışan araçlar (kişisel test, profil hesaplama, kalibrasyon sonucu üreten testler) App-only olur. Bireyin kâğıt üzerinde kendi başına çalışabileceği araçlar (soru havuzları, defterler, formlar) **kitapta yer alır**.

### Karar Dağılımı

| Araç | Yer | Gerekçe |
|---|---|---|
| Yıldız Oyuncu Testi | App-only | Puan hesaplama + travma erişim eşiği üreten algoritmaya bağlı |
| VAK Testi | App-only | Aynı mantık (kanal puanlaması) |
| MBTI Testi | App-only | Aynı mantık (16 tip hesaplama) |
| Karaktere Hazırlık Soruları | Method Book Bölüm F | Soru havuzu — bireyin kâğıt-kalemle çalıştığı araç |
| Öğrenci Defteri (4 Aşama) | Method Book Bölüm F | Yansıma defteri — bireyin kendi yazdığı araç |

Yıldız Oyuncu test formu Method Book Bölüm F'de yer **ALMAZ**. Kitap içinde sadece kavramsal açıklama + 6 boyut tanımları + App'e yönlendirme bulunur. Eğitmen sınıfta uygulamak isterse App üzerinden kullanır.

Workshop'ta da kâğıt üzerinde test formu basılmaz — atölye öncesi katılımcı App Modül I'i tamamlamış olmalı (ön koşul).

### Uygulama

- **Spine v1.3** — §3.11 olarak "Dijital Araç Sınırı İlkesi" eklenir; Method Book açık kararlarından bu birinin çözümü kaydedilir
- **Method Book Master Outline v3** — Bölüm F'den Yıldız Oyuncu test formu çıkarılır, yerine "Kavramsal açıklama + 6 boyut + App QR kodu" konur
- **Workshop Spine v1.1** — A2 ve sonraki atölye kartlarına "Ön koşul: katılımcı App Modül I'i tamamlamış olmalı" satırı eklenir; Workshop Project Instructions §6'ya "Ön koşul (App ön kalibrasyon vb.)?" sorusu eklenir

---

## 8 Mayıs 2026 — Karaktere Hazırlık Soruları 9 Adım × 3 Giriş Kapısı (Karar 8)

**Tip:** Yapısal Karar (Tip 2)
**Etkilenen katmanlar:** Method Book (Bölüm F) + Workshop
**Spine sürümü:** v1.2 → v1.3
**Karar veren:** Beyti

### Karar

Karaktere Hazırlık Soruları, Method Book Bölüm F'de 2023 Berlin 9 adımlık akışı üzerine kurulur ve her adım **Üç Giriş Kapısı (Bilişsel · Bedensel · Duygusal)** haritasıyla yapılandırılır.

### Yapı Şeması

Her adım için:

1. Adım tanımı (2023 Berlin formülasyonu)
2. Hangi kapılardan girilebilir — bir, iki veya üç kapı önerilir
3. Her kapıya özel soru seti:
   - **Bilişsel kapıdan giren oyuncu için:** analitik/yapısal sorular
   - **Bedensel kapıdan giren oyuncu için:** somatik/duyusal sorular
   - **Duygusal kapıdan giren oyuncu için:** ilişkisel/etkilenim soruları
4. **2016 soru havuzu** — ilgili adımı destekleyen 2016 belgesinden sorular, kapı ayrımı yapılmadan referans havuzu olarak

### Adım–Kapı Haritalaması (Taslak)

| Adım | Baskın Kapı(lar) | Notu |
|---|---|---|
| 1. Karakteri Tanıştırma | Bilişsel + Duygusal | "Karşılaştığım inanılmaz biri" — heyecanlı anlatım |
| 2. Karakteri Tanıma | Üç Kapı | 2016 soru kataloğunun ana kullanım yeri |
| 3. Geçmişten Anlık Görüntüler | Duygusal + Bedensel | Anılar üzerinden bedensel iz |
| 4. Mekânların Özü | Bedensel | Oda, nesne, hareket |
| 5. Çekirdek Motivasyon ve Birincil Duygular | Bilişsel | Pattern analizi |
| 6. Karakterin Fiziksel Görünümü | Bedensel | Postür, jest, ritim |
| 7. Çekirdek Düşünceler, İnançlar, Görüşler | Bilişsel | "Şu konuda ne düşünüyorum" listesi |
| 8. Kim Bu Kişi? (1 sayfalık monolog) | Üç Kapı | Sentez |
| 9. Karakteri Günlük Hayatta Deneyimleme | Bedensel + Duygusal | Yarım gün yaşama egzersizi |

Yazım sürecinde Filiz onayı ile nihayete erer.

### Uygulama

- **Spine v1.3** — yapısal karar olarak kaydedilir
- **Method Book Master Outline v3** — Bölüm F'de Karaktere Hazırlık Soruları alt yapısı bu şemaya göre yazılır; yazım fazında: 27 soru seti × adım — büyük yazım işi (estimate ~30-40 sf)
- **Workshop Spine v1.1** — A2 Modül II ve B1 (Kendi Karakterin) atölyelerinin iskeleti bu yapıdır: 9 adım × 3 Giriş Kapısı haritası, atölyenin günlere/oturumlara nasıl dağılacağının ana mimarisini verir; C2 (Karakter Sayfası Mimarisi) atölyesi bu yapıyı eksiksiz öğretir

### Notlar

- 2016 belgesindeki Hikaye / Fiziksel / Sosyal / Psikolojik 4 başlığı korunur ama yapısal değil **referans havuzu** olarak. Her adım altında "İlgili 2016 soruları için bkz. Bölüm F/Soru Havuzu" şeklinde işaret edilir.
- Bu yapı Kabul 5'in (kişiye özel giriş kapıları) Bölüm F'deki uygulamalı kanıtıdır — kitabın iç tutarlılığı için kritik.
- "Adım × Kapı" matrisi App'e de gelebilir gelecekte (Faz 3'te düşünülebilir, şimdi karar değil).

---

## 8 Mayıs 2026 — Yıldız Oyuncu 37 Madde × 6 Boyut Eşleştirme — Eylem Maddesi

**Tip:** İçerik Güncellemesi (Tip 3) — eylem maddesi, kanon kararı değil
**Etkilenen katmanlar:** App + Method Book + Workshop
**Spine sürümü:** v1.3 (eylem listesi)
**Karar veren:** Beyti

### Eylem

Yıldız Oyuncu testinin 37 maddesi (Pozitif Atölye 2015 kaynağından) ile 6 kanonik boyut (Teknik · Psikolojik · Mesleki · Yaratıcı · Entelektüel · İlişkisel) arasındaki eşleştirme tablosu dokümante edilmemiş durumda. App canlıda olduğuna göre puanlama algoritmasında bu eşleştirme mevcut — ama belge olarak çıkarılmamış.

**Yapılacak iş:** App geliştirme tarafındaki eşleştirme mantığı ekosistem-geneli bir tabloya çıkarılacak. Bu tablo:
- App geliştirme dokümantasyonuna eklenir
- Method Book Bölüm F'deki Yıldız Oyuncu kavramsal açıklamasında özet hâli yer alır
- Workshop A2 eğitmen el kitabında detay hâli yer alır

### Uygulama

- Faz 1 içinde tamamlanacak (Brief v2 §9 Faz 1 hedefleri)
- Sorumlu: Beyti (App geliştirme tarafından eşleştirme çıkarılır), Filiz (klinik tutarlılık kontrolü)

### Notlar

- Bu, kanon kararı değil bir dokümantasyon eylem maddesi. Decision Log'da işaretlenmesi, kaybolmaması için.

---

## 8 Mayıs 2026 — Çift Üçlü İlkesi (VAK ≠ Giriş Kapıları)

**Tip:** Kanon Değişikliği (Tip 1)
**Etkilenen katmanlar:** Method Book + Workbook + App + Workshop
**Spine sürümü:** v1.3 → v1.4
**Karar veren:** Beyti
**Etkili §:** §3.10 (yeniden tanımlanıyor; eski §3.10 ve §3.11 bir kademe kayar)

### Karar

ITC içinde iki ayrı üçlü kanon olarak ayrıştırılır. Bu iki üçlü farklı katmanları ölçer, farklı modüllerde operasyonel hale gelir ve karışım önceki dokümanlarda görülmüştür; bu kararla net ayrım kalıcılaşır.

**VAK Üçlüsü — Görsel · İşitsel · Kinestetik**
- Sorduğu soru: Nasıl öğrenirsin?
- Ölçtüğü: Bilgi işleme kanalı (algı–içselleştirme)
- Kanonik yeri: Modül I — Kendini Tanı (Kalibrasyon testi)
- Uygulama: App-only test (27 soru, ~5 dk) — Dijital Araç Sınırı İlkesi gereği
- Pedagojik kullanım: Zihinsel antrenmanların "derinleşme" adımı baskın kanala göre şekillenir
- Dördüncü kanal: **Sezgisel** — VAK üçlüsünün yanına dördüncü olarak konumlanır; algoritmik puanlamaya girmez, gözlemsel okumadır

**Giriş Kapıları Üçlüsü — Bilişsel · Bedensel · Duygusal**
- Sorduğu soru: Karaktere nereden girersin?
- Ölçtüğü: Karaktere erişim kanalı (analiz–temas)
- Kanonik yeri: Modül II — Karakter Dramaturjisi (operasyonel kavram)
- Uygulama: Soru havuzu — kâğıt-kalem (Karaktere Hazırlık Soruları, Method Book Bölüm F)
- Pedagojik kullanım: Türkiye bağlamında "bir gece / bir hafta" sınırı altında en hızlı doğru soruyu bulma
- Üçlü **kapalıdır** — dördüncü kapı yoktur

### 3×3 Matris

İki üçlü çarpılarak operasyonel bir matris üretir: oyuncu profilinin VAK kanalı (3) × Giriş Kapısı (3) = 9 hücre. Bu matris eğitmen için karakter çalışmasına başlama haritası, oyuncu için ise "açık kanaldan açık kapıya" giden somut ipucudur. Detaylı tablo Spine §3.10'da; matrisin Karaktere Hazırlık Soruları (Method Book Bölüm F) ile bağı orada açıklanır.

### Neden Bu Karar Şimdi?

İki üçlü, geçmiş dokümanlarda zaman zaman birbirinin yerine kullanılmıştır. Karışımın klasik biçimi: "VAK'a göre karaktere bedenden giriyor" — oysa "VAK = Kinestetik" ile "Giriş Kapısı = Bedensel" aynı şey değildir. Görsel öğrenen bir oyuncu, karaktere bilişsel kapıdan da girebilir, duygusal kapıdan da. Bu örtüşme zannı pedagojik hata üretir; bu hata Method Book yazımında ve eğitmen sertifikasyonunda en yaygın yanlışlardan biri olacaktır. Karar şimdi kanonlanır ki yazım başlarken kuralsız ilerlemesin.

### Klinik Zemin (FKA)

Giriş Kapısı seçiminin Duygusal'a yanlışlıkla zorlanması (örneğin "duygusal kanalı zayıfsan oradan başla, güçlendir" mantığı) oyuncuyu kendi duygu havuzuna geri çekme riski yaratır. Üç kapı arasında özgür dolaşım, oyuncunun karakterin verisinde kalmasını korur. Bu açıdan Çift Üçlü ayrımı sadece pedagojik değil aynı zamanda etik bir kanondur — Substitution kullanılmaz ilkesi (§3.1) ile doğrudan bağlıdır.

### Uygulama

**Spine v1.3 → v1.4:**
- §3.10 yeniden tanımlanır: "Çift Üçlü İlkesi ve 3×3 Matris" (bkz. `02-spine-3-10-guncellemesi.md`)
- Eski §3.10 (Doğrular Üç Kaynak Yapısı) → §3.11'e taşınır
- Eski §3.11 (Dijital Araç Sınırı İlkesi) → §3.12'ye taşınır
- §3.9 VAK alt-başlığına bir cümle eklenir: "Bu test Giriş Kapısı değildir — Çift Üçlü ayrımı için bkz. §3.10."
- Sürüm Geçmişi'ne v1.4 satırı eklenir

**Method Book Project Instructions v2 FINAL → v2.1:**
- §3 Kabul 5 sonuna dipnot eklenir (Decision Log + Spine §3.10 atfı)
- Bölüm C/Modül I (VAK) ve Bölüm C/Modül II (Giriş Kapıları) bölümleri Çift Üçlü ayrımını açar
- Bölüm F Karaktere Hazırlık Soruları 3×3 Matris ile çerçevelenir

**Workbook 2. baskı errata:**
- s.20 üst paragrafa kenar notu (VAK ≠ Giriş Kapısı)
- s.31–45 sezgisel temas spread'ine kanal vs kapı ayrımı kenar notu
- (Bkz. workbook/karsilastirma-raporu.md Madde C.2)

**App:**
- VAK test sonucu ekranında bilgi kutusu: "Bu kanal nasıl öğrendiğini söyler. Karaktere nereden gireceğini Modül II soruları belirler."
- Faz 2'de Modül II içine 3×3 Matris seçim arayüzü eklenir

**Workshop Spine v1.1 → v1.2:**
- A2 (Tam Modül atölyesi) eğitmen el kitabına "VAK / Giriş Kapıları ayrımı + 3×3 Matris" başlığı
- E1 sertifikasyon sınavının test maddesi olur

### Notlar

- Bu karar 2025 ITC sunumundaki yapılaşmayı kanonlaştırır. Berlin Sunum 2023 ve daha eski materyallerde iki üçlü zaman zaman birbirinin yerine geçer; o materyaller "tarihsel kaynak" konumunda kalır, kanon olarak güncellenmez.
- Sezgisel kanalın VAK'ın yanına dördüncü olarak konması Karakter Tasarım 2021 kitabıyla uyumludur (üç duyu kanalının yanında "düşünce akışı / sezgi" katmanı işaretli).
- Numara kaydırması (eski §3.10 ve §3.11'in birer kademe kayması) dört katmanın da güncellenmesini gerektirir; bu Decision Log kaydı ile Çift Üçlü Errata Revizyonu (`03-errata-revizyonu.md`) birlikte uygulanır.
- Bu karar 8 Mayıs 2026 oturumunda alınan 8 stratejik kararın yanına 9. karar olarak işlenir. Spine v1.3 aynı gün içinde v1.4'e çıkar.

---

## 6 Mayıs 2026 — Modül II Hamlet Refactor Tamamlandı

**Tip:** Yapısal Karar (Tip 2) + Açık Karar Çözüldü (Tip 4)
**Etkilenen katmanlar:** App (birincil) + Workbook (köprü) + Method Book (referans)
**Spine sürümü:** v1.1 → v1.2
**Karar veren:** Beyti (uygulama) — Filiz onayı bekleniyor (klinik onay için Senin Çerçeven hibrit yapısı)
**Tasarım eş yazımı:** Claude (Anthropic)

### Karar

App'in `/antrenman/karakter/hamlet` sayfası, Hamlet Workbook s.46-125 yapısına birebir hizalandı. Yeni karakter sayfası mimarisi:

```
Hamlet Karakter Sayfası
├── Karakter Kimliği (mevcut, korundu)
├── Değiştirilemez Doğrular (mevcut, korundu)
├── Oyun Öncesi Yaşam (YENİ)
├── Timeline · 14 Sahne (yapı dolduruldu, etkileşimli sıcaklık)
├── Yazarın Çerçevesi · 5 Tercih (sahne tabanlı yapı tamamen değişti)
├── Senin Çerçeven · 5 Boşluk + 15 alt-soru (12 alandan hibrit yapıya)
└── Modül III · Yolculuk Modu CTA (eski 9 antrenman buraya yönlendi)
```

### Uygulama Detayları

**Ana Tasarım Kararları (yan kararlar):**
- **Senin Çerçeven yapısı:** Hibrit — 5 ana boşluk + her birinde 3 alt-soru (toplam 15 yansıma alanı). Workbook'a sadakat + App'in derinleşme imkânı dengelendi.
- **Eski 9 antrenman:** Tamamen retire edildi. Modül III Yolculuk Modu (110 dk) bu içeriği kapsıyor.
- **Yazarın Çerçevesi:** Mevcut sahne tabanlı yapı silindi. Workbook'taki 5 tercih yapısına geçildi: Hayalet, Delilik, Ophelia, Erteleme, Son.
- **Tercih 4 (Erteleme):** Çoklu seçim — birden fazla yorum birlikte seçilebiliyor (Goethe + Coleridge + Freud, vs.).
- **Timeline sıcaklık:** Etkileşimli — oyuncu Workbook önerisinin yanına kendi yorumunu işaretliyor.
- **Alt-soru seçimleri:** Her boşlukta Workbook'taki 5-6 sorudan en güçlü 3'ü seçildi (özgün katkı).

**Veri Modeli Değişiklikleri:**
- 4 yeni Supabase tablosu eklendi: `oyun_oncesi_olay_yansimalar`, `oyun_oncesi_iliski_yansimalar`, `sahne_yansimalar`, `yazarin_cercevesi_secimler`
- Mevcut `bosluk_yansimalar` schema güncellendi: `alt_soru_no` kolonu eklendi
- Yeni opsiyonel tablo: `bosluk_genel_metin`
- RLS politikaları aktif
- Eski `tamamlanan_egzersizler` ve `antrenman_yansimalar` korundu (geriye dönük uyumluluk)

### Çapraz Etki

**Workbook tarafına:**
- 2. baskı manuscript için **QR kod hazırlığı** başlamalı (her bölüm sonunda "App'te bu bölümün dijital pratiği")
- App'teki bağlantılar Workbook sayfa numaralarıyla eşleşiyor — referans tutarlılığı sağlandı

**Method Book tarafına:**
- Bölüm III (Karakteri Tanı) prototip yazımı sırasında bu refactor **canlı vaka** olarak kullanılabilir
- App'teki "Doğrular → Timeline → Yazarın Çerçevesi → Senin Çerçeven" akışı, Method Book Bölüm III'ün uygulamalı karşılığı

**Spine tarafına:**
- §2 App durumu güncellendi (Modül II artık "refactor planı" değil, "tamamlandı")
- §4.3 Workbook ↔ App köprüleri canlandı — artık potansiyel değil **gerçek** bağlantılar
- §5'ten "Modül II Hamlet refactor" açık kararı kaldırıldı

### Notlar

- Bu refactor, **Brief v2 §6 Çapraz Güncelleme Protokolü'nün ilk gerçek uygulaması**. Sistemin operasyonel olarak çalıştığının doğrulaması.
- Refactor önce Hamlet'te yapıldı (pilot). Aynı yapı sonra Macbeth, Willy Loman, Biff Loman'a uygulanacak (Faz 3 Milestone 3.2).
- Beyti'nin yalnız geliştirici olarak verdiği kararlar; Filiz onayı **uygulama sonrası** gözetim formunda alınacak (klinik gözetim).

---

# AKTIF AÇIK KARARLAR (Spine §5'ten)

Bu listede **henüz çözülmemiş** kararlar var. Çözüldükçe yukarıya kayıt eklenir.

## App

- AI sesli yönlendirmenin teknik altyapısı (TTS, ElevenLabs voice cloning?)
- **Eyüboğlu telifi App'te ticari kullanım için lisans yenilemesi gerekiyor mu?** ← Faz 1'de çözülmeli (kritik)
- Method Book ve Workbook ile çapraz pazarlama (in-app linkler, QR)
- Çok-rol katmanı: bireysel/eğitmen/koç/akademi rolleri
- Ticarileşme aşaması: ödeme/abonelik (Stripe + iyzico?), fiyatlandırma şeffaflığı
- Modül II refactor — diğer üç karakter: Macbeth, Willy, Biff için aynı refactor + Doğrular 3 kaynak yapısı dahil ne zaman? (Faz 3 Milestone 3.2)

## Workbook

- 2. baskıda Method Book'a geri-referans formatı
- Klinik güvenlik eklemeleri (öz-tarama uzunluğu, "iyi değilsen" dalı formatı)
- Bölüm IX çapa cümlesi ek koruma katmanı
- İngilizce baskı için RSC Shakespeare adaptasyonu
- s.20 "3 düzey" → "4 yoğunluk" güncellemesi (2. baskı)
- s.31-45 başına MBTI App QR kutusu (2. baskı)

## Method Book

- Alt başlık: "Inside The Character" tek başına mı?
- "Actor's Gym" markasının kitap ile ilişkisi
- Manifesto madde 7-8'in nihai isimleri
- Bölüm I yapısı: Altı Kabul + Manifesto sonda mı, ayrı bölüm mü?
- Çağdaş vaka anonimleştirme derinliği
- Bölüm E klasik vakası: Macbeth mi Hamlet mi (2025 sunum Macbeth pilotluyor)
- FKA imza protokolü: bölüm başı işareti / bölüm sonu küçük not / içindekilerde belirtim

## Workshop

- E1 sertifikasyon yapısı (D1'in ön koşul rolü resmi karar mı, tasarım önerisi mi?)
- `Itc_workshop.pdf` eski tasarım: retire / referans / v0 taslak konumu
- 4 hafta ve 12 hafta program şablonları (henüz yazılmamış — 8 haftadan türetilecek)

## Ekosistem Geneli

- Method Book Türkçe ilk baskı + İngilizce çeviri sıralaması
- Yayıncı kararı (Routledge / Methuen Drama / Nick Hern Books)
- App'in yurt dışına açılma stratejisi (Stuttgart, RADA bağlantıları)
- Ekosistemin tek bir markası mı (Inside The Character) yoksa dört ayrı isim mi?

## Operasyonel

- Domain ve marka: itcactorsgym.com mi, başka isim mi?
- Şirket yapısı: LTD Türkiye / Delaware C-Corp / hibrit?
- Filiz'in formal hisse durumu (eş kurucu, hisse %?)
- İlk 100 abone fiyatlandırması: $9 life-time vs $14 12-ay sınırlı?

---

# ÖNEMLİ TARİHLER

| Tarih | Olay |
|---|---|
| 6 Mayıs 2026 | Spine v1.0 yayımlandı |
| 6 Mayıs 2026 | Spine v1.1 (Modül III pilot kararı, Modül II refactor planı kararı) |
| 6 Mayıs 2026 | Brief v2.0 yayımlandı |
| 6 Mayıs 2026 | Modül II Hamlet refactor tamamlandı |
| 6 Mayıs 2026 | Spine v1.2 yayımlandı (refactor sonrası) |
| 6 Mayıs 2026 | Decision Log v1 başlatıldı |
| **8 Mayıs 2026** | **Method Book ana yapı oturumu — 8 stratejik karar (MBTI, travma yoğunluğu, doğrular üç kaynak, Modül III yapısı, Yıldız Oyuncu 6 boyut, Workshop dördüncü katman, Dijital Araç Sınırı, Karaktere Hazırlık 9 adım × 3 Kapı)** |
| **8 Mayıs 2026** | **Spine v1.3 yayımlandı (8 karar sonrası)** |

---

*Decision Log canlı belgedir. Her stratejik karar burada loglanır.*
*Çeyreklik (üç ayda bir) gözden geçirilir, açık kararlar güncellenir.*

**Sonraki kontrol:** Pazar 10 Mayıs 2026 — Spine Health Check (haftalık) — bu güncellemenin ilk gerçek check'i
**Sonraki kapsamlı revizyon:** Ağustos 2026 (çeyreklik strategic review)
