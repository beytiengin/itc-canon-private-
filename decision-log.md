# ITC EKOSİSTEM — DECISION LOG

**Sahibi:** Beyti Engin
**Klinik & Akademik Eş Sahip:** Filiz Kaya Ataklı
**Operasyonel Eş Yazar:** Claude (Anthropic)
**Başlangıç:** 6 Mayıs 2026
**Son güncelleme:** 12 Mayıs 2026

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

## 12 Mayıs 2026 — Yolculuk Geometrisi: Sahne · Tanıklık · Çift Geri Bildirim (Karar 14)

**Tip:** Kanon Genişlemesi (Tip 1)
**Etkilenen katmanlar:** Workshop (birincil) + Method Book (Bölüm D referansı) + App (Modül III sahneleme yaklaşımı)
**Spine sürümü:** v1.5 → v1.6
**Karar veren:** Beyti
**Tasarım eş yazımı:** Claude (Anthropic)
**Etkili §:** §3.16 (yeni alt-bölüm)
**⚠ DURUM: Filiz klinik onayı bekleniyor — Spine'da provisional flag ile durur.**

### Karar

Yolculuk Modu'nun grup transmisyonu (atölye/eğitim ortamı) üç değişmez geometrik bileşenle çalışır:

**A. Sahnede yapılır.** Yolculuk her zaman fiziksel sahne alanında — atölye odasının ortasında, ışık altında, görünür konumda — gerçekleştirilir. Kapalı oda, kabin, izolasyon mekânı **YASAK**. Bu yasak etik bir kural değildir, geometrinin kendisidir: kapalı oda Yolculuk Modu'nun bileşenlerini fiziksel olarak imkânsız kılar.

**B. Grup tanıklığında.** Yolculuk yalnız değil — sessiz, dikkatli, müdahalesiz bir kohort önünde yapılır. Tanıklık geometrinin ikinci bileşenidir; oyuncuyu hem güvenceye alır (yalnız bırakılmıyor) hem de hesap verir kılar (kendi içine kaybolmuyor).

