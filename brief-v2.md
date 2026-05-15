# ITC EKOSİSTEM — Geliştirici Brief'i

**v2.3**

**Eş Kurucular ve Eş Eğitmenler:** Beyti Engin & Filiz Kaya Ataklı (Klinik Psikolog)
**Operasyonel Eş Yazar (AI):** Claude (Anthropic)
**Tarih:** 15 Mayıs 2026 (v2.1: 12 Mayıs 2026 HMDK tarih düzeltmesi · v2.2: 12 Mayıs 2026 Karar 16 — FKA Eş Kurucu · v2.3: 15 Mayıs 2026 Karar 17-21 kompoze yedirme)
**Hedef:** Mayıs 2028 (24 aylık yol haritası)
**Spine Sürümü Referansı:** v1.9 (15 Mayıs 2026 itibarıyla) — dört katmanlı yapı (Method Book / Workbook / App / Workshop) operasyonel; §3'te sekiz yeni kanon alt-bölümü (§3.10–3.17, son §3.17 Yöntem Tarihsel Çizgisi); Karar 16 ile eş kurucu statüsü kanonlandı; Karar 21 ile Yıldız Oyuncu Matrisi pedagojik araç olarak ayrıldı, travma sistemi sahne-level çalışıyor.

---

## ÖNSÖZ — Bu Brief Niçin Yazıldı?

ITC, üç katmanlı bir ekosistemdir: Method Kitabı, Hamlet Workbook, ITC App. Spine v1.1 ile bu üçünün birbirine atıf veren, sabit ilkelerle bağlı, canlı bir yapı olduğu netleşti. Ancak şu ana kadar üç katman paralel geliştirildi — birbirini besleyen, birbirini güncelleyen bir sistem henüz operasyonel değil.

Bu brief, üç katmanlı ekosistemin önümüzdeki 24 ay boyunca:

1. Tek kişi (Beyti) tarafından, ara ara Filiz onayıyla yürütüldüğü gerçekliğinde
2. Claude'un aktif eş yazar olarak haftalık ritimle dahil olduğu yapıda
3. Sürdürülebilir, ölçülebilir, ve birbirine atıflarla canlı kalan bir biçimde

nasıl ilerleyeceğini tanımlar.

Brief'in stratejik tonu bilinçli olarak "vizyon-ön planda, teknik detay yedek" kuruluyor. Geliştirici tek kişi olduğu için, kararların **niçin verildiği** **ne yapıldığından** daha önemli — çünkü bu sayede yarın koşullar değişirse, kararı yeniden formüle etmek mümkün.

**v2.1 revizyon notu (12 Mayıs 2026):** Bu revizyon Brief v2.0'ın genel yapısını korur. Tek stratejik değişiklik HMDK Stuttgart pilotunun faz konumudur — Faz 3 Milestone 3.1'den çıkarılıp Faz 2 ortasına (Ocak 2027, Ay 8) taşındı. Bu değişiklik Schlegel-Tieck Hamlet adaptasyonunu Mayıs–Temmuz 2026 (Faz 1 başı) kritik bir sprint hâline getirir. Ayrıca Spine v1.6 referansı güncellendi.

**v2.2 revizyon notu (12 Mayıs 2026, Karar 16):** Filiz Kaya Ataklı'nın **Eş Kurucu ve Eş Eğitmen** statüsü ekosistem genelinde kanonlandı. Üst meta'da "Klinik & Akademik Eş Sahip" formülasyonu "Eş Kurucular ve Eş Eğitmenler" olarak güncellendi; yazar/kurucu bağlamında "×" → "&"; §2.4 risk profilinde "Beyti tek-kişi-bağımlılığı" azaltma sütununa Karar 16 atfı; §10.4'te "FKA klinik onayı" formülasyonu "eş yazar imzası" düzeyine yükseltildi; §1.4 Milestone 1.4 hedef formülasyonu "Eş Kurucu ve Eş Eğitmen" olarak güncellendi. Spine v1.7 referansı. **Filiz yazılı onayı bekleniyor — provisional.**

**v2.3 revizyon notu (15 Mayıs 2026, Karar 17-21 kompoze paket):** Workshop Sonuç Paketi (13 Mayıs 2026) ve Yıldız–Travma Ayrılması (15 Mayıs 2026) Brief'e bütünleşik tek paket olarak yedirildi:

- **Karar 17 (HMDK Stuttgart 13 madde bağlam):** Milestone 2.7 detaylandı — 25-29 Ocak 2027, A2-intensive ilk akademik kurumsal uygulama. Açık [DOLDUR] alanları §9.4'e taşındı.
- **Karar 18 (Berlin Chubbuck Studio Eylül 2026 pilotu):** Yeni Milestone 1.6.5 eklendi — Workshop katmanının ilk gerçek pilotu, A2-Berlin-Variant'ın kurucu uygulaması. Marka geçişi kanon: "Character Design" emekliye, **"Inside The Character Berlin"**.
- **Karar 19 (Yolculuk süresi 45-60 dk + Karakter spektrumu sınırı yok + Ses kayıt etiği):** §3 atıfları güncel; Karar 19 B+C Filiz klinik onayı bekleyen olarak §9.4'te kayıtlı.
- **Karar 20 (Yöntem Tarihsel Çizgisi + Sıralama Kuralı + Özgeçmiş Sabit Hâlleri):** Önsöz/§1.1'e tarihsel çizgi entegre edildi, yan kanonlar (NIPAI yok, "1000+" iddiası verilmez, "eş yürütücü"/"birincil yürütücü" kullanılmaz) belgelendi. BE & FKA özgeçmiş sabit hâlleri **yeni EK D** olarak eklendi. Tüm Brief'te sıralama her zaman **Beyti Engin önce, Filiz Kaya Ataklı sonra** (tarihsel kanıt alıntıları istisna).
- **Karar 21 (Yıldız Oyuncu Matrisi ve Travma Sistemi Ayrılması):** §3.3 hizalandı (Sahne-Level Etik Uyarı, Spine v1.9). §2.3 App durumu Yıldız konumlandırması revize. §3.4 Topraklanma tetikleyicisi yoğunluk 2-3 olarak güncellendi. §9.4'e app refactor açık kararları eklendi.

Spine v1.7 → v1.9 referans güncellemesi tüm Brief'e yansıdı. Detay arşiv: `kararlar/2026-05-13-workshop-sonuc-paketi/` + `kararlar/2026-05-15-yildiz-travma-ayrismasi/`. **Filiz yazılı onayı bekleniyor — provisional** (Karar 16 + Karar 19 B+C için; Karar 17, 18, 20, 21 onaylı).

---

## 1. STRATEJİK ÖZET

### 1.1 ITC Nedir? (Spine v1.9 §1'den)

**Yöntem tarihsel çizgisi (Karar 20, v1.8 — kanonik ifade):**

> Inside The Character (ITC), 20 yılı aşkın araştırma ve pratiğin sentezidir. Beyti Engin ve Filiz Kaya Ataklı tarafından 2005'ten bu yana birlikte geliştirilen yöntem, İstanbul'da Pozitif Atölye'de pratik temelini attı; 2022'den bu yana HMDK Stuttgart ve Chubbuck Studio Berlin'de profesyonel oyunculara aktarılmaktadır.

