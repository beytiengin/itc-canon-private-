# Spine §3.10 Güncellemesi — Çift Üçlü İlkesi ve 3×3 Matris

**Hedef:** Spine v1.3 → v1.4
**Tarih:** 8 Mayıs 2026
**Karar referansı:** Decision Log `2026-05-08-cift-uclu/01-decision-log-eklentisi.md`

---

## Numara Kaydırması (kritik)

§3.10 yeniden işgal edildiği için mevcut alt-bölümler bir kademe kayar. Bunu Spine'a yedirmeden **önce** dört katmandaki §3.10 ve §3.11 atıflarının topyekûn güncellenmesi gerekir; ayrı errata için bkz. `03-errata-revizyonu.md`.

| Eski numara | Eski başlık | Yeni numara |
|---|---|---|
| §3.10 | Doğrular Üç Kaynak Yapısı | **§3.11** |
| §3.11 | Dijital Araç Sınırı İlkesi | **§3.12** |
| — | Çift Üçlü İlkesi ve 3×3 Matris (YENİ) | **§3.10** |

§3.9 (Modül I'in Üç Testi), §3.7 (Altı Kabul), §3.8 (Kuramsal Zemin) ve §3.1–3.6 numaraları **değişmez**.

---

## §3.10 · Çift Üçlü İlkesi ve 3×3 Matris (YENİ — v1.4)

ITC içinde iki ayrı kanonik üçlü bulunur. Bu iki üçlü zaman zaman birbirinin yerine geçecek biçimde kullanılmıştır; bu kullanım hatalıdır ve pedagojik hataya yol açar. İlke şudur: iki üçlü farklı sorulara cevap verir, farklı modüllerde operasyonel hale gelir, farklı uygulama biçimine sahiptir. Çarpımları (3×3) eğitmen ve oyuncu için somut bir başlama matrisi üretir.

### İki Üçlünün Karşılaştırması

| Boyut | VAK Üçlüsü | Giriş Kapıları Üçlüsü |
|---|---|---|
| Üçlü | Görsel · İşitsel · Kinestetik | Bilişsel · Bedensel · Duygusal |
| Sorduğu soru | Nasıl öğrenirsin? | Karaktere nereden girersin? |
| Ölçtüğü | Bilgi işleme kanalı (algı–içselleştirme) | Karaktere erişim kanalı (analiz–temas) |
| Kanonik yeri | Modül I — Kendini Tanı (Kalibrasyon) | Modül II — Karakter Dramaturjisi |
| Uygulama | App-only test (27 soru · ~5 dk) | Soru havuzu — kâğıt-kalem (Karaktere Hazırlık Soruları) |
| Dijital Araç Sınırı (§3.12) | App-only — algoritmik puanlama | Method Book Bölüm F — birey kâğıtla çalışır |
| Dördüncü kanal | **Sezgisel** (gözlemsel okuma; algoritmaya girmez) | Yok — üçlü kapalıdır |
| Pedagojik kullanım | Zihinsel antrenmanların "derinleşme" adımı baskın kanala göre | "Bir gece / bir hafta" sınırı altında en hızlı doğru soruyu bulma |

### Yaygın Hatanın Anatomisi

Karışımın klasik biçimi: *"VAK'a göre karaktere bedenden giriyor."*

- **Hata:** "VAK = Kinestetik" ile "Giriş Kapısı = Bedensel" aynı şey sanılmıştır. Aynı şey değildir.
- **Doğru okuma:** Görsel öğrenen bir oyuncu, karaktere bilişsel, bedensel veya duygusal kapıdan girebilir. Bunlar farklı katmanlardır ve birbirinden bağımsız işler.
- **Örnek:** Görsel-baskın bir oyuncu (VAK) → Macbeth'e bilişsel kapıdan girer (Giriş Kapısı) → derinleşme aşamasında karakteri "kafasında resmederek" çalışır (VAK'ın baskın kanalı bu noktada devreye girer). Kapı bilişsel olduğu için soruları analitik-yapısaldır; oyuncu görsel olduğu için derinleştirme sahnenin gözle kurulmasıdır.