**C. Çift geri bildirim — sıra sabit.** Yolculuk tamamlandığında geri bildirim iki turda alınır ve sıra **ters çevrilemez**:
1. **Önce grup** — "ne gördük" (Yazarın Çerçevesi'nin canlı tezahürü; oyuncunun ne yapmaya çalıştığı değil, ne yaptığı)
2. **Sonra oyuncu** — "ne yaşadın" (Senin Çerçeven'in canlı tezahürü; içeriden ne hissedildiği)

Sıra ters çevrildiğinde oyuncu önce kendi deneyimini sözle kapatır, sonra grup gözlemi o kapanışa hizmet eden bir okuma haline gelir — bu Yazarın Çerçevesi / Senin Çerçeven ayrımını çökertir (Spine §3.5 ve §3.11 ile çelişir).

### Gerekçe

Yolculuk Modu Hamlet Workbook'ta tek başına çalışan oyuncu için yazıldı (s.126–289, 13 bölüm). Grup transmisyonuna geçtiğinde — atölyede 8–12 kişilik bir kohortla çalışırken — Workbook'un geometrisi yeterli değildir; eğitmenin sahne kuralı, tanıklık kuralı, geri bildirim sıra kuralı olması gerekir.

Bu kurallar Berlin Chubbuck Studio iki yıllık seri (2024–2025) ve HMDK Stuttgart 2025 akademik atölye deneyimlerinde damıtıldı. Hem doğal olarak ortaya çıktılar, hem de ihlal edildiklerinde **ne olduğu görüldü**: kapalı oda denendiğinde oyuncu dissosiyatif bölgeye geçti; geri bildirim sırası tersine çevrildiğinde grup gözlemi terapi seansına benzedi.

Karar şimdi kanonlanır ki Workshop dokümantasyonunda ve eğitmen sertifikasyonunda bu üçlü değişmez olarak işlensin.

### Yazarın Çerçevesi vs Senin Çerçeven ile Bağ

Çift geri bildirim Yolculuk'un sahne üzerinde **Yazarın Çerçevesi / Senin Çerçeven ayrımının yeniden kurulması** olarak işler:

- **Grup turu = Yazarın Çerçevesi** — dışarıdan görülen, nesnel, yorumdan önceki — "Hamlet ayağa kalkarken nefesini tuttu, üç adım attı, sonra döndü"
- **Oyuncu turu = Senin Çerçeven** — içeriden yaşanan, öznel, yorumla yüklü — "Ayağa kalkarken babamı düşündüm, üç adım Wittenberg'di"

İki çerçeve farklı veridir — birbirinin yerine geçmez. Spine §3.11 (Doğrular Çift Üçlü) bu ayrımı Method Book'ta kuramsal olarak işliyordu; Karar 14 onu **sahne geometrisinde** operasyonelleştirir.

### Klinik Zemin (FKA — onay bekleniyor)

Filiz onayı bekleyen kritik nokta: çift geri bildirim sırasında oyuncu, grup turundan sonra "kendi deneyimini" anlatırken **dissosiyatif anı geçişi** riski taşır. Yolculuk yoğunsa, oyuncu "ben Hamlet'ken bunu yaptım" derken karakterle kendisi arasındaki sınırı kaybedebilir.

Bu risk için klinik koruma protokolü Filiz tarafından şekillendirilecek. Olası unsurlar:
- Oyuncu turundan önce zorunlu topraklanma adımı (en az 2–3 nefes, isim teyidi)
- Eğitmenin "şimdi sen anlat — Hamlet değil, oyuncu" formülasyonu (üçüncü kişi geçişi)
- FKA klinik on-call eşiklerinin bu noktada devreye girmesi (3+ dk dissosiyatif belirti, anı geçişi)

Filiz onayı gelene kadar §3.16 metni Spine'a girer ama "provisional" flag taşır.

### Uygulama

- **Spine v1.5 → v1.6:**
  - §3.16 yeni alt-bölüm olarak eklenir: "Yolculuk Geometrisi: Sahne · Tanıklık · Çift Geri Bildirim"
  - §3.16 başlığına `[Filiz klinik onayı bekleniyor]` flag'i eklenir
  - §3.11 (Doğrular Çift Üçlü) sonuna §3.16 atfı: "Bu çerçeve ayrımı sahne geometrisinde §3.16 ile canlanır."
  - §3.5 (Karakter Sayfası Mimarisi) sonuna §3.16 atfı: "Mimarinin sahne geometrisi karşılığı için §3.16."
  - Sürüm Geçmişi'ne v1.6 satırı

- **Workshop (geliştirme aşamasında):**
  - C3 (Akış & Performans Atölyesi) §3.16 üzerine kurulur
  - A2 (Tam Modül Atölyesi) Modül III bloğu §3.16 geometrisiyle yürür
  - Eğitmen el kitabı §3.16'yı sahne yönetimi olarak işler
  - E1 sertifikasyonu §3.16'yı operasyonel olarak yapabilmeyi şart koşar (sınama maddesi)

- **Method Book Bölüm D (Etik Altyapı ve Eğitmen Rehberliği):**
  - "Yolculuk grup transmisyonu" alt-bölümü §3.16'yı akademik dille açar
  - Filiz imzalı klinik koruma protokolü buraya yazılır (onay sonrası)

- **App Modül III:**
  - Yolculuk Modu **bireysel** kullanımda kalır (oyuncu tek başına, kulaklıkla, kendi alanında)
  - App'in grup transmisyonu yoktur — Karar 14 doğrudan App'i etkilemez, ama Method Book Bölüm D'de "App'in tek başına kullanımı vs Workshop grup transmisyonu" ayrımı netleşir

### Notlar

- "Yasak" ifadesi sert kullanılır çünkü ihlali pedagojik hata değil, **klinik tehlike** üretir. Kapalı oda Yolculuk'u panik atağa ya da dissosiyatif epizoda dönüştürme potansiyeli taşır — bu Berlin Chubbuck Studio ikinci yılında bir kez yaşandı, eğitmen müdahalesi gerekti.
- Üç bileşen birbirinden ayrılmaz — biri eksikse Yolculuk Modu olmaz, başka bir şey olur. Bu yüzden "geometri" denir, "öneri" değil.
- Karar 14 Method Book Bölüm D yazımının (Faz 2, Ay 7–14) erken kanonik girdilerinden biri olacak.

---

## 12 Mayıs 2026 — Karakter Haritası Taksonomisi: Yolculuk × Çapa × Tip (Karar 13)

**Tip:** Kanon Genişlemesi (Tip 1)
**Etkilenen katmanlar:** Workshop (birincil) + Workbook (zaten içerir — kanon teyit) + Method Book (Bölüm E vaka çalışmaları) + App (Modül III navigasyon)
**Spine sürümü:** v1.5 → v1.6
**Karar veren:** Beyti
**Tasarım eş yazımı:** Claude (Anthropic)
**Etkili §:** §3.15 (yeni alt-bölüm)

### Karar

Her ITC karakterinin yolculuk yapısı üç ayrı eksende işaretlenir. Bu üçlü işaretleme **bir taksonomi** olarak kanondur; her karakter dosyası bu üçlüyle haritalanır.

**A. Yolculuk Bölüm Yapısı — kaç bölüm**
Karakterin yolculuğu kaç kanonik bölüme ayrılır. Hamlet için **13 bölüm** (Workbook s.126–289'da kanon). Macbeth için sayısal kanon ayrı tartışılır (Macbeth Timeline PDF'inde 12 bölüm önerisi var, kanon onayı bekliyor). Diğer karakterler eklendikçe sayıları kararlaştırılır.

**B. Çapa Noktaları — hassas yoğunluk anları**
Yolculuk içinde belirli sayıda çapa noktası vardır. Çapa, oyuncunun karakterin yoğunluğuyla **bedensel olarak tutulduğu** ankordur — Bedensel Yoklama (Spine §3.4 Topraklanma Protokolü'nün karşı kutbu). Hamlet için **5 çapa** kanon:
- **Çapa No 1** — Babanın hayaleti (Bölüm IV)
- **Çapa No 2** — Aktörlerin gelişi
- **Çapa No 3** — "Olmak ya da olmamak" (Bölüm IX) — **EN HASSAS** (FKA klinik koruma katmanı zorunlu, bkz. Workbook errata D.5)
- **Çapa No 4** — Ophelia'nın mezarı
- **Çapa No 5** — Düello (Bölüm XIII)

Çapa numarası bölüm numarasıyla aynı değildir; çapa "bölüm içindeki tekil hassas an"dır, bölüm "yolculuk dilimi"dir.

**C. Bölüm Tipleri — pedagojik fonksiyon**
Her bölüm dört tipten birine girer. Tip, bölümün **yolculuk içindeki işlevini** sınıflar:
- **Tip A — Çapa bölümü:** Bir çapa noktası içerir; yoğunluk doruğu burada
- **Tip B — Geçiş bölümü:** İki çapa arası dramaturjik geçiş; bedensel yoğunluk düşük, anlatı katmanı yüksek
- **Tip C — Derin yüzleşme bölümü:** Çapa yok ama birikimli yoğunluk var; özel statü taşır (alt-açıklama aşağıda)
- **Tip D — Kapanış bölümü:** Yolculuğun çözüldüğü, çıkış geometrisinin hazırlandığı bölüm

### Tip C — Özel Statü

Tip C bölümleri ITC pedagojisinde özel önemdedir. Çapa noktası içermez (yani belirgin bir doruk yok), ama oyuncunun bir önceki birkaç bölümün birikiminden dolayı **bedensel olarak yüklü** bir hâlde girdiği bölümdür. Tip A daha öngörülebilir bir yoğunluk taşır (çapa hazırlanır, alınır, bırakılır); Tip C ise sinsi yoğunluktur — eğitmen Tip C'lerde **birikimli yorgunluk** ve **gizli dissosiyatif belirtiler** için ek dikkat tutar.

Hamlet'te Tip C bölümler özellikle Bölüm VII–VIII civarındadır (Polonius öldürme ve sonrası). Workbook bunu zaten Tip C/Tip B/Tip A tiplemesiyle işaretliyor (`s.310` ve TOC bölümünde — 2. baskıda TOC eşleştirildiğinde Tip işaretleri görünür hâle gelir).

### Travma Matrisi (8×4) ile Ayrım — kritik

Karakter haritası taksonomisi (yolculuk × çapa × tip) **§3.3 Yıldız Profil Eşleşme Matrisi'nin temel aldığı Travma Matrisi (8×4) ile karışmamalıdır**:

| Boyut | Karakter Haritası (§3.15) | Travma Matrisi (§3.3) |
|---|---|---|
| Birim | Yolculuk bölümü | Sahnedeki travmatik içerik |
| Ölçtüğü | Yolculuk içindeki yapısal konum | İçeriğin etik yoğunluğu |
| Sınıflama | A/B/C/D bölüm tipi + çapa numarası | 8 kategori × 4 yoğunluk (0/1/2/3) |
| Kim kullanır | Eğitmen — sahne ritmi için | Oyuncu × Eğitmen — etik filtre için |
| Pedagojik soru | "Şu an yolculuğun neresindeyiz?" | "Bu içerik oyuncu için güvenli mi?" |

İki sınıflama **birbirine bağımlı çalışır ama farklı sorular sorar**. Tip A bir bölüm (çapa noktası) aynı anda Travma Matrisi'nde "Kayıp × Tanıklık" (2 yoğunluk) olabilir; bunlar iki ayrı işarettir, biri konum diğeri içerik. Eğitmen sertifikasyonu (E1) için bir kriterdir: aday her iki sınıflamayı bir karakter üzerinde ayrı ayrı doldurabilmeli.

### Kanonik Atıf Formatı

Bir karakter haritası noktasına atıf yaparken üçlü format kullanılır:

```
Hamlet · Bölüm IX · Tip A · Çapa No 3
```

Bu format Workshop dokümantasyonunda, Method Book Bölüm E vakalarında, App Modül III navigasyon etiketlerinde, Workbook 2. baskı TOC eşleştirmesinde tutarlı kullanılır.

### Gerekçe

Workbook v1.0 zaten bu yapıyı içeriyor — 13 bölüm, 5 çapa, A/B/C/D tipler. Ancak Spine'da kanon olarak yazılmamıştı. Bu durumda Method Book yazımı sırasında her vaka çalışması için tiplemenin **yeniden icat edilme** riski vardı. Karar 13 mevcut yapıyı kanonlaştırır ve diğer karakterlere (Macbeth, Willy, Biff) genişleme yolunu açar.

Ayrıca atölye dokümantasyonunda — özellikle HMDK Stuttgart Participants Handbook ve Berlin Sunum 2023'te — bu üçlü taksonomi gevşek formlarda kullanılıyordu. Karar 13 ortak terminolojiyi sabitler.

### Uygulama

- **Spine v1.5 → v1.6:**
  - §3.15 yeni alt-bölüm olarak eklenir: "Karakter Haritası Taksonomisi: Yolculuk × Çapa × Tip"
  - §3.3 (Yıldız Profil Eşleşme Matrisi) sonuna §3.15 ayrım notu: "Bu matris karakter haritasından (§3.15) farklı bir eksendir — karışmamalıdır."
  - §3.15 başlığında benzer karşı atıf: "Bu taksonomi §3.3 Travma Matrisi'nden farklı bir eksendir."
  - Sürüm Geçmişi'ne v1.6 satırı

- **Workbook 2. baskı:**
  - TOC tutarsızlığı düzeltilirken Tip A/B/C/D ve Çapa No 1–5 işaretleri TOC'da görünür hâle getirilir
  - s.310 "11 yolculuk → 13 yolculuk" düzeltmesi yapılırken Tip dağılımı da görünür kılınır
  - Errata listesine yeni madde: TOC'da bölüm tipi ve çapa numarası işaretleri (Öncelik P4 — Çapraz referans)

- **Method Book Bölüm E (Uygulama Vakaları):**
  - Hamlet ve Macbeth vakaları §3.15 üçlü taksonomisiyle haritalanarak yazılır
  - Bölüm E'nin her vakası bir tablo açılışıyla başlar: "Yolculuk · Çapa · Tip dağılımı"

- **App Modül III (Yolculuk Modu):**
  - Bölüm navigasyon arayüzünde her bölüm yanında Tip A/B/C/D etiketi
  - Çapa içeren bölümlerde (Tip A) Çapa No görünür (örn. "Bölüm IX — Tip A — Çapa No 3")
  - Tip C bölümlerinde eğitmen versiyonu için "birikimli yoğunluk — dikkat" işareti (eğitmen panellerinde, oyuncuya görünmez)

- **Workshop:**
  - C2 (Karakter Sayfası Mimarisi) atölyesinde §3.15 taksonomisi öğretilir
  - A2 (Tam Modül atölyesi) Modül III bloğunda kullanılır
  - E1 sertifikasyon kriteri: aday yeni bir karakter için bu üçlü haritayı doldurabilmeli + §3.3 Travma Matrisi ile karıştırmamalı

### Notlar

- Macbeth'in çapa sayısı ve kanonik bölüm sayısı henüz açık — Macbeth Timeline PDF temel alınarak ayrı bir kararla netleşir.
- Workbook v1.0 zaten Tip C için ek dikkat işareti taşıyor (Yoklama'larla yakın yerleştirme); §3.15 bunu kanonlaştırır.
- Bu karar Workshop projesinde olgunlaşmış bir kavramın geri beslenmesidir — Karar 6'nın (Workshop dördüncü katman) operasyonel meyvesi.

---

## 12 Mayıs 2026 — Tek Karakter İlkesi: Grup Transmisyonunda Kohort Mimarisi (Karar 12)

**Tip:** Kanon Genişlemesi (Tip 1)
**Etkilenen katmanlar:** Workshop (birincil) + Method Book (Bölüm D pedagojik dayanak)
**Spine sürümü:** v1.5 → v1.6
**Karar veren:** Beyti
**Tasarım eş yazımı:** Claude (Anthropic)
**Etkili §:** §3.14 (yeni alt-bölüm)

### Karar

ITC grup transmisyonunda (atölye, akademik eğitim, kurumsal pilot) **kohort tek bir karakter etrafında toplanır**. 8–14 kişilik bir kohortta her katılımcı farklı karakter çalıştığında ITC operasyonel olarak çalışmaz.

İlke üç düzeyde gerekçelidir:

**A. Pedagojik düzey — Kabul 1'in operasyonel görünürlüğü**
Spine §3.7 Kabul 1: *"Karakter analiz edilmelidir."* Tek karakter ilkesi bu kabulün kohort ölçeğindeki karşılığıdır: grup aynı karakteri farklı kapılardan analiz ederek Kabul 1'in çoklu giriş kapılarını (Kabul 5) **canlı olarak görür**. Eğer her katılımcı farklı karakter çalışıyorsa, analiz örnekleri karşılaştırılamaz hâle gelir; kohort birbirinin çalışmasından öğrenemez.

**B. Operasyonel düzey — eğitmen bilişsel yükü**
Eğitmen (BE, FKA, veya sertifikalı eğitmen) bir atölye günü boyunca bir karakterin haritasını taşır. 12 farklı karakter taşımak yapısal olarak mümkün değildir — eğitmen ya yüzeyselleşir ya da bazı katılımcıları ihmal eder. Tek karakter ilkesi eğitmenin bilişsel yükünü tek bir derin yapıya odaklar ve böylece her katılımcıya tam dikkat verir.

**C. Etik düzey — klinik konteyner**
Filiz klinik gözetim mantığı kohortun aynı yoğunluk topografyasında olmasını gerektirir. Hamlet kohortunda Çapa No 3 (Bölüm IX, "olmak ya da olmamak") herkesin karşılaşacağı en hassas an olarak önceden bilinir; klinik on-call protokolü (bkz. Karar 11 / §3.13) bu nokta etrafında planlanır. 12 farklı karakter = 12 farklı çapa topografyası = klinik gözetim imkânsız.

### Format Uygulaması

Tek karakter ilkesi tüm atölye formatları için zorunludur, **B1 istisnası dışında**:

| Format | Tek Karakter | Hangi karakter? |
|---|---|---|
| A1 (Tanıtım, 3–4 saat) | ✅ Zorunlu | Hamlet (varsayılan demo karakteri) |
| A2 (Tam Modül atölyesi) | ✅ Zorunlu | Atölye programıyla belirlenir |
| **B1 (Kendi Karakterin)** | **❌ İstisna** | Her katılımcı kendi rolü — bkz. aşağıda |
| C1 (Metin Çözümleme) | ✅ Zorunlu | Atölye konusuyla belirlenir |
| C2 (Karakter Sayfası Mimarisi) | ✅ Zorunlu | Hamlet veya Macbeth |
| C3 (Akış & Performans) | ✅ Zorunlu | Atölye programıyla belirlenir |
| D1 (Etik & Klinik Güvenlik) | ✅ Zorunlu | Hamlet (Çapa No 3 etiği örneği) |
| D2 (Kuramsal Çerçeve) | ✅ Zorunlu | Hamlet (Çift Üçlü uygulaması) |
| E1 (Train-the-Trainer) | ✅ Zorunlu | Adaylara verilen karakter |

### B1 İstisnası — "Kendi Karakterin"

B1 (Kendi Karakterin) atölyesi katılımcıların **kendi prova ettikleri ya da yakında prova edecekleri** karakterlerle çalıştıkları formattır. Burada tek karakter ilkesi uygulanmaz çünkü atölyenin amacı her katılımcının kendi yaratım sürecine ITC çerçevesini taşımasıdır.

B1 istisnasının operasyonel maliyeti yüksektir — eğitmenin her katılımcının karakterini tek tek tanıması gerekir. Bu yüzden B1 için **ön koşul**: katılımcı A2 mezunu olmalı (yani Hamlet veya Macbeth üzerinde tam ITC döngüsünü tamamlamış olmalı). A2 mezunu olmayan katılımcılar B1'e alınmaz — çünkü ITC çerçevesini önce ortak bir karakter üzerinde edinmeden kendi karakterine taşıyamazlar.

Bu ön koşul Workshop A2 → B1 sıralamasını kanonlaştırır: A2 her zaman önce, B1 ileri seviye.

### Gerekçe

Berlin Chubbuck Studio iki yıllık seride (2024–2025) ilk altı ay "her katılımcı kendi karakteri" denendi, sonuç: kohort öğrenme parçalı, eğitmen yorgunluğu yüksek, klinik gözetim kaybediliyor. İkinci altı ayda Hamlet ortak karakter olarak getirildi — birden öğrenme katlandı, kohort sinerjisi açıldı. HMDK Stuttgart 2025 atölyesinde aynı yaklaşım baştan benimsendi, başarılı oldu.

Karar 12 bu deneyimin kanonlaştırılmasıdır.

### Karar 6 (Workshop Dördüncü Katman) ile İlişki

Karar 6 Workshop'u ekosisteme ekledi ama atölye formatlarının iç mimarisini açmadı. Karar 12 bu mimarinin **birinci temel taşıdır**: kohort yapısı.

### Uygulama

- **Spine v1.5 → v1.6:**
  - §3.14 yeni alt-bölüm olarak eklenir: "Tek Karakter İlkesi (Grup Transmisyonunda)"
  - §3.14 başlığında §3.7 Kabul 1'e atıf: "Bu ilke Kabul 1'in kohort ölçeğindeki operasyonel karşılığıdır."
  - Sürüm Geçmişi'ne v1.6 satırı

- **Workshop:**
  - Tüm atölye kartlarına (A1, A2, C1, C2, C3, D1, D2, E1) "Karakter: [karakter adı]" satırı zorunlu hâle getirilir
  - B1 atölye kartına "Ön koşul: A2 mezunu" satırı yazılır
  - Workshop Project Instructions §6'daki "Ön koşul" sorusu B1 için netleşir

- **Method Book Bölüm D (Etik Altyapı ve Eğitmen Rehberliği):**
  - "Kohort mimarisi" alt-bölümü §3.14'ü akademik dille açar
  - Berlin Chubbuck Studio ve HMDK Stuttgart deneyimleri vaka olarak işlenir

- **App:**
  - App bireysel kullanım olduğu için Karar 12 doğrudan etkilemez
  - Ancak App'in gelecek "eğitmen arayüzü" (Brief Faz 2 Milestone 2.6) kohort oluşturma akışında "kohort karakteri seçimi" zorunlu alan haline gelir (B1-tipi kullanım için "kendi karakterleri" opsiyonu sunulur)

### Notlar

- "Karakter" derken kanonik ITC karakterleri (Hamlet, Macbeth, Willy Loman, Biff Loman) ya da gelecek karakterler kastedilir. Eğitmenin kendi yazdığı bir vaka karakteri olamaz — kohort karakterinin Workbook benzeri kanonik veriye (Doğrular, Timeline, Çerçeveler) sahip olması şart.
- Macbeth ITC kanonuna giriyor ama henüz Workbook'u yok; Macbeth atölyesi açılmadan önce Workbook benzeri bir kanon dokümanı yazılması gerekir (Macbeth Timeline PDF temel alınabilir).
- Bu karar tek başına olduğunda anlamlı değil — Karar 11 (transmisyon mimarisi) ve Karar 13 (karakter haritası taksonomisi) ile birlikte Workshop atölye mimarisinin üç temel taşını oluşturur.

---

## 12 Mayıs 2026 — Transmisyon Mimarisi: BE × FKA Eş Eğitmenlik (Karar 11)

**Tip:** Kanon Genişlemesi (Tip 1)
**Etkilenen katmanlar:** Workshop (birincil) + Method Book (Bölüm D Etik & Eğitmen) + ekosistem geneli (FKA'nın resmi rolü)
**Spine sürümü:** v1.5 → v1.6
**Karar veren:** Beyti × Filiz
**Tasarım eş yazımı:** Claude (Anthropic)
**Etkili §:** §3.13 (yeni alt-bölüm)

### Karar

ITC transmisyonu (atölye, akademik eğitim, kurumsal pilot) Beyti Engin (pedagojik lider) × Filiz Kaya Ataklı (klinik gözetim) eş eğitmenlik modeliyle çalışır. Bu eş eğitmenlik beş katmanlı dağılım taşır:

**1. Teorik bloklar — paylaşımlı**
Felsefe, Kabuller, Manifesto, kuramsal zemin (Damasio · Goleman · Gardner · Levine · Csikszentmihalyi), Çift Üçlü matrisleri (§3.10 ve §3.11) eş eğitmen olarak birlikte sunulur. İki ses — pedagojik ve klinik — bir araya gelir; katılımcı yöntemin **çift sesli yapısını** baştan duyar.

**2. Modül I (Kalibrasyon) — birlikte**
VAK, MBTI, Yıldız Oyuncu testlerinin yorumlanması her zaman eş eğitmenli yapılır. Yıldız Oyuncu'nun psikolojik puanı (§3.3 Yıldız Profil Eşleşme Matrisi'nin eşik mekanizmasını besler) Filiz tarafından klinik perspektifle yorumlanır; bu yorumlama her zaman BE'nin pedagojik çerçevesiyle birlikte sunulur.

**3. Modül II (Karakter Dramaturjisi) — BE önder, FKA eşlikçi**
Karaktere Hazırlık Soruları (Method Book Bölüm F · 9 adım × 3 Giriş Kapısı), Doğrular Çift Üçlü matrisi (§3.11), Timeline ve Çerçeveler çalışması BE'nin pedagojik liderliğindedir. FKA arka planda gözlemci — etik kayma, kişisel travmaya kayma, dissosiyatif belirti gözetler. FKA müdahale eder ama merkeze çıkmaz.

**4. Modül III (Yolculuk + Sahneleme) — BE solo, FKA klinik on-call**
Yolculuk Modu ve sahne çalışması BE solo yürütür. Bu modül oyuncunun bedensel-duygusal yoğunlukla temas ettiği yer; pedagojik yönlendirme tek sesli olmalı. FKA bu modülde **klinik on-call** konumundadır — atölye odasında bulunur ama yönlendirme yapmaz; aşağıdaki tetikleyiciler aktive olduğunda devreye girer:

- **3+ dakika dissosiyatif belirti** (göz teması kaybı, "burada değilim" ifadesi, bedensel donma)
- **Anı geçişi** (oyuncu karakterin sahnesi yerine kendi geçmişindeki bir olaya geçer — örn. "Babamla bu konuyu konuşmuştuk")
- **BE sezgisi durdurma** (BE eğitmenliği bir anda anlamlandıramadığında FKA'ya işaret verir; FKA değerlendirme yapar)

Tetikleyici aktive olduğunda BE atölyeyi geçici olarak duraklatır; FKA topraklanma protokolünü (§3.4) ya da klinik bir geçişi yönetir. Sonrasında BE ya atölyeye devam eder ya da o oturumu kapatır — karar FKA'nın klinik değerlendirmesine göre alınır.

**5. Etik bloklar — FKA imzalı**
Travma Matrisi (§3.3, 8×4), Substitution kullanılmaz ilkesi (§3.1), Topraklanma Protokolü (§3.4), Yıldız Profil Eşleşme Matrisi (§3.3), Yolculuk Geometrisi'nin klinik koruma katmanı (§3.16, onay sonrası) bloklarının **klinik içeriği** FKA tarafından sunulur. BE pedagojik bağlamı kurar ama klinik içeriğin sözcüsü FKA'dır. Atölye katılımcılarına ve dokümantasyona "Bu bölüm Filiz Kaya Ataklı tarafından imzalanmıştır" işareti taşır.

### Eş Eğitmenliğin Operasyonel Maliyeti

Beş katmanlı dağılım hem güçtür hem maliyettir. Operasyonel sonuçlar:

**Maliyetler:**
- İki eğitmen tüm atölyede bulunmalı — fiyatlandırma iki eğitmen ücretini taşır
- Filiz'in klinik takvimi atölye takvimiyle çatışabilir — atölye planlanırken Filiz'in onayı önkoşul
- Eş eğitmen kohortu (E1 sertifikasyonu) zorlu — pedagojik eğitmen × klinik gözetimci çifti yetiştirmek tek eğitmenden daha pahalı

**Sonuçlar:**
- Atölye fiyatlandırması Solo Eğitmen × Eş Eğitmen olarak iki katmanlı olabilir
- Kurumsal pilotlar (HMDK Stuttgart, Royal Central vb.) için eş eğitmenlik standarttır — kurum bunun klinik güvencesini bekler
- Bireysel oyuncu pilotları (küçük atölyeler) için solo eğitmen seçeneği açılabilir — ama solo eğitmen Modül III'ü tek başına yapmamalıdır; ya FKA on-call (uzaktan video) ya da Modül III bloğu programdan çıkar

### Karar 6 ile İlişki

Karar 6 (8 Mayıs) Workshop'u dördüncü katman olarak ekosisteme ekledi ve Filiz'in klinik gözetim rolünü genel hatlarıyla işaretledi. Karar 11 bu rolü **operasyonel düzeyde** açar: hangi modülde nerede durur, hangi tetikleyiciler aktive olunca müdahale eder, hangi bloklar imzasını taşır.

Filiz Engin'in (Klinik & Akademik Eş Sahip) ekosistemdeki konumu — Karar 11 ile birlikte — net hâle gelir:
- **Method Book:** Çift sesli (BE + FKA), Bölüm D imzalı (Etik & Eğitmen Rehberliği)
- **Workbook:** Klinik güvenlik eklemeleri imzalı (2. baskı)
- **App:** Klinik güvenlik motoru (Yıldız Profil eşleşme, Topraklanma overlay) onay imzalı
- **Workshop:** Beş katmanlı eş eğitmenlik dağılımı (bu karar)

### Uygulama

- **Spine v1.5 → v1.6:**
  - §3.13 yeni alt-bölüm olarak eklenir: "Transmisyon Mimarisi: BE × FKA Eş Eğitmenlik"
  - §3.1 (Substitution kullanılmaz) sonuna §3.13 atfı: "Bu ilkenin grup transmisyonundaki canlı koruyucusu §3.13."
  - §3.4 (Topraklanma Protokolü) sonuna §3.13 atfı: "Atölye ortamında bu protokol §3.13'ün klinik on-call pozisyonundan uygulanır."
  - Sürüm Geçmişi'ne v1.6 satırı

- **Workshop:**
  - Eğitmen el kitabı §3.13 üzerine kurulur
  - Atölye kartlarına eğitmen dağılımı netleşir: "Eğitmenlik: BE + FKA / BE solo + FKA on-call / vb."
  - D1 (Etik & Klinik Güvenlik) atölyesi FKA imzalı olarak yazılır
  - E1 sertifikasyonu: pedagojik eğitmen × klinik gözetim çifti olarak sertifikalanır (tek eğitmen sertifikası yoktur)

- **Method Book Bölüm D (Etik Altyapı ve Eğitmen Rehberliği):**
  - "Eş eğitmenlik mimarisi" alt-bölümü §3.13'ü akademik dille açar
  - Klinik on-call tetikleyicileri Filiz tarafından detaylandırılır

- **Brief v2 (v2.0 → v2.1):**
  - §9.5 Operasyonel Kararlar listesinden "Filiz'in formal hisse durumu" kararı çözüme yaklaşır — Karar 11 Filiz'in operasyonel rolünü net hâle getirir; hisse düzenlemesi bu netliğin üzerine inşa edilir
  - §6.6 Claude'un Rolü bölümüne paralel olarak Filiz'in transmisyon rolünün netleştirilmesi notu

### Notlar

- Karar 11 Filiz tarafından onaylanmış sayılır çünkü Beyti × Filiz birlikte bu modelin Berlin Chubbuck Studio ve HMDK Stuttgart deneyimlerinde olgunlaştığını gözlemledi. Ancak metnin yazılı hâli olarak Filiz onay turunda kontrol edecek — klinik on-call tetikleyicileri özellikle.
- Solo eğitmen senaryosu (bireysel pilotlar için) açık karar olarak Spine §5'e işlenir — Karar 11'i ihlal etmeden ama daha küçük ölçekte uygulayabilen bir model gerekli.
- Bu karar Workshop atölye mimarisinin üç temel taşının ilkidir (Karar 11 + 12 + 13). Karar 14 (yolculuk geometrisi) dördüncü taş — sahnenin kendisinin geometrisi.

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
| **12 Mayıs 2026** | **Workshop geri besleme paketi (Karar 11–14) — Spine v1.6 yayımlandı** |
| **12 Mayıs 2026** | **Brief v2.1 yayımlandı — HMDK Stuttgart pilotu Faz 3 → Faz 2 (25–29 Ocak 2027)** |

---

*Decision Log canlı belgedir. Her stratejik karar burada loglanır.*
*Çeyreklik (üç ayda bir) gözden geçirilir, açık kararlar güncellenir.*

**Sonraki kontrol:** Pazar 10 Mayıs 2026 — Spine Health Check (haftalık) — bu güncellemenin ilk gerçek check'i
**Sonraki kapsamlı revizyon:** Ağustos 2026 (çeyreklik strategic review)