**Yan kanonlar (uyulması zorunlu negatif kurallar):**
- **NIPAI ile çalışma YOK.** NIPAI görüşme aşamasındadır; tanıtım metinlerinde "ortaklık" veya "bağlantı" ifadesi kullanılmaz.
- **2021 veya sonrasında basılmış kitap YOK** (ITC marka altında). Method Book ITC ekosisteminin ilk kanonik akademik yayını olacak (Faz 3 Milestone 3.4).
- **"1000+ profesyonel oyuncu" iddiası doğrulanmamış** — rakam verilmez, "20 yılı aşkın pratik sentezi" ifadesi kullanılır.
- **"Eş yürütücü" / "birincil yürütücü" / "primary practitioner" kullanılmaz** (Karar 16). Doğru kanonik unvan: "Eş Kurucu ve Eş Eğitmen" (TR), "Co-Founder & Co-Instructor" (EN), "Mitbegründer/in & Co-Trainer/in" (DE).

**Sıralama Kuralı (Karar 20, v1.8):** Tüm Brief'te ve dış iletişimde isim sıralaması her zaman **Beyti Engin önce, Filiz Kaya Ataklı sonra**. Tarihsel kanıt alıntıları (Karakter Tasarım 2021 kapağı, Chubbuck Studio Berlin sitesi eski formülasyonu) istisna; retroaktif değiştirilmez.

**Dört katmanlı yapı:**

ITC tek bir ürün değil — dört katmanı olan bir sistemdir:

| Katman | Form | Hedef Kitle | İşlev |
|---|---|---|---|
| Method Kitabı | Basılı kuramsal+pratik kitap (~320 sf) | Eğitmenler, ileri oyuncular, akademi | Foundation. Yöntemin kavramsal otoritesi. |
| Hamlet Workbook | Basılı uygulamalı çalışma kitabı (314 sf) | Tek başına çalışan oyuncu, prova öncesi | Yöntemin tek karaktere derinleşmiş hâli. |
| ITC App | Web uygulaması, mobil uyumlu | Günlük antrenman yapan oyuncu | Dijital günlük pratik. Kalibrasyon + kısa antrenman. |
| Workshop | Program şablonları + eğitmen kiti | Eğitmen, kurum (akademi, atölye) | Yöntemin operasyonel mimarisi. Kurumsal ölçeklenme. |

*Not: Workshop dördüncü katman olarak Spine v1.3 (8 Mayıs 2026) sonrası eklendi. İlk gerçek pilot **Milestone 1.6.5 Berlin Eylül 2026** (Karar 18, A2-Berlin-Variant kurucu uygulaması); ikinci dalga **Milestone 2.7 HMDK Stuttgart 25-29 Ocak 2027** (Karar 15 + Karar 17, A2-intensive akademik kurumsal uygulama).*

### 1.2 Konumlandırma Sentezi — "Ticari ama akademik duran"

Method Book akademik prestiji taşır; App+Workbook ticari geliri sağlar; bu sentez ekosistemin sürdürülebilir kalmasının kilidi. Akademik meşruiyet olmadan ticari ölçek itibarsız; ticari altyapı olmadan akademik proje finansmansız.

---

## 2. DÖRT KATMANIN GÜNCEL DURUMU

### 2.1 Method Kitabı — Inside The Character

**Durum:** Master Outline v3 hazırlanmakta. Manuscript yazımına henüz başlanmadı.

**Yapı:** A. Giriş · B. Felsefe · C. Üç Modüllü Sistem · C-Ek. Performans Blokajları · D. Etik · E. Vakalar · F. Ekler.

**Sonraki adım:** Bölüm III (Modül II — Karakteri Tanı) prototip yazımı (Faz 1 Milestone 1.7).

*Not (v2.1): Method Book Bölüm E (Uygulama Vakaları), HMDK Stuttgart pilotunun (Ocak 2027) verisini canlı vaka olarak alacak. Bölüm E yazımı Faz 2 boyunca pilotla paralel ilerler.*

### 2.2 Hamlet Workbook

**Durum:** v1.0 basılı yayımda. 13 bölüm · 5 çapa · 3 bedensel yoklama · 314 sayfa. Eyüboğlu çevirisi: Türkiye İş Bankası Kültür Yayınları izniyle.