### 3×3 Matris

İki üçlünün kesişimi 9 hücreli bir matris üretir. Her hücre, oyuncunun "açık kanalından açık kapıya" geçişinde önerilen başlangıç egzersizini taşır. Matris kullanımı: oyuncu VAK kalibrasyonundan (Modül I) baskın kanalını öğrenir; Karaktere Hazırlık Soruları (Modül II / Method Book Bölüm F) ile baskın kapısını bulur; matriste karşılık gelen hücreye bakar.

|                  | **Bilişsel Kapı**                          | **Bedensel Kapı**                              | **Duygusal Kapı**                                  |
|------------------|--------------------------------------------|------------------------------------------------|----------------------------------------------------|
| **Görsel**       | Sahne diyagramı · zihin haritası · timeline çizimi | Karakterin silueti · postür eskizi · ayna çalışması | Yüz/beden ifadesi okuma · karakter portresi etüdü |
| **İşitsel**      | Replik analizi · tonlama yapısı · monolog parçalama | Nefes-ses ritmi · vokal warm-up · prosodi çalışması | Ses kalitesi-duygu eşleştirme · iç ses dinleme   |
| **Kinestetik**   | Yapıyı bedenle deneyimleme · blocking provası | Hareket etüdü · somatik bedensel yoklama · yürüyüş | Karakterin bedensel duygusu · imgesel temas      |

**Önemli — etik kayıt:** "Kinestetik × Duygusal" hücresinde *karakterin* bedensel duygusu çalışılır, oyuncunun kendi anısı değil. Bu Substitution kullanılmaz ilkesinin (§3.1) matris üzerinde işaretidir.

### Sezgisel Dördüncü Kanal

VAK üçlüsünün yanında **Sezgisel** kanal dördüncü olarak konumlanır. Bu kanal Karakter Tasarım 2021 kitabında ("görebildiğiniz · işitebildiğiniz · tadabildiğiniz · dokunabildiğiniz · koklayabildiğiniz" duyu açıklamasının üzerinde "bir düşünce akışı" olarak işaretli) ve Hamlet Workbook s.31–45 sezgisel temas bölümünde yer alır.

Sezgisel kanal algoritmik puanlamaya girmez; VAK testi 27 soruluk Görsel–İşitsel–Kinestetik puanlamasıyla sınırlıdır. Sezgisel, eğitmenin atölyede ya da oyuncunun günlüğünde gözlemsel olarak farkına vardığı bir katmandır. Bu, ITC'nin VAK testini sınır olarak işaretler — testin yeterince ölçemediği bir kanal vardır ve metot bunu reddetmez.

Sezgisel kanal matriste dördüncü bir satır açmaz — kendi başına bir okuma kanalıdır; matrise sezgisel okumanın notları kenardan eklenir.

Giriş Kapıları üçlüsü **kapalıdır**. Bilişsel · Bedensel · Duygusal'a "Sezgisel" dördüncü olarak eklenmez. Giriş Kapıları operasyonel olarak üç kapıyla çalışır ve bu üçlü Method Book Bölüm F'deki 9 adımlık Karaktere Hazırlık Soruları haritasının omurgasıdır.

### Karaktere Hazırlık Soruları ile Bağ

Karaktere Hazırlık Soruları (Method Book Bölüm F · 2023 Berlin 9 adımlık akış) Üç Giriş Kapısı ile yapılandırılır. Her adımda kapılardan biri (ya da birden fazlası) baskındır; her kapı için ayrı soru seti bulunur.

- **Bilişsel kapı** — analitik / yapısal sorular (örn. "Karakterin değiştirilemez doğruları nelerdir?")
- **Bedensel kapı** — somatik / duyusal sorular (örn. "Karakter bir odaya girdiğinde bedeni nasıl hareket eder?")
- **Duygusal kapı** — ilişkisel / etkilenim soruları (örn. "Karakter babasını anlattığında bedeninde ne oluyor?")

