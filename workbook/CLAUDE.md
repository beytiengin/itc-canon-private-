# Hamlet Workbook — Claude Hafızası

Bu dosya Claude Code için referans niteliğindedir. Hamlet Workbook'un (Inside The Hamlet) ITC ekosistemindeki konumu, içeriği, açık işleri, ve önemli uyarıları tek yerde toplar.

**Sürüm:** v1.1 (kanon-uyumlu yedirme)
**Tarih:** 15 Mayıs 2026 (Karar 21 sonrası)
**Önceki ortam:** Claude.ai Workbook Project (briefing v1.0 → bu dokümana yedirildi)
**Spine sürümü:** v1.9 (Karar 17-21 yedirildi)
**Brief sürümü:** v2.3

---

## 1 · Hızlı Durum Özeti

**Inside The Hamlet** (Hamlet Workbook) — ITC ekosisteminin dört katmanından biri. Sürüm 1.0 print-ready, 314 sayfa, 170×240mm. Yöntemin **tek karaktere derinleşmiş hâli** (Spine §1 dört katmanlı yapıda Workbook'un işlevi).

- **Türkçe baskı:** Tamamlandı (PDF basıma hazır)
- **İngilizce çevirisi:** Threshold pilotu (11/30 sayfa) yapıldı; Translation Manual v0.4 hazır
- **Açık işler:** 2. baskı klinik güvenlik eklemeleri, errata, App entegrasyonu, mobil/dijital uzantı

**Kanon konumu:** Spine §1 dört katmanlı ekosistem (Method Book / Workbook / App / Workshop) — Workbook = Hamlet karaktere derinleşmiş hâli, tek başına çalışan oyuncu için.

---

## 2 · Repo İçinde Konumu

```
itc-canon/
├── spine.md                 ← ITC Ekosistem Spine v1.9 (kanon omurgası)
├── decision-log.md          ← Tüm kararlar (Karar 1-21)
├── brief-v2.md              ← Ekosistem Brief v2.3
├── .claude/rules/           ← Kanonik kurallar (terminoloji, etik çerçeve, decision-log format)
├── kararlar/                ← Karar paketleri arşivi (her karar bir klasör)
├── workbook/                ← Hamlet Workbook (BU klasör)
│   ├── CLAUDE.md            ← Bu doküman
│   ├── errata-listesi.md    ← 2. baskı errata + klinik güvenlik eklemeleri
│   └── karsilastirma-raporu.md  ← Workbook ↔ App köprüleri
├── method-book/             ← Method Kitabı (Faz 2 başı)
├── app/                     ← ITC App (submodule, github.com/beytiengin/itc-app)
└── workshop/                ← Workshop atölye katmanı
    ├── spine.md
    ├── kurumsal-pilot-paketleri/
    │   ├── berlin-eylul-2026/      ← Karar 18 pilot
    │   └── hmdk-stuttgart-ocak-2027/ ← Karar 17 pilot
    └── karakter-dosyalari/
```

**Önemli:** Workbook ayrı bir repo DEĞİL — itc-canon'un alt klasörü. Önceki briefing eskisinde ayrı bir `inside-the-hamlet/` repo önerisi vardı; bu kanon yapıya uyarlandı (Spine §1 + Brief §1.1 dört katmanlı ekosistem mantığına göre).

---

## 3 · Workbook İçeriği

### 3.1 Print-Ready PDF (Türkçe)
- `inside_hamlet.pdf` — 316 sayfa (içindekiler + kitap), 170×240mm, 5MB. Basıma hazır.

### 3.2 Bütüncül HTML Galeri
- `galeri_butun.html` — 24 dosya birleşik, 316 sayfa, 814KB. Tarayıcıda göz atma için.

### 3.3 İçindekiler (s.iii-iv)
- `icindekiler.html`

### 3.4 Aşama 2 — 7 batch HTML (Eşik + Kısım I + Kısım II + Bütünleşme)
- `batch9_esik.html` — Eşik (s.1-30)
- `batch10_kisim1.html` — Kısım I Tanışma (s.31-45)
- `batch11_kisim2_dogrular_oyunoncesi.html` — Kısım II/1 Doğrular + Oyun Öncesi (s.46-65)
- `batch11_kisim2_timeline.html` — Kısım II/2 Timeline (s.66-85)
- `batch12_yazarin_cercevesi.html` — Kısım II/3 Yazarın Çerçevesi (s.86-105)
- `batch12_senin_cerceven.html` — Kısım II/4 Senin Çerçeven (s.106-125)
- `batch13_butunlesme.html` — Bütünleşme (s.290-314)

### 3.5 Aşama 1 — 16 dosya (Kısım III Yolculuk Modu, s.126-289, ~110 dk)
- `bolum_i_tam.html` … `bolum_xiii_tam.html` (13 bölüm)
- `yoklama_1_tam.html`, `yoklama_2_tam.html`, `yoklama_3_tam.html` (3 yoklama)

### 3.6 İngilizce baskı dosyaları
- `translation_manual_v04.md` — Translation Manual v0.4 (locked terminoloji + felsefe + kaynaklar)
- `threshold_pilot_v01.html` — Threshold ilk 11 sayfa İngilizce pilot

> **Not — Fiziksel dosya durumu (15 Mayıs 2026 kısmi yedirme):** Aşağıdaki dosyalar `workbook/tr/` altında local repo'da:
> - Aşama 1 (Yolculuk Modu Kısım III): `bolum_ii`, `bolum_iii`, `bolum_iv`, `bolum_v`, `bolum_vi`, `bolum_viii`, `bolum_ix`, `bolum_x`, `bolum_xi` — 9 bölüm
> - Yoklama: `yoklama_1_tam.html`, `yoklama_2_tam.html`
>
> **Hâlâ eksik (Claude.ai sohbetinden indirilip alınmalı):**
> - Aşama 1 bölümler: `bolum_i_tam.html` (Tanışma), `bolum_vii_tam.html` (Hayalet), `bolum_xii_tam.html` (Mezarlık — Çapa 4), `bolum_xiii_tam.html` (Düello — Çapa 5)
> - `yoklama_3_tam.html`
> - Aşama 2: `batch9_esik.html` (Eşik), `batch10_kisim1.html`, `batch11_kisim2_dogrular_oyunoncesi.html`, `batch11_kisim2_timeline.html`, `batch12_yazarin_cercevesi.html`, `batch12_senin_cerceven.html`, `batch13_butunlesme.html`
> - Ana dosyalar: `inside_hamlet.pdf`, `galeri_butun.html`, `icindekiler.html`
> - İngilizce: `translation_manual_v04.md`, `threshold_pilot_v01.html` (`workbook/en/`'e)

---

## 4 · Önemli Kararlar — Workbook Bağlamında

### 4.1 · Karar 1+2 (Spine v1.1, 6 Mayıs 2026) — Workbook ↔ App Entegrasyonu

1. **Modül II Hamlet refactor kararı (Karar 1):** App'teki Modül II 9 antrenmanı, Workbook yapısına göre yeniden inşa edildi (Doğrular → Timeline → Yazarın Çerçevesi → Senin Çerçeven) — Spine v1.2'de tamamlandı
2. **Modül III pilot kararı (Karar 2):** Workbook'un 13 yolculuk metni (s.126-289, ~110 dk), App Modül III'ün ilk pilotu olacak (Faz 1 Milestone 1.2)
3. **Konumlandırma sentezi:** Ekosistem "ticari ama akademik duran" (Brief v2.3 §1.2)

### 4.2 · Workbook Sürüm 1.1'de Düzeltilenler (4 tutarsızlık)

1. İthaf typo: B.E. & F.E. → **B.E. & F.K.A.** (s.5)
2. Bölüm XI çift isim → **"Anne ile Yüzleşme"** her yerde (s.10 ToC ve bölüm başlığı)
3. ToC sayfa numaraları güncellendi (s.9 ve s.10'da +70 / +164 kaydırmalar)
4. Bölüm IX çift isim → **"Var olmak mı, Yok olmak mı"** her yerde

### 4.3 · Eyüboğlu Çevirisi Uyumu — Tamamlandı

**76 değişiklik** uygulandı: 55 Aşama 2'de + 21 Aşama 1'de. Kitap boyunca tek tutarlı Eyüboğlu çevirisi var. Önemli olanlar:

- *"Olmak ya da olmamak"* → *"Var olmak mı, yok olmak mı"*
- *"Geri kalanı sessizlik"* → *"Üst tarafı… sessiz bir dünya"*
- *"Olgunlaşmak her şey"* → *"Bütün mesele hazır olmakta"*
- *"Bir sıçan!"* → *"Ne o? Bir fare mi?"*
- *"Kırk bin kardeş aşkı"* → *"Bin kardeşi bütün sevgilerini"*
- *"Bir serçenin düşmesinde takdir-i ilahi var"* → *"Serçenin ölmesinde bile bir bildiği vardır kaderin"*

### 4.4 · İngilizce Baskı Kararları (Translation Manual v0.4)

- Shakespeare kaynağı: **RSC Shakespeare Complete Works** (Bate & Rasmussen, 2007)
- Başlık: *Inside The Hamlet — An Actor's Workbook for Character Construction*
- Felsefe: **Hibrit** (ITC sadık, ton uyarlanmış)
- Locked terminoloji: **Doğrular → The Givens** (Stanislavski) · **Saray → the Court** · **Kulis → The Wings** · **Anne ile Yüzleşme → The Closet Scene**
- Çevirmen: **AI-assisted translation, edited by Beyti Engin & Filiz Kaya Ataklı**
- Kültürel referanslar: Anglo-Amerikan tiyatro karşılıkları (Bülent Emin Yarar → Robert Wilson, Ayla Algan → Vanessa Redgrave/Judi Dench)
- Eyüboğlu kredisi gider, RSC kaynak künyesi gelir

### 4.5 · Workbook Etkili Diğer Kararlar (Spine v1.3-v1.9)

- **Karar 10 (Spine v1.5):** Doğrular Çift Üçlü ve 3×3 Matris (Kaynak × Katman) — Workbook s.51 Kaynak Üçlüsü korundu, 2. baskıda Katman Üçlüsüne çapraz referans eklenecek
- **Karar 16 (Spine v1.7):** Filiz Kaya Ataklı Eş Kurucu statüsü — Workbook 2. baskıda ithaf ve kapak künyesi bu çerçevede revize edilir (zaten ithafta B.E. & F.K.A. var)
- **Karar 20 (Spine v1.8):** Sıralama kuralı (BE → FKA) + BE/FKA özgeçmiş sabit hâlleri — Workbook 2. baskı kapak künyesi ve hakkında sayfaları bu sabit hâllere göre yazılır
- **Karar 21 (Spine v1.9):** Yıldız Profil Eşleşme Matrisi geri çekildi — Workbook 2. baskıda Yıldız eşikleri atıfları varsa errata listesine eklendi (`errata-listesi.md`)

---

## 5 · Açık İşler — Öncelik Sırasıyla

### Yakın vade
1. **Threshold kalan s.12-30 İngilizce çevirisi** (Önsöz 2 + "Bu kitap nedir" spread'i ile devam)
2. **2. baskı klinik güvenlik eklemeleri** (Eşik helpline notu, öz-tarama, "terapi değildir" disclaimer'ı, Yoklama dallarına "iyi değilsen" 3 satırı) — `workbook/errata-listesi.md`'ye işle
3. **2. baskı errata** (s.310 "11 yolculuk" → 13, Method Book geri-referansları, TOC tutarsızlığı) — `workbook/errata-listesi.md`
4. **Workbook materyallerinin local repo'ya alınması** — PDF, HTML batch'ler, çeviri pilotu Claude.ai project knowledge'dan indirilip workbook/ altına kopyalanmalı (`tr/` ve `en/` alt klasörleri açılabilir)
5. **İthaf + Önsöz özgün metinleri** (BE+FKA yazacak — Karar 16 + Karar 20 hizalı sabit hâlleri kullanarak)
6. **Kolofon bilgileri** (s.314): ISBN, kesin tarih, basım yeri

### Orta vade
7. **Part I → III → Integration İngilizce çevirisi** (Threshold pilotu kabul edildikten sonra)
8. **Mobil/dijital uzantı** — sesli not + Whisper deşifre + Beyti'nin sesi (ElevenLabs) → Spine'da App tarafıyla bağlantılı, Modül III pilotu içinde uygulanacak (Brief v2.3 Milestone 1.2)
9. **App entegrasyonu** — Workbook ↔ App köprüleri (in-book QR kod, App içinden "Workbook'ta tam metin" linkleri) — `workbook/karsilastirma-raporu.md` baz alınır

### Karar 21 sonrası işler (15 Mayıs 2026)

- **2. baskı errata listesinde:** Yıldız Profil Eşleşme atıfları varsa revize (errata-listesi.md'de işle)
- **Workbook'taki travma kategorisi etiketlemesi:** Spine §3.3 yeni sahne-level uyarı sistemine göre her bölüme kategori + yoğunluk etiketi (2. baskı için)

---

## 6 · İlk Mesajda Söyleyeceklerin (Şablon)

```
Selam Claude. Inside The Hamlet (Hamlet Workbook) projesinde çalışıyoruz —
ITC ekosisteminin dört katmanından biri. 314 sayfa, sürüm 1.0 print-ready.

Önce şu dosyaları oku:
1. workbook/CLAUDE.md (bu doküman, projenin tam bağlamı)
2. spine.md (Spine v1.9, ekosistem omurgası)
3. decision-log.md (Karar 1-21, en üstten en alta)
4. brief-v2.md (Brief v2.3, operasyonel yol haritası)

Sonra [yapmak istediğin iş] üzerinde çalışmaya başlayalım.
```

---

## 7 · Önemli Uyarılar (Spine v1.9 ile hizalı)

### ⚠ Eyüboğlu telifi

Workbook'ta Türkiye İş Bankası izniyle kullanılıyor — kişisel/atölye kullanımı için. **Ticari uygulama (App üzerinden satış) için ayrı lisans gerekir.** Brief v2.3 §9.3 açık karar: "Eyüboğlu telifi App'te ticari kullanım için lisans yenilemesi gerekiyor mu? (kritik, Faz 1'de çözülmeli)"

### ⚠ ITC etik çerçeve (Spine §3.1 + Karar 21 sonrası)

> *"Karakter senin kişisel travmalarınla inşa edilmez. Karakterin kendi verisi vardır."* (Substitution Yasağı, §3.1)
>
> *"Sahip değil — misafir."* (Workbook s.18, Kabul 4'ün uygulamalı motto formu)

ITC oyuncunun kendi biyografik travmalarına dönmesini istemez. Karakterin verisi karakterin kendisinden çıkarılır. Bu Workbook'un tüm bölümlerinde aynen geçerli.

### ⚠ Travma Matrisi (Spine §3.2) — 8 Kategori × 4 Yoğunluk

**Kategoriler:** Şiddet · Kayıp · İhanet · Cinsel · Zihinsel Kırılma · Çocukluk · Ahlaki Yara · Varoluşsal

**Yoğunluk:** 0 Yok · 1 Atıf · 2 Tanıklık · 3 İcra

> **Not:** Önceki briefing'de "8×3" yazıyordu — bu yanlış. Kanon **8×4** (4 yoğunluk seviyesi, "0 Yok" dahil; Spine §3.2 v1.3'ten beri teyitli).

Workbook 2. baskısında her bölüme travma kategorileri ve yoğunluk değerleri etiketlenir (klinik güvenlik için).

### ⚠ Sahne-Level Etik Uyarı (Spine §3.3 — Karar 21, v1.9)

**Karar 21 (15 Mayıs 2026) ile geri çekilen yapı:**
- Eski: "Yıldız eşikleri (≥5/3-5/<3)" üzerinden oyuncu profili-bazlı gate
- Yeni: Sahne-level uyarı; oyuncu profili sahne erişimini etkilemez

**Yeni mantık:** Travma kategorileri sahne-level etiketlemedir; karakter verisinden metinden çıkarılır. Oyuncuya **uyarı** olarak gösterilir, gate değil. Yoğunluk 2-3 sahneler sonrası §3.4 Topraklanma Protokolü otomatik tetiklenir (kategori- ve profil-bağımsız).

Workbook 2. baskıda **eski Yıldız eşikleri atıfları varsa revize edilir** — `errata-listesi.md`'de işle. Karar 21 gerekçesi: Substitution Yasağı (§3.1) ile yapısal uyum (karakter, oyuncudan bağımsız bir veri yapısıdır).

### ⚠ Topraklanma Protokolü (Spine §3.4) — 6 adım

Workbook s.288-289'da Hamlet'e özel adaptasyon var. Yoğunluk 2 (Tanıklık) veya 3 (İcra) sahneler sonrası **otomatik önerilir** (Karar 21, kategori- ve profil-bağımsız).

Adımlar:
1. Nefes (4-4-6, üç tekrar)
2. Bedene dönüş (eller, yüz)
3. İsim (üç kez yüksek sesle)
4. Tarih (gün-ay-yıl)
5. Mekân (5 farklı renk/nesne)
6. Kapanış cümlesi: "Karakter orada — ben buradayım."

### ⚠ Bölüm IX çapa cümlesi

En dikkat isteyen yer, klinik güvenlik notu var (4 Mayıs Gottman incelemesi). Brief v2.3 §9.2 açık karar: "Bölüm IX çapa cümlesi ek koruma katmanı". 2. baskı errata'da klinik güvenlik eklemesi olarak işlenir — `errata-listesi.md`'de yer alıyor.

---

## 8 · Workbook ↔ Ekosistem Çapraz Atıflar

### Method Book
- Workbook Bölüm I-V akış yapısı, Method Book Bölüm F (Karaktere Hazırlık Soruları, 9 adım × 3 Giriş Kapısı) ile çapraz referanslı
- 2. baskıya Method Book geri-referans formatı eklenir (sayfa numaraları)
- Method Book Bölüm C/Modül II'nin teorik temeli Workbook'taki karakter sayfası mimarisidir (Spine §4.1)

### App
- App Modül II Hamlet refactor Workbook s.50-125 ile birebir hizalandı (Karar 1, Spine v1.2'de uygulandı)
- App Modül III yolculuk modu Workbook s.126-289 metinleri üzerine kuruluyor (Karar 2, Faz 1 Milestone 1.2)
- Çapraz referans detayı: `workbook/karsilastirma-raporu.md`

### Workshop
- Workbook'un Bölüm IX çapa cümlesi ve Topraklanma adaptasyonu Workshop'taki transmisyon mimarisinde (Spine §3.13) FKA klinik on-call tetikleyicisi olarak işlev görür
- Berlin pilotu (Karar 18, Eylül 2026) ve HMDK pilotu (Karar 17, Ocak 2027) Workbook materyalini kullanır
- Workshop Tek Karakter İlkesi (§3.14) gereği A2 kohortları Hamlet etrafında toplanır — Workbook bu transmisyonun temel materyalidir

---

## 9 · Çalışma Akışı (Claude Code)

### Repo yapısı
- Workbook ITC ekosistem repo'sunun (`itc-canon`) alt klasörü
- Spine + Decision Log her zaman bir üst dizinde
- Karar paketleri `itc-canon/kararlar/` altında arşivlenir

### Workflow
1. Yeni oturumda önce bu CLAUDE.md'yi oku → Workbook bağlamı
2. `spine.md` v1.9 oku → ekosistem omurgası
3. `decision-log.md` (en üstten en aza Karar 21 → Karar 1) gözden geçir
4. Yapılacak işe göre `workbook/errata-listesi.md` veya `workbook/karsilastirma-raporu.md` aç
5. Edit/iterate döngüsü Claude Code'da hızlı (file system erişimi var)

### Karar yedirme akışı

Yeni karar geldiğinde:
1. `kararlar/YYYY-MM-DD-konu/` klasörü açılır
2. `decision-log.md` en üste yeni karar girişi eklenir
3. `spine.md` etkilenen alt-bölümler güncellenir + sürüm artar
4. `brief-v2.md` revizyon notu eklenir (her v2.X)
5. Etkilenen katman dokümanları (workbook/CLAUDE.md, app/CLAUDE.md, vs.) güncellenir
6. `.claude/rules/etik-cerceve.md` etkileniyorsa güncellenir

Detay: `.claude/rules/decision-log-format.md`

---

## 10 · Sürüm Notları

- **v1.0 (briefing)** — 15 Mayıs 2026 — Claude.ai project knowledge'dan Claude Code'a aktarım için hazırlanan ilk briefing. Spine v1.1 referansı + 8×3 travma matrisi + Yıldız eşikleri (≥5/3-5/<3) içeriyordu. **Kanon-uyumsuzluklar mevcuttu** (Karar 21'den önce hazırlanmış).
- **v1.1 (yedirme)** — 15 Mayıs 2026 — Bu doküman. Spine v1.9'a hizalandı; 8×4 travma matrisi kanonu netleştirildi; Karar 21 sonrası Yıldız Profil Eşleşme geri çekildi (yeni mimari: sahne-level uyarı sistemi). Repo strüktürü itc-canon altında workbook/ alt klasör olarak uyarlandı. Karar 1-21 atıfları eklendi.

---

*Inside The Hamlet · ITC Ekosistemi dört katmanından biri*
*Eş Kurucular ve Eş Eğitmenler: Beyti Engin & Filiz Kaya Ataklı (Klinik Psikolog)*
*Operasyonel Eş Yazar (AI): Claude (Anthropic)*