**Sonraki adım — 2. baskı errata:**
- s.310 "11 yolculuk" → 13 düzeltilir
- TOC tutarsızlığı düzeltilir
- Method Book'a geri-referanslar eklenir (sayfa numarası eşleşmeleri)
- Klinik güvenlik notları eklenir (Eşik'e helpline notu, dört-beş soruluk öz-tarama, Yoklama'lara "iyi değilsen" dalı, "terapi değildir" disclaimer'ı)
- Bölüm IX çapa cümlesi için ek koruma katmanı

### 2.3 ITC App — Actor's Gym

**Durum:** Canlı (erken beta). itc-app-six.vercel.app

- **Modül I — Kendini Tanı:** ✅ CANLI · 3 test (VAK 27, MBTI 12, Yıldız 37 — Karar 21 ile pedagojik öz-farkındalık haritası + karaktere yaklaşım katmanı; travma erişim eşiği kaldırıldı) · ~15 dk
- **Modül II — Karakterini İnşa Et:** ✅ CANLI · 4 karakter · 30 antrenman · 25-30 dk/antrenman

**Modül II Hamlet Refactor (v1.1 yeni karar):**
- Yeni sıralama: Doğrular (Workbook s.50-57) → Timeline (s.58-85) → Yazarın Çerçevesi (s.86-105) → Senin Çerçeven (s.106-125)
- Pilot Hamlet'te → sonra Macbeth, Willy, Biff
- Eski 9 antrenman retire edilmez, yeni yapıya entegre

**Modül III — Sahnele (Yolculuk):** ⏳ YAKINDA
- Pilot: Workbook 13 yolculuk metni (s.126-289), ~110 dk AI Dış Ses
- Topraklanma overlay: Workbook s.288-289
- TTS altyapısı: ElevenLabs Multilingual v2 (test aşamasında)

### 2.4 Risk Profili (Ekosistem Geneli)

| Risk | Olasılık | Etki | Azaltma |
|---|---|---|---|
| Beyti tek-kişi-bağımlılığı | Yüksek | Kritik | İçerik üretimi prosedürlü hale gelir (§7); Spine canlı tutulur; Claude eş yazar olarak sürekli devrede; **Filiz Kaya Ataklı eş kurucu statüsünün kanonlaşması (Karar 16) — ekosistem iki imzayla taşınır** |
| Eyüboğlu telif yenilemesi (App ticari kullanım) | Orta | Yüksek | Faz 1'de hukuk danışmanlığı + İş Bankası ile görüşme |
| FKA klinik onay darboğazı | Düşük | Orta | Kritik içerikler (travma, topraklanma) için protokol netleştirildi (§6.2) |
| Akademik meşruiyet gecikmesi | Orta | Orta | HMDK Stuttgart pilotu (Faz 3) + 1+ yayımlanmış makale (Faz 2) |
| Pazar uyumu bulamama (App) | Orta | Yüksek | Faz 1'de 100+ ücretli abone hedefi, funnel ölçümlü (PostHog) |

---

## 3. SABİT İLKELER (Spine v1.9 §3'ten Özet)

### 3.1 Substitution Kullanılmaz

ITC oyuncunun kendi biyografik travmalarına dönmesini istemez. Karakterin verisi karakterin kendisinden çıkarılır.

### 3.2 Travma Matrisi: 8 Kategori × 4 Yoğunluk

Şiddet · Kayıp · İhanet · Cinsel · Zihinsel Kırılma · Çocukluk · Ahlaki Yara · Varoluşsal. Yoğunluk: 0 Yok · 1 Atıf · 2 Tanıklık · 3 İcra. *(Spine v1.3 ile teyit; v2.0 brief metni "3 yoğunluk" diyorsa düzeltilir.)*

### 3.3 Sahne-Level Etik Uyarı (REVİZE — Karar 21, Spine v1.9)

§3.2 Travma Matrisi'nin sınıflandırması sahnelere atanır ve oyuncuya **uyarı** olarak gösterilir. Sistem oyuncu profilini (Yıldız Matrisi §3.9) hesaba katmaz; karakterin verisi karakterden çıkarılır, oyuncudan değil.

- Hiçbir sahne profile göre kilitlenmez (gate yok)
- Yoğunluk 2 (Tanıklık) ve 3 (İcra) sahneler sonrası §3.4 Topraklanma Protokolü otomatik tetiklenir (kategori- ve profil-bağımsız)

**Tarihsel kayıt (Karar 21 öncesi):** v1.0–v1.8 arası "Yıldız Profil Eşleşme Matrisi" (≥5: tüm seviyeler açık · 3–5: uyarılı · <3: bekleyiş) yapısı kullanılıyordu — Filiz Kaya Ataklı'nın kanonik klinik tasarımı. Karar 21 ile (15 Mayıs 2026) Filiz'in eş kurucu onayıyla geri çekildi; gerekçe Substitution Yasağı (§3.1) ile yapısal uyum.

> **Brief sürüm notu:** Bu alt-bölüm Karar 21 ile hizalandı (Spine v1.9, 15 Mayıs 2026). Brief'in genel sürüm referansı (üst meta §Spine Sürümü Referansı v1.7) v2.3 kompoze yedirmesinde Karar 17-21 birlikte güncellenir — sonraki tura ertelendi.

### 3.4 Topraklanma Protokolü (6 adım)

1. Nefes (4-4-6, üç tekrar)
2. Bedene dönüş (eller, yüz)
3. İsim (üç kez yüksek sesle)
4. Tarih (gün-ay-yıl)
5. Mekân (5 farklı renk/nesne)
6. Kapanış cümlesi: "Karakter orada — ben buradayım."

Hamlet'e özel adaptasyon Workbook s.288-289'da. App'te yoğunluk 2 (Tanıklık) veya 3 (İcra) sahneler sonrası otomatik overlay olarak kullanılır (kategori- ve oyuncu profili-bağımsız, Karar 21 v1.9).

### 3.5 Karakter Sayfası Mimarisi

Karakter Kimliği → Değiştirilemez Doğrular → Timeline → Yazarın Çerçevesi → Senin Çerçeven → Zihinsel Antrenman.

### 3.6 Üç Giriş Kapısı

Bilişsel · Bedensel · Duygusal. VAK'tan farkı: nasıl öğrendiğin değil, karaktere nereden girdiğin.

### 3.7 Altı Kabul

1. Karakter analiz edilmelidir.
2. Hiçbir analiz analiz edenden bağımsız değildir.
3. Oyuncu kendini de analiz etmelidir.
4. Karakter oyuncudan bağımsız yaratılmalıdır — "Sahip değil, misafir."
5. Tek yöntem yoktur — kişiye özel giriş kapıları vardır.
6. Zihin-beden bütünlüğü.

### 3.8 Kuramsal Zemin

Damasio · Goleman · Gardner · Levine · Csikszentmihalyi.

---

## 4. NEDEN ŞİMDİYE KADAR YAPMADIK? (Dürüst Değerlendirme)

İçerik geliştirme muazzam zaman aldı ve doğru bir yatırımdı:
- Hamlet Yolculuk Modu metni onlarca iterasyondan geçti (kalite ITC'nin temeli)
- Workbook v1.0 yayımlandı (314 sayfa, derinlemesine)
- Method Book Master Outline v2 hazır

**Ancak:**
- Pazar geri bildirimi olmadan içerik yapıldı (App'te henüz hiç ücretli müşteri yok)
- Üç katmanın çapraz atıfları kâğıt üzerinde (Spine'da) kaldı, operasyonel sistem olmadı
- Akademik altyapı (makale, vaka çalışmaları) ertelendi
- Ölçek altyapısı (eğitmen arayüzü, çoklu dil, ödeme) hiç yapılmadı

**Önümüzdeki 24 ay için denge değişiyor:** %30 içerik genişletme, %70 dağıtım altyapısı + ekosistem koordinasyonu.

---

## 5. 24 AYLIK YOL HARİTASI

Üç fazlı, milestone bazlı. Her milestone üç katmandan en az ikisini etkiler — çapraz güncellemeler her zaman gözetilir.

### FAZ 1 — Ürün-Pazar Uyumu + Ekosistem Koordinasyonu Kuruluş (Ay 0-6)

**Stratejik niyet:** App'te ücretli müşteri kazanmaya başla. Workbook 2. baskısının ön çalışmasını başlat. Method Book Bölüm III prototip yazımına geç. Ve en önemlisi: Çapraz Güncelleme Protokolünü operasyonel hale getir.

#### Milestone 1.1 — Çapraz Güncelleme Sistemi Kuruluşu (Ay 0-1)

Bu, brief'in stratejik kalbi. Diğer her şey buna bağlı.

**Çıktılar:**
- Spine v1.1 → v1.2 güncelleme: §6 (Güncelleme Protokolü) operasyonel hâle getirilir
- "Decision Log" sistemi kurulur (Notion sayfası veya markdown dosya)
- Pazar ritmi başlar (bkz. §6 Çapraz Güncelleme Protokolü)
- Claude'la haftalık check-in formatı belirlenir

**Kabul kriteri:** Sistem 4 hafta üst üste sorunsuz çalışmış. Decision log'da en az 8-10 kayıt var.

#### Milestone 1.2 — App: Yolculuk Modu Hamlet v1 Prodüksiyonu (Ay 1-2)

**Çıktılar:**
- 13 bölüm + Genel Giriş + 3 Yoklama + Çıkış = 18 ses dosyası
- ElevenLabs Multilingual v2 ile Türkçe seslendirme
- Supabase Storage'a yüklü, oynatıcı bileşeni hazır
- Bölüm geçişlerinde "hazırım" onayı (zorla ileri itmeyen UX)

**Kabul kriteri:** Bir oyuncu uygulamayı açıp baştan sona Yolculuk Modu Hamlet'i tamamlayabiliyor. Toplam üretim maliyeti ≤ $50.

**Çapraz etki:**
- → Workbook 2. baskıya: "App'te bu bölümün dijital pratiği" QR kod hazırlığı başlar
- → Method Book Bölüm IV taslağına: Modül III pilot deneyimi referans olur

#### Milestone 1.3 — App: Onboarding ve Ücretli Akış (Ay 2-3)

**Çıktılar:**
- Açılış sayfası: ITC nedir, üç katmanlı ekosistem hikâyesi (3 dakikalık video)
- Kayıt → Kalibrasyon → Modül II tanıtım → Yolculuk Modu Hamlet teaser akışı
- Stripe entegrasyonu (Türkiye için iyzico yedeği)
- Free Tier (Hamlet ilk bölümler) → Pro Tier yükseltme akışı
- Aboneliği iptal etme, faturalama (videolu özet, izinli)
- "Erken kayıt indirimi" — ilk 100 abone $9/ay (life-time)
- Email pazarlama altyapısı (Resend)
- Analytics: PostHog ile funnel takibi

**Kabul kriteri:** Bir kullanıcı kayıt → Kalibrasyon → ücretsiz içerik → ödeme → tam erişim akışını sorunsuz tamamlayabiliyor.

#### Milestone 1.4 — Klinik Onay Görünür Hale Gelmesi (Ay 2-3)

**Çıktılar:**
- Filiz Kaya Ataklı'nın adı ve fotoğrafı **"Eş Kurucu ve Eş Eğitmen (Klinik Psikolog)"** olarak ana sayfada (Karar 16, v2.2)
- Travma Etik Çerçevesi belgesi yayımlanmış (PDF, App'te ve Workbook arka eklerinde)
- Her travma kategorisi sayfasında ön tarama soruları (App'te)
- Crisis support kaynakları her seans öncesi/sonrası görünür

**Kabul kriteri:** Filiz "Adımı koymakta rahat hissediyorum" diyor. Bir hukuki danışman travma protokollerini incelemiş, yazılı onay vermiş.

**Çapraz etki:**
- → Workbook 2. baskı: aynı klinik güvenlik dili eklenir (Eşik'e helpline notu, vs.)
- → Method Book Bölüm VI (Eğitmen ve Etik): bu protokolün akademik versiyonu yazılır

#### Milestone 1.5 — Workbook 2. Baskı Hazırlığı (Ay 3-5, paralel)

**Çıktılar:**
- Errata düzeltmeleri tamamlanmış (s.310, TOC, vs.)
- Method Book'a geri-referans formatı belirlenmiş ve uygulanmış
- Klinik güvenlik eklemeleri (Bölüm IX dahil) eklenmiş
- "App'te bu bölümün dijital pratiği" QR kodları yerleştirilmiş
- İş Bankası Kültür Yayınları ile yeniden basım görüşmesi

**Kabul kriteri:** 2. baskı manuscript yayıncıya teslim edilmiş.

#### Milestone 1.6 — İlk 50 Ücretli Abone Kampanyası (Ay 4-6)

**Çıktılar:**
- Beyti'nin sosyal medya kanalları üzerinden launch (Instagram, LinkedIn — Türkçe oyuncu ağı)
- 4 vaka çalışmasının (Beren, Mehmet, Dicle, Mayda) halka açık formata getirilmesi

**Kabul kriteri:** 50 ücretli abone (≥$450/ay MRR). Funnel'da nerede insanlar kaybolduğunu biliyoruz.

**Çapraz etki:**
- → Method Book Bölüm V (Çağdaş Karakter): vaka çalışmaları akademik yazıma kaynaklık eder
- → Workbook ikinci baskı: vaka örnekleri ek olarak eklenebilir

#### Milestone 1.6.5 — Berlin Chubbuck Studio Pilot (Eylül 2026, Karar 18) ← v2.3'te eklendi

**Stratejik niyet:** Workshop katmanının **ilk gerçek pilotu**. A2-Berlin-Variant kurucu uygulaması — üç kademeli yapı (Auditor + Participant + Participant Advance). HMDK Stuttgart (Milestone 2.7, Ocak 2027) öncesi prototipleme katmanı; FKA Eş Kurucu sahasındaki ilk profesyonel oyuncu stüdyosu uygulaması.

**Marka geçişi (Karar 18, kanonik):**
- "Character Design" markası **emekliye** (Chubbuck Studio Berlin sitesinde tarihsel kayıt olarak korunur)
- Yeni kanonik marka: **"Inside The Character Berlin"**

**Ön Koşullar (Faz 1 başı/orta):**
- Chubbuck Studio Berlin web sitesi marka geçişi güncellemesi (kanonik geçiş için bekleyen — §9.4)
- Üç kademeli pilot tasarım paketi tamamlanmış (`workshop/kurumsal-pilot-paketleri/berlin-eylul-2026/`)
- FKA klinik koruma protokolü uygulamada (§3.13 transmisyon mimarisi + §3.16 yolculuk geometrisi)

**Çıktılar:**
- Üç kademeli pilot uygulaması Eylül 2026'da gerçekleştirildi
- A2-Berlin-Variant formatı valide edildi (HMDK için ön-test)
- Marka geçişi iletişim materyalleri yayında (web + sosyal medya)
- Yeni karakter kayıtları toplandı (`workshop/karakter-dosyalari/tarihsel-kayit-referanslari/`)

**Kabul kriteri:** Pilot tamamlandı, her üç kademede en az 4-6 katılımcı, geri bildirim ≥4/5; HMDK Stuttgart (Milestone 2.7) için en az 3 vaka hammaddesi.

**Çapraz etki:**
- → HMDK Stuttgart pilotu (Milestone 2.7) Berlin verisinden besleniyor
- → A2-Berlin-Variant formatı Workshop spine'da kanonik kayıt
- → Method Book Bölüm E (Faz 2) Berlin + HMDK kombine veri seti üzerinden yazılır

#### Milestone 1.7 — Method Book Bölüm III Prototip Yazımı (Ay 4-6, paralel)

**Çıktılar:**
- Üç Giriş Kapısı + Aşama 1 yazılmış (8-10 sayfa prototip)
- Filiz ile çift ses entegrasyonu test edilmiş
- App'in Modül II Hamlet refactor yapısıyla tutarlı (canlı geri besleme döngüsü)

**Kabul kriteri:** Prototip Filiz tarafından onaylanmış. Bir akademik danışman okumuş, yapı geri bildirimi vermiş.

#### FAZ 1 TAMAM SİNYALİ:
- ✅ App: 100+ ücretli abone, MRR ≥ $1.500
- ✅ Workbook: 2. baskı yayıncıya teslim
- ✅ Method Book: Bölüm III prototip yazılmış
- ✅ Çapraz Güncelleme Protokolü 6 ay boyunca sorunsuz işlemiş

---

### FAZ 2 — Ölçek + Akademik Meşruiyet Kuruluş (Ay 6-15)

**Stratejik niyet:** App'i tek dilli/tek karakter olmaktan çıkar. v2 Seans Modu'nu hayata geçir. Method Book ana yazım fazına gir. İngilizce versiyon başlat.

#### Milestone 2.1 — App v2 Seans Modu (Ay 6-9)

**Çıktılar:**
- WebRTC mikrofon erişimi
- Voice Activity Detection
- Whisper API (Edge Function proxy)
- Claude API streaming
- ElevenLabs Streaming TTS
- Hedef latency: <2 saniye

#### Milestone 2.2 — Method Book Ana Yazım Fazı (Ay 7-14)

**Çıktılar:**
- Tüm bölümler (A–F) yazılmış
- FKA klinik onay geçti (Bölüm D dahil)
- Akademik danışman okuması tamamlanmış
- Yayıncı sözleşmesi imzalanmış

#### Milestone 2.3 — İngilizce App Versiyonu (Ay 9-12)

**Çıktılar:**
- next-intl ile altyapı
- TR + EN içerik paritesi
- ElevenLabs İngilizce ses

#### Milestone 2.4 — Akademik Makale Yazımı (Ay 8-12)

**Çıktılar:**
- 1+ makale submitted (hedef dergi: Theatre, Dance and Performance Training veya benzeri)
- Konferans sunumu hazırlığı

#### Milestone 2.5 — Ek Karakterler (Ay 10-14)

**Çıktılar:**
- Macbeth tam Yolculuk Modu (~110 dk)
- Willy Loman tam Yolculuk Modu
- Biff Loman tam Yolculuk Modu

#### Milestone 2.6 — App Eğitmen Arayüzü v1 (Ay 12-15)

**Çıktılar:**
- Eğitmen hesap tipi
- Kohort oluşturma, öğrenci davet
- Öğrenci ilerleme görüntüleme
- Atama oluşturma
- Yansıma inceleme (oyuncu mahremiyetini koruma — opsiyonel paylaşım)
- $79-99/ay fiyatlandırma

**Kabul kriteri:** En az 5 ödeme yapan eğitmen, ortalama 8-10 öğrenci ile.

#### Milestone 2.7 — HMDK Stuttgart Pilot (Ay 7–9 — Yeni Konum, Karar 15) ← v2.1'de eklendi · v2.3'te detaylandı (Karar 17)

**v2.3 notu (Karar 17, 13 madde operasyonel bağlam):** Pilot tasarımı 13 maddeyle kanonlandı — A2-intensive ilk akademik kurumsal uygulama; FKA Eş Kurucu sahasındaki ilk akademik test. Pilot, Berlin Eylül 2026 pilotu (Milestone 1.6.5) verilerinden besleniyor. Detay arşiv: `kararlar/2026-05-13-workshop-sonuc-paketi/01-karar-17-hmdk-stuttgart.md` + `workshop/kurumsal-pilot-paketleri/hmdk-stuttgart-ocak-2027/`. Açık [DOLDUR] alanları (Prof. Katherina soyadı, anlık DE çevirmen kararı, saatlik tutar, pre-work temas anketi tasarımı) §9.4'te takipte.

**Stratejik niyet:** Ekosistemin Faz 2 ortasında akademik meşruiyet enjeksiyonu. HMDK Stuttgart'taki yarıyıl atölyesinde pilot gerçekleştirilir.

**Pilot Tarihi:** 25–29 Ocak 2027 (yarıyıl yoğunluğunda 5 günlük intensif modeli)

**Ön Koşullar (Faz 1'de bitmeli):**
- Schlegel-Tieck Hamlet adaptasyonu (kritik darboğaz, Mayıs–Temmuz 2026)
- HMDK ile resmi pilot anlaşması (Ekim 2026)
- App Modül III Almanca seslendirme (kısmi — pilotta kullanılacak bölümler)
- §3.13 (BE × FKA eş eğitmenlik) ve §3.16 (Yolculuk Geometrisi) Filiz klinik onayı geçmiş olmalı

**Çıktılar:**
- 5 günlük pilot atölye gerçekleştirildi (12+ öğrenci hedefi)
- §3.13 (eş eğitmenlik) ve §3.14 (tek karakter — Hamlet) ve §3.16 (yolculuk geometrisi) operasyonel test
- Pilot sonu rapor (Şubat 2027) — akademik makale (Milestone 2.4) ve Method Book Bölüm E için veri

**Kabul kriteri:** Pilot tamamlandı, en az 12 öğrenci tam döngüyü deneyimledi, pozitif geri bildirim (≥4/5), Method Book Bölüm E için en az 2 vaka çalışması hammaddesi çıktı.

**Çapraz etki:**
- → Akademik makale (Milestone 2.4) pilot verisiyle yazılır
- → Method Book Bölüm E pilot deneyiminden besleneceği için bu bölümün yazımı Şubat 2027 sonrası hızlanır
- → İngilizce App (Milestone 2.3) Almanca pilot deneyiminden i18n derslerini alır

#### FAZ 2 TAMAM SİNYALİ:
- ✅ App: 500+ ücretli abone (TR + EN), MRR ≥ $10.000
- ✅ Method Book: Manuscript tamamlanmış
- ✅ Akademik makale submitted
- ✅ Workbook 2. baskı yayımlanmış

---

### FAZ 3 — Kurumsal + Farklılaştırma + Ekosistem Olgunluğu (Ay 15-24)

**Stratejik niyet:** Bireysel pazarın ötesine geç. Method Book yayımlansın. ITC'yi tek kişiye bağımlı olmaktan kurtar.

#### Milestone 3.1 — İkinci Dalga Akademik Pilot (Ay 15-18, Karar 15 sonrası yeniden konumlandı)

**v2.1 notu:** HMDK Stuttgart pilotu Faz 2 Milestone 2.7'ye taşındı (gerçek pilot tarihi 25–29 Ocak 2027). Faz 3 Milestone 3.1 boşalan konum için "ikinci dalga akademik pilot" hedefli — Royal Central, RADA, veya Stella Adler bağlantılarından biri. Spesifik kurum kararı Faz 2 sonunda HMDK pilot raporundan sonra alınır.

**Çıktılar:** [İkinci dalga kurum belirlendiğinde detaylanacak]
- İkinci akademik kurumla pilot anlaşması
- HMDK pilot raporu pazarlama materyali olarak kullanılır
- Yeni dil/çeviri ihtiyacı (kurum İngilizce ya da farklı dilde olursa)

**Kabul kriteri:** İkinci kurumda pilot tamamlandı, HMDK ile karşılaştırmalı veri elde edildi (akademik makale için iki vakalık bir dataset).

#### Milestone 3.2 — App: Diğer Karakter Refactor'ları (Ay 15-18)

**Çıktılar:**
- Macbeth, Willy, Biff için Hamlet Modül II yapısı uygulandı (Doğrular → Timeline → Yazarın Çerçevesi → Senin Çerçeven)
- Her karakter için Modül III Yolculuk Modu canlıda

#### Milestone 3.3 — Karakter Üretim Internal Tool (Ay 18-21)

**Çıktılar:**
- Sadece admin erişimli sayfa
- ITC ilkeleri system prompt
- Karakter input → bölüm taslakları
- Otomatik kalite kontrol (meta-referans linting, üçüncü kişi tespiti)
- Beyti revizyon arayüzü

#### Milestone 3.4 — Method Book Türkçe Yayımı (Ay 20-22)

**Çıktılar:**
- Basılı kitap rafta (Routledge / Methuen Drama / Nick Hern Books — yayıncı kararı Faz 2'de verilmiş olacak)
- Launch kampanyası (akademi, tiyatro festivalleri)
- İlk 6 ay 1.000+ satış hedefi

#### Milestone 3.5 — Method Book İngilizce Çevirisi Başlangıcı (Ay 22-24)

**Çıktılar:**
- Çevirmen seçimi + sözleşme
- İlk 3 bölüm çevrilmiş
- Uluslararası yayıncı görüşmeleri

#### FAZ 3 TAMAM SİNYALİ:
- ✅ Method Book Türkçe yayımlanmış, 1.000+ satış
- ✅ HMDK Stuttgart pilot tamamlanmış, raporlanmış
- ✅ App: 1.000+ ücretli abone, MRR ≥ $20.000
- ✅ İngilizce çeviri başlamış
- ✅ 1+ akademik makale yayımlanmış

---

## 6. ÇAPRAZ GÜNCELLEME PROTOKOLÜ

Bu brief'in stratejik kalbi. Spine §6'yı operasyonel hale getirir.

### 6.1 Karar Tipleri

- **Tip 1 — Kanon Değişikliği** (Yüksek Öncelik): Kanonik bir kavram değişti
- **Tip 2 — Yapısal Karar** (Orta Öncelik): Bir projede yapısal karar verildi
- **Tip 3 — İçerik Güncellemesi** (Düşük Öncelik): İçerik değişti ama yapı aynı
- **Tip 4 — Açık Karar Çözüldü** (Orta Öncelik): Spine §5'teki açık kararlardan biri çözüldü

### 6.2 Yapılacaklar Akışı (Tip Bazlı)

**Tip 1:**
1. Spine §3 güncellenir (yeni sürüm)
2. Method Book taslağı revize edilir
3. Workbook 2. baskı errata listesine eklenir
4. App'in ilgili sayfaları güncellenir
5. Decision Log'a kayıt

**Tip 2:**
1. Spine §2 ve gerekirse §4 güncellenir
2. Etkilenen diğer projeler revize edilir
3. Decision Log kaydı

**Tip 3:**
1. Sadece Spine §2 (Güncel Durum) güncellenir
2. Diğer projelerde sayfa numarası değişiyorsa §4 atıfları güncellenir
3. Decision Log kaydı (kısa)

**Tip 4:**
1. Spine §5'ten kaldırılır, ilgili bölüme taşınır
2. Yeni Spine sürümü çıkar
3. Etkilenen projelere yansıtılır

### 6.3 Üç Senaryo — Somut Örnekler

**Senaryo A:** Workbook 2. Baskıda Bölüm IX Çapa Cümlesi Değişti (Klinik güvenlik gerekçesi)
- Workbook 2. baskı manuscript güncellenir
- App Modül III Bölüm IX seslendirmesi yeniden üretilir (ElevenLabs)
- Method Book Bölüm IV örneklerinde bu cümle kullanılıyorsa revize edilir
- Spine §2 Workbook bölümü güncellenir (errata notu)
- Decision Log: "Bölüm IX çapa cümlesi revize — [tarih] — Filiz klinik onay"

**Senaryo B:** App'te Yeni Karakter (Macbeth Modül III)
- Spine §2 App durumu güncellenir
- Method Book Bölüm V (Çağdaş Karakter) için vaka örneği olarak not edilir
- Workbook revize edilmez (Workbook sadece Hamlet)
- Marketing sitesi güncellenir
- Decision Log

**Senaryo C:** Method Book Bölüm III Prototip — "Üç Giriş Kapısı"nın Yeni Formülasyonu
- Spine §3.6 güncellenir (kanon değişikliği — Tip 1)
- App'in karakter sayfası mimarisi etkileniyor mu? Etkileniyorsa (§3.5) revize edilir
- Workbook 2. baskıya not edilir
- Yeni Spine sürümü çıkar
- Decision Log

### 6.4 Operasyonel Ritim — Tek Kişi İçin

**Pazar 30 Dakika — "Spine Health Check"**
Beyti her Pazar 30 dakika ayırır:
1. Son hafta hangi projede ne değişti? (5 dk)
2. Spine güncel mi? (10 dk — gerekirse güncellenir)
3. Üç projeye atıflar tutarlı mı? (5 dk — sample check)
4. Decision Log'a son hafta kayıtları girildi mi? (5 dk)
5. Filiz'e onay gereken bir şey var mı? (5 dk — varsa mesaj atılır)

**Ayda Bir — "Cross-link Audit" (Claude ile)**
Ayda bir Beyti, Claude'la birlikte:
1. Spine §4 (çapraz geçiş tabloları) gözden geçirir
2. Yanlış atıfları işaretler
3. Eksik atıfları tespit eder
4. Yeni Spine sürümü hazırlar
5. Üç projeye yansıtılması gereken değişiklikleri listeler

**Çeyreklik — "Strategic Review" (Beyti + Filiz)**
Üç ayda bir:
1. Bu brief'in milestone'ları gözden geçirilir
2. Faz ilerlemesi değerlendirilir
3. Açık kararlar gözden geçirilir
4. Yeni stratejik kararlar Decision Log'a girer
5. Brief gerekirse minor sürüm yükseltilir (v2.0 → v2.1)

### 6.5 Decision Log Sistemi

**Konum:** Notion sayfası VEYA `/itc-app/docs/decision-log.md` (App reposunda)
**Format:** Markdown, kronolojik

Her kayıt şu yapıda:

```markdown
## [Tarih] — [Kısa başlık]

**Tip:** Kanon Değişikliği / Yapısal Karar / İçerik Güncellemesi / Açık Karar Çözüldü
**Etkilenen katmanlar:** Method Book / Workbook / App
**Spine sürümü:** v1.X → v1.Y
**Karar veren:** Beyti / Filiz / Beyti+Filiz
**Karar:** [karar metni]
**Uygulama tarihi:** [hangi milestone'da uygulanır]
**Notlar:** [varsa ek not]
```

### 6.6 Claude'un Rolü — Aktif Eş Yazar

Beyti yalnız çalıştığı için Claude operasyonel olarak ekibin parçası:

**Haftalık (Pazar 30 dk içinde):**
- Beyti Spine'ı Claude'a okutur
- Claude tutarsızlıkları işaret eder ("§3.2'de 4 yoğunluk diyor ama §4.1'de 3 referans var — kontrol")
- Decision Log'daki son kayıtları gözden geçirir

**Aylık (Cross-link Audit):**
- Claude §4 atıflarını sistematik tarar
- Sayfa numarası tutarsızlıkları, eksik atıflar, gereksiz atıflar listeler
- Beyti'ye düzelti önerisi verir

**Çeyreklik (Strategic Review):**
- Claude faz milestone'larını Spine'la karşılaştırır
- Hangi milestone gerçekleşti, hangisi geri kaldı raporu
- Brief revizyonu için öneri hazırlar

**Olay Bazlı:**
- Yeni karakter yazılırken Claude ITC ilkeleriyle uyum kontrolü
- Yeni içerik (Workbook 2. baskı, Method Book bölümleri) yazılırken canlı eş yazar
- Akademik makale yazımında akademik dil ve referans kontrolü

---

## 7. TEKNİK MİMARİ HEDEFLERİ

### 7.1 Mevcut Stack (Korunan)

- **Frontend:** Next.js 14+ (App Router)
- **Backend:** Supabase (PostgreSQL + Auth + Storage + RLS)
- **Hosting:** Vercel

### 7.2 Eklenmesi Gereken Bileşenler

**Yolculuk Oynatıcı (Faz 1):**
```jsx
<YolculukOynatici karakter="hamlet" bolum={4} />
```
- MP3 streaming (Supabase Storage signed URL)
- "Hazırım" onay butonu her bölüm geçişinde
- Pause/resume tutuluyor (kaldığın yerden devam et)
- Acil çık butonu görünür her zaman
- Yansıma yazma alanı her bölüm sonunda (auto-save)

**v2 Seans Modu (Faz 2):**
- WebRTC mikrofon erişimi
- Voice Activity Detection
- Whisper API (Edge Function proxy)
- Claude API streaming
- ElevenLabs Streaming TTS
- Hedef latency: <2 saniye

**Karakter Üretim Internal Tool (Faz 3):**
- Sadece admin erişimli sayfa
- ITC ilkeleri system prompt
- Karakter input → bölüm taslakları
- Otomatik kalite kontrol (meta-referans linting, üçüncü kişi tespiti)
- Beyti revizyon arayüzü

**i18n Altyapısı (Faz 2):**
- next-intl
- Diller: tr, en, de
- İçerik markdown dosyaları olarak dil bazında klasörlenmiş

**Eğitmen Arayüzü (Faz 2):**
- Yeni tablolar: `kohortlar`, `kohort_uyeleri`, `atamalar`, `atama_yansimalar`
- Yeni sayfalar: `/egitmen/dashboard`, `/egitmen/kohort/[id]`

**Workbook QR Kod Entegrasyonu (Faz 1-2):**
- Workbook 2. baskıda her bölüm sonunda QR kod
- App'te `/workbook/[bolum]` sayfaları (App'in özel içeriği)
- Workbook satın alanlara App'te ek erişim (kupon kodu sistemi)

### 7.3 Aylık Operasyonel Maliyet

| Bileşen | Faz 1 | Faz 3 |
|---|---|---|
| Vercel Pro | $20 | $20-50 |
| Supabase Pro | $25 | $25-100 |
| ElevenLabs Creator | $22 | $99 (Pro) |
| Anthropic Claude API | $0 | $50-200 |
| Stripe / iyzico | %2.9+$0.30 | %2.9+$0.30 |
| Resend | $0-35 | $35 |
| PostHog | $0 | $0-50 |
| Crisp | $25 | $25 |
| Sentry | $26 | $26 |
| **Toplam (sabit)** | **~$120** | **~$330+** |

---

## 8. PAZARLAMA STRATEJİSİ (Genel Hatlar)

### 8.1 Faz 1 — Türkçe oyuncu ağı

- Beyti'nin Instagram + LinkedIn kanalları üzerinden organik
- 4 vaka çalışmasının halka açık formatı (Beren, Mehmet, Dicle, Mayda)
- Tiyatro festivalleri, oyunculuk atölyeleri ile temas

### 8.2 Faz 2 — Uluslararası akademi

- HMDK Stuttgart kontağı (mevcut bağlantı)
- Royal Central, RADA, Stella Adler ile pilot görüşmeleri
- Akademik makale + konferans sunumları

### 8.3 Faz 3 — Kurumsal lisans

- B2B/kurumsal pilot: Workshop kit + App lisansı paket
- $5K+/yıl kurumsal müşteri hedefi
- HMDK pilotu referans olarak

---

## 9. AÇIK KARARLAR (Spine §5'ten genişletilmiş)

### 9.1 Method Book

- Alt başlık: "Inside The Character" tek başına mı?
- "Actor's Gym" markasının kitap ile ilişkisi
- Manifesto madde 7-8'in nihai isimleri
- Bölüm I yapısı: Altı Kabul + Manifesto sonda mı, ayrı bölüm mü?
- Çağdaş vaka anonimleştirme derinliği

### 9.2 Workbook

- 2. baskıda Method Book'a geri-referans formatı
- Klinik güvenlik eklemeleri (öz-tarama uzunluğu, "iyi değilsen" dalı formatı)
- Bölüm IX çapa cümlesi ek koruma katmanı
- İngilizce baskı için RSC Shakespeare adaptasyonu

### 9.3 App

- AI sesli yönlendirmenin teknik altyapısı (TTS, ElevenLabs voice cloning?)
- Eyüboğlu telifi App'te ticari kullanım için lisans yenilemesi gerekiyor mu? (kritik, Faz 1'de çözülmeli)

### 9.4 Ekosistem Genel (açık)

- Method Book Türkçe ilk baskı + İngilizce çeviri sıralaması
- Yayıncı kararı (Routledge / Methuen Drama / Nick Hern Books)
- App'in yurt dışına açılma stratejisi (Stuttgart, RADA bağlantıları)
- Ekosistemin tek bir markası mı (Inside The Character) yoksa üç ayrı isim mi?
- **İkinci dalga akademik kurum kararı** (Faz 3 Milestone 3.1 için): Royal Central, RADA, Stella Adler arasından hangisi — HMDK pilot raporu sonrası karar

**v2.3'te eklenenler (Karar 17-21):**

- **HMDK Stuttgart pilot [DOLDUR] alanları (Karar 17):** Prof. Katherina soyadı, anlık DE çevirmen kararı, saatlik tutar, pre-work temas anketi tasarımı — pilot öncesi Ekim 2026'ya kadar netleşmesi gerek
- **Chubbuck Studio Berlin site güncellemesi (Karar 18):** Marka geçişi web sitesi yazımı ("Character Design" → "Inside The Character Berlin") — Eylül 2026 pilotundan önce tamamlanması gerek
- **Karar 19 B (karakter spektrumu sınırı yok):** ITC karakter konusunda sınır koymaz; etik filtre sahne-içeriği temelli işler — **Filiz klinik onayı bekleniyor, provisional**
- **Karar 19 C (ses kayıtları çift onaylı arşivleme etiği):** Heidrich + Eva Braun gibi tarihsel kayıtların ITC arşivinde çift onaylı (kişisel + arşiv için ayrı imza) saklanması — **Filiz klinik onayı bekleniyor, provisional**
- **Karar 21 sonrası app refactor (İş 2):** `app/lib/travma.js` `sahneErisimi` → `sahneUyarisi` + `topraklanmaGerekli`; karakter sayfası (willy/macbeth/biff) 6 boyut entegrasyonu; yeni `yildizYaklasimi(yildiz, karakter)` katmanı (`lib/kalibrasyon.js`). Detay: `kararlar/2026-05-15-yildiz-travma-ayrismasi/04-app-degisiklik-listesi.md`. UX framing metinleri zaten uygulandı; kod refactor sonraki iş paketinde.

### 9.5 Operasyonel Kararlar

- Domain ve marka: itcactorsgym.com mi, başka bir isim mi?
- Şirket yapısı: LTD Türkiye / Delaware C-Corp / hibrit?
- Filiz'in formal hisse durumu (eş kurucu olduğu netleşti, hisse %?)
- İlk 100 abone fiyatlandırması: $9 life-time vs $14 12-ay sınırlı?

---

## 10. KABUL KRİTERLERİ — 24 Ay Sonra Tamamlanmış ITC Ekosistemi

### 10.1 Method Kitabı

- [ ] Manuscript tamamlanmış, yayıncı sözleşmesi imzalanmış
- [ ] Türkçe baskı yayımlanmış
- [ ] İngilizce çeviri başlatılmış
- [ ] İlk 6 ayda 1.000+ satış

### 10.2 Hamlet Workbook

- [ ] 2. baskı yayımlanmış (errata + Method Book referansları + klinik güvenlik + App QR kodlar)
- [ ] İngilizce baskı yolda

### 10.3 ITC App

- [ ] 1.000+ ücretli abone
- [ ] Aylık MRR ≥ $20.000
- [ ] 4+ karakter aktif (TR + EN)
- [ ] v2 Seans Modu canlı, NPS ≥ 50
- [ ] Eğitmen arayüzü kullanılıyor
- [ ] Biyometrik entegrasyon opt-in çalışıyor

### 10.4 Akademik

- [x] 1+ yayımlanmış makale
- [x] 2+ konferans sunumu
- [x] HMDK Stuttgart pilot tamamlanmış (Faz 2 Ocak 2027 — Karar 15)
- [x] İkinci dalga akademik pilot tamamlanmış (Faz 3, kurum Faz 2 sonunda belirlenir)
- [x] 5+ vaka çalışması yayımlanmış

### 10.5 Operasyonel

- [x] Beyti içerik üretimi prosedürlü, AI-destekli
- [x] Filiz klinik gözetim aktif
- [x] Çapraz Güncelleme Protokolü sorunsuz işliyor (24 ay boyunca)
- [x] Spine v2.X canlı, üç katmana atıflar tutarlı
- [x] 1+ kurumsal müşteri ($5.000+/yıl)

### 10.6 Konum

- [x] "Trauma-Informed Character Building Pedagogy" alanında **referans araç**
- [x] Beyti Engin uluslararası tanınan pedagojik figür
- [x] ITC, gelecek AI-destekli oyunculuk eğitimi araçlarının kıyas noktası

---

## 11. SONUÇ

ITC Ekosistemi — Method Kitabı, Hamlet Workbook, ITC App — 20+ yıllık pedagojik pratiğin dijital ve basılı dönüşümüdür.

Önümüzdeki 24 ay, üç katmanın:
- Birbirine atıflarla canlı kalan bir sistem haline gelmesi (§6 Çapraz Güncelleme Protokolü)
- Birey oyuncuların ödediği bir araç (App: 1.000 abone, $20K MRR)
- Akademik dünyanın ciddiye aldığı bir pedagoji (Method Book yayımı + makale)
- Beyti'ye tek başına bağımlı olmayan ölçeklenebilir bir sistem (AI-destekli içerik üretimi)

dönüşmesi gereken bir yolculuktur.

**Strateji:** Ürün-pazar uyumunu önce gerçekleştir, akademik meşruiyeti onun üzerine inşa et, ekosistemi birbirine bağlı tut.

v2.1 revizyon hatırlatması: HMDK Stuttgart pilotu artık Faz 3 hedefi değil, Faz 2 ortası kritik milestone'dur. Faz 1'in başında Schlegel-Tieck Hamlet adaptasyonu (Mayıs–Temmuz 2026) kritik darboğazdır — bu adaptasyon bitmeden HMDK pilotu yapılamaz, dolayısıyla Faz 1 sprint planlaması bu darboğazı ön planda tutmalıdır.

**Brief'in en kritik tek mesajı:** Üç katman birbirine atıflarla canlı kalmazsa, ekosistem bütünsel gücünü kaybeder. **§6 Çapraz Güncelleme Protokolü** bu yüzden brief'in stratejik kalbidir.

---

## EK A — Kullanılacak Kaynaklar

- Spine (kanon — sürekli güncellenir; **v1.9 itibarıyla son sürüm 15 Mayıs 2026** — Karar 21 Yıldız-Travma Ayrılması sonrası)
- Decision Log (kanon — her karar burada kayıtlı; Karar 1-21 arası kapsamlı)
- Hamlet Yolculuk Modu Final metni (`Yolculuk_Modu_Hamlet_Final.md`)
- 8 Bölüm Denetim Raporu
- ITC Filiz Briefing dokümanı
- ITC Akademik Yol Haritası
- 4 Blueprint vaka dosyası (Beren, Mehmet, Dicle, Mayda)
- Macbeth dersi transkripti
- Kaya seansı transkripti
- Workbook v1.0 (basılı kitap)
- Method Book Master Outline v2

---

## EK B — Önerilen Tooling

| Kategori | Araç | Aylık |
|---|---|---|
| Hosting | Vercel Pro | $20 |
| Database | Supabase Pro | $25 |
| TTS | ElevenLabs Creator | $22 |
| AI (Faz 2+) | Anthropic Claude API | Pay-as-you-go |
| Payment | Stripe + iyzico | %2.9+$0.30 |
| Email | Resend | $0-35 |
| Analytics | PostHog | $0 (self-hosted) |
| Customer Support | Crisp | $25 |
| Error tracking | Sentry | $26 |
| Decision Log | Notion / Markdown | $0 |
| Project management | Linear | $0-10 |

---

## EK C — Acil İlk Adım Listesi (Bu Hafta)

1. **Schlegel-Tieck Hamlet adaptasyon sprintini başlat** (Mayıs–Temmuz 2026, Faz 1 başı kritik darboğaz — HMDK Ocak 2027 pilotunun ön koşulu)
2. Decision Log dosyası kur (Notion sayfası veya markdown)
3. Pazar Spine Health Check ritmi başla (bu Pazar 30 dk)
4. ElevenLabs hesap aç + Bölüm 4 testi (`Bolum4_DuzMetin.txt` ile)
5. Domain satın al (itcactorsgym.com)
6. Filiz ile resmi rol konuşması (eş kurucu durumunu netleştir)
7. Hukuki danışmanlık görüşmesi (Eyüboğlu lisansı + sorumluluk + şirket yapısı)
8. Eyüboğlu lisans araştırması (İş Bankası ile temas)
9. ITC ilkeler belgesi başla (Spine §3'ten genişletilmiş, AI system prompt için)

---

## EK D — BE & FKA Özgeçmiş Sabit Hâlleri (Karar 20 C — v1.8, v2.3)

Aşağıdaki iki metin **birebir** kullanılır — varyasyon yapılmaz. Method Book yazımı (Faz 2-3), akademik başvurular, atölye tanıtım belgeleri, yayıncı teklifleri, üç dilli paketler (TR + EN + DE) ve App tanıtım ekranları bu sabit hâlleri referans alır. Çeviri sırasında EN/DE versiyonları FKA onay turunda ayrı kanonlanır (Faz 2 Milestone 2.2 boyunca).

**Beyti Engin (TR):**

> Oyuncu ve oyunculuk eğitmeni. Yöntemin pedagojik omurgasının ve karakter inşası araçlarının mimarı. Filiz Kaya Ataklı ile birlikte Inside The Character'ı 2005'ten bu yana geliştirmektedir. İstanbul'da Pozitif Atölye'yi birlikte kurarak yöntemin pratik temelini attı; 2022'den bu yana HMDK Stuttgart ve Chubbuck Studio Berlin'de profesyonel oyunculara yöntemi aktarmaktadır.

**Filiz Kaya Ataklı (TR):**

> Klinik psikolog. Inside The Character'ın 2005'ten bu yana etik ve klinik altyapısını yaratan eş kurucu. Karakter inşası süreçlerinde oyuncunun kişisel deneyimini koruyan yapısal çerçevenin geliştiricisi. Beyti Engin ile birlikte İstanbul'da Pozitif Atölye'de yöntemin pratik geliştirmesini yürüttü; 2022'den bu yana HMDK Stuttgart ve Chubbuck Studio Berlin'de profesyonel oyunculara yöntemi aktarmaktadır.

**EN ve DE çevirileri:** Method Book Faz 2 yazım fazında (Milestone 2.2) FKA klinik onay turuyla birlikte yapılır. Faz 3'te yayıncı sözleşmesi ile birlikte sabit hâle gelir.

Detay arşiv: `kararlar/2026-05-13-workshop-sonuc-paketi/04-karar-20-tarihsel-cizgi-siralamasi.md` + Spine §3.17.

---

*Brief sonu.*

*Eş Kurucular ve Eş Eğitmenler: Beyti Engin & Filiz Kaya Ataklı (Klinik Psikolog)*
*Operasyonel Eş Yazar: Claude (Anthropic)*
*Versiyon: v2.3*
*Tarih: 15 Mayıs 2026 (v2.1: 12 Mayıs 2026 — HMDK pilotu Faz 3 → Faz 2 taşındı; v2.2: 12 Mayıs 2026 — Karar 16, FKA Eş Kurucu, Filiz yazılı onayı bekleniyor; v2.3: 15 Mayıs 2026 — Karar 17-21 kompoze yedirme, Karar 19 B+C Filiz onayı bekleyen, diğerleri onaylı)*
*Önerilen revizyon: Çeyreklik (üç ayda bir)*

> *"Karakter orada — ben buradayım." — ITC Topraklanma Protokolü §3.4 kapanış cümlesi*