Bu soru havuzu kâğıt-kalemle çalışıldığı için Method Book'ta yer alır — Dijital Araç Sınırı İlkesi §3.12 gereği. App'te bulunmaz; App'in karşılık gelen alanı "Senin Çerçeven" boşluk yansımalarıdır (Workbook s.106–125).

### Klinik Zemin (FKA)

Giriş Kapısı seçiminin Duygusal'a yanlışlıkla zorlanması (örneğin "duygusal kanalı zayıfsan oradan başla, güçlendir" mantığı) oyuncuyu kendi duygu havuzuna geri çekme riski yaratır. ITC bu mantığı reddeder: oyuncu hangi kapıyı seçtiyse seçsin, karakterin verisinde kalır — kendi yarasında değil.

3×3 Matris bu açıdan bir güvence katmanıdır: matris hücreleri "açık kanaldan açık kapıya" geçişi somut egzersizle gösterir; oyuncuyu kendi geçmişine değil, karakterin verisine yönlendirir. Eğitmen bir kapıdan giriş "denenip" sonuç alınmadığında diğer kapıya geçer — bu test-deneme akışı Modül II/Aşama 2'nin operasyonel ritmidir.

Bu açıdan Çift Üçlü ayrımı sadece pedagojik değil, aynı zamanda etik bir kanondur. Substitution kullanılmaz ilkesi (§3.1) ile doğrudan bağlıdır.

### Dört Katmana Etki

| Katman | Çift Üçlü İlkesi'nin Etkisi |
|---|---|
| Method Book | Modül I (VAK) ve Modül II (Giriş Kapıları) ayrı bölümler; her bölümün başında diğerine bir ayrım notu. Bölüm F Karaktere Hazırlık Soruları 3×3 Matris ile çerçevelenir. |
| Workbook (Hamlet) | Mevcut yapı zaten doğru — s.31–45 VAK bağlamı, s.50–125 Giriş Kapılarıyla operasyonel. 2. baskıda iki kenar notu yeterli (bkz. karşılaştırma raporu Madde C.2). |
| ITC App | VAK test sonucu ekranında bilgi kutusu. Faz 2'de Modül II içine 3×3 Matris seçim arayüzü. |
| Workshop | A2 eğitmen el kitabında "VAK / Giriş Kapıları ayrımı + 3×3 Matris" başlığı — E1 sertifikasyon test maddesi. |

---

## Sürüm Geçmişi Satırı (Spine §6 sonuna eklenir)

```
v1.4 — 8 Mayıs 2026 — §3.10 yeniden tanımlandı: Çift Üçlü İlkesi ve 3×3 Matris
(VAK × Giriş Kapıları). Eski §3.10 (Doğrular Üç Kaynak Yapısı) §3.11'e, eski §3.11
(Dijital Araç Sınırı İlkesi) §3.12'ye kaydı. §3.9 VAK alt-başlığına ayrım notu eklendi.
v1.3'ün geri kalan içeriği aynen korundu.
```

---

## §3.9 VAK Alt-Başlığına Eklenecek Satır

§3.9 · Modül I'in Üç Testi · VAK — Öğrenme Stili Analizi alt başlığının "Pedagojik kullanımı" satırının altına eklenir:

> **Önemli ayrım:** VAK ≠ Giriş Kapıları. VAK "nasıl öğrendiğini" söyler (algı kanalı). Karaktere "nereden girdiğini" (Bilişsel · Bedensel · Duygusal) Modül II'deki Giriş Kapıları belirler. İki üçlünün kesişimi 3×3 Matris'tir — bkz. §3.10.

---

*Spine'a yedirme sırası: önce numara kaydırması (eski §3.10 → §3.11, eski §3.11 → §3.12), sonra yeni §3.10 metni, sonra §3.9 alt notu, sonra §6 Sürüm Geçmişi satırı. Aynı commit'te yapılması önerilir.*
