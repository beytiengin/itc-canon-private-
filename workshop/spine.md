# ITC Workshop — Ekosistem Spine

**v1.3** · 13 Mayıs 2026

**Eş Kurucular ve Eş Eğitmenler:** Beyti Engin & Filiz Kaya Ataklı (Klinik Psikolog)
**Operasyonel Eş Yazar:** Claude (Anthropic)

> Bu doküman, ITC ekosisteminin dördüncü katmanı olan atölye/eğitim mimarisinin Spine'ıdır. Method Book / Workbook / App / Workshop dört katmanlı ekosistemde Workshop'un iç ailesini — formatlar, hedef kitleler, içerik derinlikleri, format arası geçişler — yapılandırır. ITC Ekosistem Spine v1.7+ ile çapraz referanslıdır.

---

## Editör Notu (ana repoya yedirme, 12 Mayıs 2026)

Bu Workshop Spine v1.2 Workshop sohbetinde üretildi. Ana repoya yedirilirken iki tutarsızlık tespit edildi ve burada belgelenir:

### Karar Numarası Haritası — Workshop sohbeti ↔ Ana Decision Log

| Workshop sohbeti numarası | Ana Decision Log karşılığı | Durum |
|---|---|---|
| Karar 9 (Çift Üçlü: VAK × Giriş Kapıları) | Karar 9 ✓ aynı | Ana repoda yedirildi (Spine §3.10) |
| Karar 10 (Doğrular Çift Üçlü: Kaynak × Katman) | Karar 10 ✓ aynı | Ana repoda yedirildi (Spine §3.11) |
| **Karar 11 (HMDK Stuttgart Bağlam, 13 madde)** | Ana repoda Karar 11 = Transmisyon Mimarisi (BE × FKA Eş Eğitmenlik, Spine §3.13) — **farklı içerik**. **13 maddelik bağlam ana repoya Karar 17 olarak yedirildi (Spine v1.8, 13 Mayıs 2026).** | Workshop sohbeti Karar 11'in 13 maddesi ana Decision Log'a Karar 17 olarak yedirildi (13 Mayıs 2026). Tarih maddesi zaten Brief v2.1 Milestone 2.7'de hizalı (Karar 15). Açık [DOLDUR] alanları (3a/8a/12a + Katherina soyadı + DE çevirmen + saatlik tutar + temas anketi tasarımı) §8'de Karar 17 alt-maddeleri olarak takipte. |
| **Karar 12 (FKA Eş Kurucu ve Eş Eğitmen)** | Ana repoda **Karar 16** olarak yedirildi (Spine v1.7) | Ana Decision Log'da Karar 12 = Tek Karakter İlkesi (farklı içerik). FKA Eş Kurucu kararı ana repoda Karar 16 olarak yer aldı. **Filiz yazılı onayı bekleniyor — provisional.** |

Workshop spine içinde "Karar 11" ve "Karar 12" Workshop sohbetinin kendi sırasıdır; ana Decision Log'a atıf yapılırken Karar 16 (FKA Eş Kurucu) referansı kullanılır.

### Berlin Eylül 2026 Pilotu — Karar 18 Yedirildi

Bu Workshop Spine v1.2 Berlin Chubbuck Studio Eylül 2026 pilotunu A2'nin **ilk gerçek pilotu** olarak konumlandırmıştı (HMDK Ocak 2027 ikinci uygulama). Berlin pilotu ana repoya **Karar 18 olarak yedirildi** (13 Mayıs 2026, Spine v1.8): A2-Berlin-Variant'ın kurucu uygulaması; üç kademeli yapı (Auditor + Participant + Participant Advance) operasyonelleştirildi; «Inside The Character Berlin» marka kanonlandı («Character Design» emekliye); Karar 16 EN formülasyonu Chubbuck Studio Berlin sitesi güncellemesine eklendi. §9 Brief çelişkisi notu HMDK + Berlin yedirme satırlarıyla güncellendi. Açık [DOLDUR] alanları (spesifik tarih, EN Hamlet, paket gönderim tarihi, Advance ön koşul, ücretlendirme) §8 Karar 18 alt-maddeleri olarak takipte. Pilot paket iskeleti `workshop/kurumsal-pilot-paketleri/berlin-eylul-2026/` altında açıldı.

### MANIFEST.md Emekliye Ayrıldı

Bu Spine ana repoya yedirilirken `workshop/MANIFEST.md` (v1.6.0) `workshop/archive/MANIFEST-v1.6.0.md` olarak arşivlendi. Manifest "kanonik değil, derleme" iddiasındaydı; bu Workshop Spine ise "single source of truth" iddiasında (bkz. §11). İki belge aynı amaca paralel duruyordu; karışıklığı önlemek için Workshop'un canlı kanonu bu Spine olarak konumlandı.

### Ana Spine Sürüm Referansı

Doküman içindeki "Ekosistem Spine v1.7+" ve "Spine §3.10/§3.11" referansları ana Spine v1.6 (Karar 11-14 paketi) + v1.7 (Karar 16 FKA Eş Kurucu) sürümleriyle birlikte okunmalı. Referans değerleri yedirme sırasında metin içinde de güncellendi.

---

## v1.3'te Neler Değişti

v1.2 (12 Mayıs 2026) ana repoya yedirilirken §1 editör notunda iki açık iş işaretlenmişti: (1) HMDK 13 madde Karar 17 olarak yedirme; (2) Berlin Eylül 2026 pilotu Karar 18 olarak yedirme. v1.3 her ikisini de kapatır + Karar 19 (Yolculuk Süresi + Spektrum + Arşiv Etiği) operasyonel parametrelerini Workshop Spine'a yansıtır.

**Karar 17 (HMDK Stuttgart 13 madde bağlam kanonu)**
- Ana Decision Log'a Karar 17 olarak yedirildi (Spine v1.8)
- §1 editör notunda Karar Numarası Haritası tablosu güncellendi
- §8 HMDK başlığı "Karar 11 — alt-maddeler" → "Karar 17 — alt-maddeler" (3a DE çevirmen, 8a pre-work anket, 12a Katherina soyadı + Günther adaptasyonu aynen kalır)
- Pilot paket iskeleti `workshop/kurumsal-pilot-paketleri/hmdk-stuttgart-ocak-2027/` açıldı

**Karar 18 (Berlin Chubbuck Studio Eylül 2026 pilot + marka geçişi)**
- Ana Decision Log'a Karar 18 olarak yedirildi (Spine v1.8); A2-Berlin-Variant'ın kurucu uygulaması, ilk gerçek pilot
- §1 editör notunda "Berlin Eylül 2026 Pilotu — Açık Karar" → "Karar 18 Yedirildi"
- §8 Berlin bölümü başlığı "Karar 18 — alt-maddeler" (spesifik tarih, EN Hamlet, paket gönderim, Advance ön koşul, Advance ücret)
- Marka kanonu: «Inside The Character Berlin», eski «Character Design» emekliye
- Pilot paket iskeleti `workshop/kurumsal-pilot-paketleri/berlin-eylul-2026/` açıldı (10 alt-dosya planı, marka geçişi iletişim metinleri dahil)

**Karar 19 (Yolculuk Süresi 45-60 dk + Spektrum + Ses Kayıtları Arşiv Etiği)**
- §4 A2 ortak omurga "Yolculuk" satırında süre referansları 45-60 dk aralığına revize edildi (Karar 19 A — Berlin tarihsel kayıt kanonu, ana Spine §3.16)
- §2 Tasarım İlkeleri'ne yeni madde: "Karakter spektrumu sınırı yok (Karar 19 B)" — etik filtre §3.3 üzerinden işler, karakter kimliği üzerinden değil; tarihsel karanlık figürler çalışılabilir (**Filiz klinik onayı bekleniyor**)
- §8 Eğitmen ve klinik altyapı listesine yeni madde: "Ses kayıtları arşivleme onay formu şablonu — `workshop/katilimci-materyalleri/katilimci-onay-formu.md` (Karar 19 C uygulama; **Filiz klinik onayı bekleniyor**)"
- Tarihsel kayıt arşivi iskeleti `workshop/karakter-dosyalari/tarihsel-kayit-referanslari/` açıldı (Heidrich, Eva Braun, Bianca/Sofia + Berlin pilotu yeni kayıtları için)

**§9 Brief v2 çelişkisi notu** HMDK + Berlin yedirme satırlarıyla güncellendi. **Brief v2 → v2.3 revizyonu hâlâ açık** — Karar 17 detay + Karar 18 yeni Milestone 1.8 + Karar 20 (ana Spine §3.17) önsöz §1 + sıralama denetimi bütünleşik tek paket olarak sonraki turda yedirilir.

**Karar 20 dolaylı:** Ana Spine'da §3.17 yeni alt-bölüm olarak yedirildi (Yöntem Tarihsel Çizgisi). Workshop Spine §1 editör notu, §11 footer ve diğer eş kurucu referansları zaten BE → FKA sıralama uyumluluğunda — Karar 20 sıralama kuralı ek değişiklik gerektirmedi.

---

## v1.2'de Neler Değişti

v1.1 (8 Mayıs 2026) Ekosistem Spine v1.3 sonrasında yazılmıştı. v1.2 dört önemli karar dalgasını içselleştirir:

**Karar 9 (8 Mayıs, Ekosistem Spine v1.4) — Çift Üçlü İlkesi: VAK × Giriş Kapıları**
- VAK üçlüsü (Modül I, App-only) ile Giriş Kapıları üçlüsü (Modül II, kâğıt-kalem) iki ayrı katmandır
- Karışım pedagojik ve etik hatadır
- 3×3 Matris (Matris 1) — A2 ve B1 atölyelerinde öğretilir
- Sezgisel dördüncü kanal VAK'ın yanında; Giriş Kapıları üçlüsü kapalı

**Karar 10 (12 Mayıs, Ekosistem Spine v1.5) — Doğrular Çift Üçlü: Kaynak × Katman**
- Kaynak Üçlüsü (Metin içi · Süreç içi · Yaratımsal) — doğru nereden geliyor
- Katman Üçlüsü (Metinsel · Dramaturjik · Zihinsel Sabit) — doğru neye dair
- 3×3 Matris (Matris 2) — Modül II Doğrular bloğunda
- Matris 1 ve Matris 2 ayrı eksenlerde; karışmamalıdır

**Karar 11 (12 Mayıs) — HMDK Stuttgart Bağlam (13 madde onaylı)**
- 25-29 Ocak 2027 tarih kesin
- 12 öğrenci · Schauspiel bölümü · Hamlet (Frank Günther DE çevirisi)
- BE TR → anlık DE çeviri · FKA bazen EN
- FKA 5 gün fiziksel Stuttgart'ta
- Üretim takvimi 8.5 aya sıkıştırıldı

**Karar 12 (12 Mayıs) — FKA Eş Kurucu ve Eş Eğitmen Statüsü Kanon**
- Tüm dokümantasyonda "Eş Kurucu ve Eş Eğitmen" formülasyonu
- "× " yerine "&" işareti
- Eski "klinik gözetim" formülasyonu emekliye

**Format ailesi:** A2 dört varyantta (base 8 hafta · intensive 5 gün · short 4 hafta · extended 12 hafta) korundu; üretim sırası **Berlin Eylül 2026** (gerçek pilot) + **HMDK Ocak 2027** (ikinci uygulama) sıralamasıyla yeniden hizalandı. A2-Berlin-Variant alt-formatı eklendi.

---

## 0 · Bu Doküman

Bu belge, ITC ekosisteminin dördüncü katmanı olan atölye/eğitim mimarisinin Spine'ıdır. Method Book / Workbook / App / Workshop dört katmanlı ekosistemde Workshop'un iç ailesini yapılandırır.

ITC Ekosistem Spine v1.7+ §1 (Ekosistem Haritası), §3 (Sabit ITC İlkeleri) ve §4 (Çapraz Geçişler) ile çapraz referanslıdır. O Spine yöntemin değişmez omurgasını, bu Spine atölye katmanının iç çeşitliliğini tanımlar.

Decision Log v1+ ile birlikte okunur — Decision Log Workshop kararlarının tarihçesidir, bu Spine kararların güncel sentezidir.

---

## 1 · Atölye Katmanının Konumu

Method Book bilgi taşır (akademik otorite). Workbook tek bir karaktere derinleşmiş uygulama sunar. App günlük dijital pratik verir. Workshop, ekosistemin canlı transmisyon katmanıdır — eğitmen-oyuncu temaslı, beden-beden öğrenmenin gerçekleştiği yer.

Workshop tek bir format değil — bir aile. Bir oyuncu yöntemle tanışmak için 3 saatlik bir tanıtıma gelebilir; profesyonel rolünü hazırlamak için 5 günlük intensive'a gelebilir; akademik dönem boyunca 8 haftalık programa katılabilir; ya da kendisi eğitmen olmak için iki bloklu bir train-the-trainer'a gelebilir. Aynı omurga, farklı dozlarda.

Workshop, Method Book'un D bölümünden (Eğitmen Rehberliği) türeyen bir uygulama katmanıdır. D bölümü kavramsal, Workshop operasyonel — eğitmenin elinde fiilen kullandığı program kiti.

---

## 2 · Tasarım İlkeleri (her formatta sabit)

Hangi format olursa olsun aşağıdaki ilkeler değişmez. Bunlar ITC Ekosistem Spine v1.7+ §3'teki sabit ilkelerin atölye karşılığıdır:

- **Spine'a sadakat:** Altı Kabul, Üç Giriş Kapısı, Travma Matrisi 8×4 (Karar 2), Yıldız Eşleşme her formatta omurgadır. Atölye omurgaya aykırı bir şey önerirse, hata atölyededir.

- **Etik koruma gömülü:** Substitution yasağı ("Sahip değil — misafir."), Yıldız Profil eşleşme matrisi ve 6 adımlık topraklanma protokolü her atölyenin tasarımında vazgeçilmezdir. Format kısaldıkça etik koruma değil, içerik kısaltılır.

- **Çift Üçlü kanonu:** İki ayrı 3×3 matris atölyede öğretilir ve karışmamalıdır. Matris 1 (VAK × Giriş Kapıları, Karar 9) ve Matris 2 (Kaynak × Katman, Karar 10). Bkz. §5.

- **Dijital Araç Sınırı İlkesi (Karar 7):** Modül I testleri (VAK/MBTI/Yıldız) atölyede kâğıt üzerinde çözülmez — App'ten gelir, atölyede yorumlanır. Egzersizler, soru havuzları ve defterler atölye materyalleri olarak kâğıt formatında.

- **FKA eş eğitmen pratiği (Karar 12):** Filiz Kaya Ataklı eş kurucu ve eş eğitmendir. A2 ve B1 atölyeleri her iki kurucunun fiziksel mevcudiyetiyle verilir; diğer formatlarda eş eğitmen rolü açık karar (§8).

- **Karakter spektrumu sınırı yok (Karar 19 B):** ITC karakter konusunda sınır koymaz; etik filtre Spine §3.2 Travma Matrisi (8×4) ve §3.3 Sahne-Level Etik Uyarı üzerinden işler, karakter kimliği üzerinden değil. Tarihsel karanlık figürler (Eva Braun, Heidrich gibi) ITC çerçevesinde çalışılabilir; etik koruma **sahne içeriğiyle** (travma yoğunluğu ve kategorisi) belirlenir, oyuncu profili üzerinden değil. (v1.9 — Karar 21 sonrası: eski "psikolojik puan eşiği" gate mekanizması kaldırıldı; yoğunluk 2-3 sahneler sonrası §3.4 Topraklanma Protokolü otomatik tetiklenir.) **Filiz klinik onayı bekleniyor — provisional.**

- **Kendi başına değer testi:** Bir atölye tek başına anlamlı eğitim verir mi? Vermiyorsa kendi başına satılmaz; daha geniş bir formatın parçası olarak konumlanır.

- **Prototip-önce:** Bir format tam kurulmadan, valide edilmeden türevleri açılmaz. **Berlin Chubbuck Studio Eylül 2026** A2-intensive'in ilk gerçek pilotudur; **HMDK Stuttgart 25-29 Ocak 2027** ikinci uygulama. A2-base (8 hafta) bu iki pilottan sonra konsolide edilir.

- **VAK ve Giriş Kapısı varyantları:** Her atölye, oyuncuların farklı kanallarına göre alternatif egzersizler içerir. Modül II atölyelerinde her adım için üç kapıdan giriş seçeneği sunulur. "Herkese aynı yol" ITC dilinde yanlıştır.

- **Peer kollaboratör çerçevesi:** Uluslararası bağlamda atölyeler kurumsal onay arayan değil, metodolojist olarak konumlanır. Bu konumlandırma her formatın iletişim materyaline sızar.

---

## 3 · Atölye Aileleri

Atölye katmanı beş aileye ayrılır. Her aile farklı bir soruya cevap verir:

| Aile | Soru | Konum |
|---|---|---|
| A · Temel | ITC nedir, nasıl tadılır? | Yöntemle ilk temas + amiral gemisi |
| B · İleri | Yöntemi mezunluk sonrası nasıl derinleştirim? | A2 mezunlarına ikinci patika |
| C · Tematik Derinleşme | Yöntemin bir kavramını kendi başına ne kadar kazabilirim? | ITC'nin tek bir parçasında uzmanlaşma |
| D · İhtisas | Bu yöntem benim mesleğime nasıl uyar? | Eğitmen, yönetmen, audition, klinik |
| E · Meta | Yöntemi nasıl başkalarına aktarırım? | Ekosistem büyümesi |

---

## 4 · Format Envanteri

### A · Temel

#### A1 · Tanıtım Atölyesi (3-4 saat)
- **Hedef:** ITC'yi ilk kez duyan oyuncu, festival/davetli gruplar, açılış etkinlikleri
- **İçerik:** İki Kabul (4 ve 5) + bir Giriş Kapısı demosu + Hamlet üzerinden kısa grup egzersizi + Q&A
- **Yolculuk:** Yok. Sadece grup demoları.
- **Çıktı:** ITC'nin "tadı" — devam edecekler A2'ye yönlendirilir
- **Pazarlama notu:** Ücretsiz/sembolik fiyat; ekosistemin huni girişi

#### A2 · Tam Modül Atölyesi (FORMAT AİLESİ — amiral gemisi)

A2 dört varyantlı bir ailedir. Hammadde 8 haftalık Detaylı Eğitim Programı; oradan türetilir.

| Varyant | Süre | Hedef bağlam | Durum |
|---|---|---|---|
| **A2-intensive** | 5 gün ardışık | Yoğun pilot, kurumsal misafir öğretmenlik | **İkinci uygulama: HMDK Stuttgart 25-29 Ocak 2027** |
| **A2-Berlin-Variant** | 4 gün (Auditor + Participant + Advance) | Profesyonel oyuncu stüdyosu — Berlin Chubbuck modeli | **İlk gerçek pilot: Eylül 2026** |
| **A2-base** | 8 hafta (haftalık seans) | Akademik dönem programı | Pilot retrospektifleri sonrası konsolide edilecek (Şubat-Mayıs 2027) |
| **A2-short** | 4 hafta | Kısa dönem programı, profesyonel oyuncu | A2-base konsolide olduktan sonra türetilir |
| **A2-extended** | 12 hafta | Uzun dönem akademik program | A2-base genişletmesi, en sona |

**A2 ortak omurga (her varyantta sabit):**

- **Hedef:** Profesyonel oyuncu veya akademik son sınıf/yüksek lisans (8-14 kişilik kohort, varyanta göre)
- **İçerik:** Tüm teorik altyapı + Modül I kalibrasyon + Modül II Karakter Sayfası Mimarisi + Modül III Akış & Topraklanma & Sahneleme
- **Karakter:** Tek karakter — Hamlet (varsayılan) veya Macbeth. Kohort ortak alan paylaşır.
- **Pedagojik omurga:** 9 adım × 3 Giriş Kapısı matrisi (§6). 8 haftalık formatta her hafta bir adım; 5 günlük intensive'de adımlar günlere dağılır; 4 günlük Berlin formatında sıkıştırılmış dağıtım.
- **Çift Üçlü kanonu öğretimi:** Matris 1 (VAK × Giriş Kapıları) Modül I bloğunda; Matris 2 (Kaynak × Katman) Modül II Doğrular bloğunda. İkisi ayrı eksenler — kademeli öğretim (Kaynak Üçlüsü önce, Katman Üçlüsü sonra).
- **Yolculuk:** Her oyuncuya bire bir Modül III yolculuğu. **Sahnede grup tanıklığında**, çift geri bildirim mimarisiyle (önce grup, oyuncu dinlenirken; sonra oyuncu kendi deneyimini paylaşır). **Yolculuk süresi 45-60 dk aralığında** (Karar 19 A — Berlin tarihsel kayıt kanonu, ana Spine §3.16). 8 haftalık formatta haftalık seans bu yolculuğa ek teorik blok içerir; 5 günlük intensive'de günlük slot içinde 60 dk; A2-Berlin-Variant'ta 45-60 dk.
- **Modül I uygulaması:** VAK + MBTI + Yıldız Oyuncu testleri pre-work olarak App'te (Dijital Araç Sınırı İlkesi — Karar 7).
- **Eş eğitmenlik:** Beyti Engin & Filiz Kaya Ataklı (her iki eş kurucu fiziksel mevcut — Karar 12). Teorik bölümler paylaşımlı, Modül II BE önder/FKA eşlikçi, Modül III yolculuklar BE solo (FKA sahnede klinik on-call), etik blok FKA imzalı.

#### A2-Berlin-Variant — Detay (Eylül 2026 için)

Berlin Chubbuck Studio'nun tarihsel **Auditor + Participant** kademeli yapısına eklenen **Advance** kademesiyle:

- **4 gün**, profesyonel oyuncu kohortu
- **Üç kademeli katılım:**
  - **Auditor** (20-24 kişi) — atölye + diğerlerinin yolculuklarını izleyici
  - **Participant** (8 kişi) — tam katılım + 1 Hamlet yolculuğu sahnede
  - **Participant Advance** (4-6 kişi) — Participant artı + kendi karakter mini-journey (B1-bridge entegre)
- **Karakter:** Hamlet (ortak alan); Advance kohortu için kendi karakter (mini-journey)
- **Dil:** Türkçe + İngilizce + Almanca çevirmen (Berlin tarihsel modeli)
- Detaylı yapı: Berlin Atölye Paketi v1.0'da (üretilecek)

### B · İleri

#### B1 · Kendi Karakterin (5 gün veya 4 hafta)
- **Önkoşul:** A2 (herhangi bir varyant) tamamlanmış
- **Hedef:** Mezun olmuş oyuncu, prova öncesi prep, rolüne hazırlanan profesyonel
- **İçerik:** Her oyuncu kendi rolüyle gelir; ITC mimarisi her birinin karakterine ayrı ayrı uygulanır. 9 adım × 3 Kapı matrisi her oyuncunun kendi metni üzerinden. Teori yeniden anlatılmaz; doğrudan uygulamaya gidilir.
- **Yolculuk:** Bireyselleştirilmiş — her oyuncuya kendi karakteri için özel yolculuk tasarımı. Sahnede grup tanıklığında.

#### B1-bridge (A2'ye ekli kısa varyant)
A2-Berlin-Variant'ın Participant Advance kademesinde uygulanır. A2'nin son 1-2 gününe eklenen advance modül.

#### B2 · Repertuar Geçişi (3 gün)
- **Önkoşul:** A2 + B1 tamamlanmış
- **Hedef:** İki/üç rol arasında geçiş yapan oyuncu (rep tiyatrosu, paralel dizi/film)
- **İçerik:** Aynı oyuncuda iki farklı karakter sayfasının paralel inşası, geçiş protokolleri

### C · Tematik Derinleşme

#### C1 · Boşluklar Atölyesi (2-3 gün)
- **Konu:** ITC'nin imza pratiği — karakterin yazılmamış anları
- **İçerik:** Yaratıcı boşluk teorisi · 8-10 boşluk egzersizi · grup paylaşımı

#### C2 · Karakter Sayfası Mimarisi (3 gün)
- **Konu:** Doğrular (Çift Üçlü — Matris 2) → Timeline → Yazarın Çerçevesi → Senin Çerçeven kademeli derinleşmesi
- **İçerik:** Workbook'un tam yapısı bu atölyede öğretilir

#### C3 · Akış & Performans Atölyesi (3 gün)
- **Konu:** Modül III'ün kendi başına atölyesi — sahnede akışta kalmak
- **İçerik:** Akış teorisi (Csikszentmihalyi) · zihinsel canlandırma · prova öncesi rutin · topraklanma · sahne çıkış protokolü
- **Pazar notu:** A2'den sonra ikinci en kolay satılan format adayı

#### C4 · Kararlar Odası (2 gün)
- **Konu:** Karakterin karar anlarına yoğunlaşma — üç sesli iç koridor egzersizi

### D · İhtisas

#### D1 · Etik & Klinik Güvenlik (3 gün) — FKA imzalı
- **Hedef:** Eğitmen, koç, oyunculuk öğretmeni, yönetmen yardımcısı
- **İçerik:** Travma matrisi 8×4 derinleştirme · Yıldız eşleşme klinik bakış · topraklanma protokolü ileri uygulama · Tip C bölüm yönetimi · helpline/disclaimer/öz-tarama altyapısı
- **FKA varlığı:** Bu format FKA'nın özel olduğu yer — eş kurucu klinik çerçevesinin yönteme nasıl gömülü olduğunun transmisyonu
- **Çıktı:** Etik gözetim sertifikasının ön koşulu (E1 için zorunlu modül)

#### D2 · Yönetmenler için ITC (3 gün)
- **Hedef:** Tiyatro / dizi / film yönetmenleri
- **İçerik:** Oyuncuyu ITC dilinden okumak · prova ekonomisi · kısa zamanda derin sonuç

#### D3 · Audition / Cold Reading Lab (2 gün)
- **Hedef:** Audition aşamasındaki oyuncu, ajans temsiliyetinde profesyonel
- **İçerik:** ITC'nin sıkıştırılmış uygulanışı — bir gece, bir saat, on dakika

### E · Meta

#### E1 · Eğitmen Yetiştirme — Train-the-Trainer (10 gün, 5+5)
- **Önkoşul:** A2 + B1 + D1 tamamlanmış (D1 ön koşulu açık karar)
- **Hedef:** ITC adıyla atölye verecek eğitmen adayı
- **İçerik:** Yöntemin pedagojik aktarımı · her modülü öğretme egzersizleri · etik gözetim · sertifikasyon · iki blok arası sahada gözlemli pratik (~2-3 ay)

#### E2 · Akademik Dönem Programı (yarıyıl)
- **Hedef:** Konservatuar, üniversite tiyatro bölümü
- **İçerik:** A2-extended (12 hafta) ile örtüşür ya da paralel kullanılır

---

## 5 · Çift Üçlü Kanonu (atölyede öğretim)

ITC Ekosistem Spine v1.4 (Karar 9) ve v1.5 (Karar 10) ile kanon olan iki ayrı 3×3 matris atölyede öğretilir. Karışmamalıdır.

### 5.1 · Matris 1: VAK × Giriş Kapıları (Spine §3.10, Karar 9)

**Sorduğu:** Oyuncu nasıl çalışır?
**Yeri:** Modül I (kalibrasyon, App pre-work) + Modül II (uygulama)

|  | Bilişsel Kapı | Bedensel Kapı | Duygusal Kapı |
|---|---|---|---|
| **Görsel** | Sahne diyagramı · zihin haritası · timeline çizimi | Karakterin silueti · postür eskizi · ayna çalışması | Yüz/beden ifadesi okuma · karakter portresi etüdü |
| **İşitsel** | Replik analizi · tonlama yapısı · monolog parçalama | Nefes-ses ritmi · vokal warm-up · prosodi | Ses kalitesi-duygu eşleştirme · iç ses dinleme |
| **Kinestetik** | Yapıyı bedenle deneyimleme · blocking provası | Hareket etüdü · somatik bedensel yoklama · yürüyüş | Karakterin bedensel duygusu · imgesel temas |

"Kinestetik × Duygusal" hücresinde **karakterin** bedensel duygusu çalışılır, oyuncunun kendi anısı değil — substitution yasağının matris üzerinde işareti.

**Sezgisel dördüncü kanal** VAK'ın yanında (algoritmaya girmez, gözlemsel). Giriş Kapıları üçlüsü **kapalıdır** — dördüncü kapı yoktur.

### 5.2 · Matris 2: Kaynak × Katman (Spine §3.11, Karar 10)

**Sorduğu:** Doğru neye benziyor?
**Yeri:** Modül II Doğrular bloğu

|  | Metinsel | Dramaturjik | Zihinsel Sabit |
|---|---|---|---|
| **Metin içi · doğrudan** | Hamlet prens; Wittenberg mektubu | Cenaze ve düğün arasında 2 ay | "Bana düşmez olaydı dünyayı düzeltmek" |
| **Süreç içi · örtük** | Polonius'un kontrol dili | Saray Wittenberg'i geride bıraktı | Hamlet için intikam ahlaken muğlak |
| **Yaratımsal · sahnelemeye bağlı** | "Olmak ya da olmamak"ın yeri | Modern dönem mi, Rönesans mı? | Hamlet ateist mi, dindar mı? |

Kaynak Üçlüsü "doğru nereden geliyor" (tartışma alanı), Katman Üçlüsü "doğru neye dair" (çalışma yeri) sorusunu cevaplar.

### 5.3 · İki matrisin atölyede öğretim sırası

**Kademeli öğretim** (Spine v1.5 Karar 10'dan):

- **Başlangıç** (A2 ilk modülleri, D1): Matris 1 (VAK × Giriş Kapıları) tek başına — Modül I kalibrasyon bloğunda
- **Orta** (A2 Modül II Doğrular bloğu, C2): Kaynak Üçlüsü tek başına çalışılır
- **İleri** (A2 sonu, B1, C2 derinleşmesi): Katman Üçlüsü tanıtılır, Kaynak ile ilişkisi açıklanır, Matris 2 bütünüyle uygulanır

İki matris aynı anda öğretilmez — kademeli sentez son güne bırakılır.

---

## 6 · A2 Pedagojik Omurga: 9 Adım × 3 Giriş Kapısı

A2 ailesinin iskeleti 9 adım × 3 Giriş Kapısı haritasıdır (Decision Log 8 Mayıs 2026 Karar 8). Her adımda kapılardan biri (ya da birden fazlası) baskındır; her kapı için ayrı soru seti bulunur.

| Adım | Tanım | Baskın Kapı(lar) | Notu |
|---|---|---|---|
| 1. Karakteri Tanıştırma | Heyecanlı anlatım — "karşılaştığım inanılmaz biri" | Bilişsel + Duygusal | Açılış adımı, grup paylaşımı |
| 2. Karakteri Tanıma | Detaylı analitik tanıma — soru havuzu | Üç Kapı | 2016 soru kataloğunun ana yeri |
| 3. Geçmişten Anlık Görüntüler | Karakterin kritik anılarına bedensel iz | Duygusal + Bedensel | Anılar üzerinden somatik iz |
| 4. Mekânların Özü | Karakterin önemli mekânları | Bedensel | Oda, nesne, hareket |
| 5. Çekirdek Motivasyon ve Birincil Duygular | Karakterin temel sürücüleri | Duygusal + Bilişsel | Pattern analizi |
| 6. Karakterin Fiziksel Görünümü | Postür, jest, ritim | Bedensel | Beden organizasyonu |
| 7. Çekirdek Düşünceler, İnançlar, Görüşler | Karakterin zihinsel sabitleri | Bilişsel | Matris 2 Katman Üçlüsü'nün uygulama yeri |
| 8. Kim Bu Kişi? (1 sayfalık monolog) | Karakterin sentezi — birinci tekil | Üç Kapı | Sentez adımı |
| 9. Karakteri Günlük Hayatta Deneyimleme | Yarım gün karakter olarak yaşama | Bedensel + Duygusal | Yaşama egzersizi |

### A2-intensive (5 gün) adım dağıtımı

| Gün | Adımlar | Modül | Yolculuk |
|---|---|---|---|
| 1 | Adım 1 + Adım 2 başlangıç | Modül I + Modül II giriş | 0-2 (Yıldız ≥5 pilot) |
| 2 | Adım 2 + Adım 3 | Modül II — A | 3 |
| 3 | Adım 4 + Adım 5 | Modül II — B | 3 |
| 4 | Adım 6 + Adım 7 + Modül III teori | Modül II — C + Modül III | 3 |
| 5 | Adım 8 + Adım 9 (kısaltılmış) + sahneleme | Modül III + bütünleşme | 3-1 |

### A2-Berlin-Variant (4 gün) adım dağıtımı

| Gün | Adımlar | Modül | Yolculuk |
|---|---|---|---|
| 1 | Adım 1-2 + Modül I yorumlama | Modül I + Modül II giriş | 0 (sadece tanışma) |
| 2 | Adım 3-5 yoğunlaştırılmış | Modül II — A+B birleştirilmiş | 2-3 başlangıç |
| 3 | Adım 6-7 + Modül III teori | Modül II — C + Modül III | 3-4 |
| 4 | Adım 8 + Advance B1-bridge + bütünleşme | Modül III + B1 mini | 3-4 + Advance B1 |

A2-base (8 hafta) dağıtımı: 1 hafta = 1 adım, son hafta sentez.

---

## 7 · Patika Haritaları

Her oyuncu/profesyonel ITC ekosisteminde farklı bir patika izler. Şablon:

| Profil | Patika | Süre |
|---|---|---|
| Profesyonel oyuncu | A1 → A2 (intensive veya base) → B1 → C-aileden seçim | ~6 ay-2 yıl |
| Profesyonel oyuncu (Berlin) | A2-Berlin-Variant (Participant Advance) → B1 → C-ailesi | ~1 yıl |
| Eğitmen adayı | A2 → B1 → D1 → E1 | ~1-2 yıl |
| Yönetmen | A1 → D2 (gerekirse A2 demo bölümleri) | Birkaç hafta-3 ay |
| Akademik kurum (kohort olarak) | A2-base 8 hafta veya A2-extended 12 hafta | Yarıyıl/yıl |
| Akademik kurum (intensive) | A2-intensive 5 gün — HMDK Stuttgart modeli | 1 hafta |
| Profesyonel stüdyo (Berlin modeli) | A2-Berlin-Variant 4 gün — Chubbuck modeli | 4 gün |
| Audition oyuncusu | A1 → D3 (zaman varsa A2) | Birkaç hafta |

---

## 8 · Açık Kararlar

Bu kararlar henüz verilmedi. Çözüldüğünde Spine güncellenir ve Decision Log'a kayıt düşer.

### Format ve sıralama

- A2-base (8 hafta) konsolide edilmesi: Berlin Eylül 2026 + HMDK Ocak 2027 pilot retrospektifleri sonrası [BE & FKA Şubat-Mayıs 2027]
- A2-short (4 hafta) ve A2-extended (12 hafta) ne zaman türetilir? [BE pazar kararı]
- A2-Berlin-Variant: Berlin pilotundan sonra standart bir varyant mı olur, yoksa Chubbuck'a özel kalır mı? [BE + Berlin]
- A1 Tanıtım ücretlendirme modeli [BE pazar kararı]

### Eğitmen ve klinik altyapı

- E1 Train-the-Trainer için D1 zorunlu ön koşul mu? [BE & FKA]
- A2 dışındaki formatlarda FKA fiziksel mevcudiyeti — modül başına mı, sürekli mi? [FKA]
- Workbook 2. baskı klinik güvenlik eklemelerinin Workshop materyallerine yansıması [FKA]
- Karar 12 (FKA Eş Kurucu) yazılı onayı bekleniyor [FKA]
- Ses kayıtları arşivleme onay formu şablonu — `workshop/katilimci-materyalleri/katilimci-onay-formu.md` (Karar 19 C uygulama; **Filiz klinik onayı bekleniyor**)
- Karakter spektrumu sınırı yok kanonu (Karar 19 B) — Filiz klinik onayı bekleniyor [FKA]

### Konumlandırma ve marka

- "ITC Workshops" alt-markası ayrı bir kimlik mi? (Spine v1.5 §5 açık karar)
- Format isimleri TR vs EN/DE — bağlama göre seçim
- Atölye + App bundle modeli [BE pazarlama]
- Berlin'de eski "Character Design" markasının emekliye ayrılması — Chubbuck Studio sitesinin güncellenmesi gerek

### Operasyonel

- B2B (kurumsal paket) vs B2C (bireysel kayıt) [BE iş geliştirme]
- Yardımcı fasilitatör rolü: paralel iş facilitate edilecekse FKA mı, ayrı asistan mı? [BE & FKA]
- Itc_workshop.pdf eski tasarım: retire / referans / v0 taslak konumu

### HMDK Stuttgart 25-29 Ocak 2027 (Karar 17 — alt-maddeler)

- **3a.** Anlık DE çevirmeni kim olacak? [HMDK koordinasyon]
- **8a.** Pre-work önceden ITC temas anketi tasarımı [BE + Claude]
- **12a.** Prof. Katherina'nın soyadı [HMDK koordinasyon]
- Günther çevirisi sıkıştırılmış 4 sahne adaptasyonu — kim yazacak? [BE]

### Berlin Chubbuck Studio Eylül 2026 (Karar 18 — alt-maddeler)

- Spesifik tarih (Eylül başı/ortası/sonu)? [Berlin koordinasyon]
- A2-Berlin-Variant Participant Advance ücretlendirmesi (Auditor €230-250, Participant €550-650 önerisi sabit; Advance Chubbuck onayı, Participant'tan ~€150-200 üstü öneri)
- Hamlet metin EN versiyonu (Workbook EN hazır mı, ne kadar)?
- Berlin paketi gönderim tarihi: Mayıs sonu hedef [DOLDUR: gerçek deadline]
- Participant Advance ön koşul tanımı (A2 mezunu zorunlu mu, profesyonel deneyim eşdeğer mi) — §3.14 B1 istisnasıyla tutarlılık

---

## 9 · Üretim Sırası

Brifin "prototip-önce" ilkesine göre formatlar bir sırada kurulur. v1.2'de sıra Berlin Eylül 2026 ve HMDK Ocak 2027 takvimlerine göre yeniden hizalandı:

| Sıra | Format | Hedef tarih | Gerekçe |
|---|---|---|---|
| 1 | A2-Berlin-Variant (4 gün, Hamlet) | **Eylül 2026** | **İlk gerçek pilot — Berlin Chubbuck Studio** |
| 2 | A2-intensive (5 gün, Hamlet) | **Ocak 2027** | HMDK Stuttgart — ikinci uygulama, akademik kurumsal pilot |
| 3 | A2-base (8 hafta) konsolide | Şubat-Mayıs 2027 | İki pilot retrospektifi sonrası 8 haftalık programın finalize edilmesi |
| 4 | C3 · Akış & Performans (3 gün) | Yaz 2027 | Pazarda en kolay satılan format |
| 5 | B1 · Kendi Karakterin (5 gün veya 4 hafta) | Sonbahar 2027 | A2 mezunlarına ikinci patika |
| 6 | D1 · Etik & Klinik Güvenlik (3 gün) | Sonbahar 2027 | FKA görünürlüğünü kurar. E1 ön koşulu |
| 7 | A1 · Tanıtım (3-4 saat) | Yıl içi | Pazarlama aracı + huni girişi |
| 8 | E1 · Train-the-Trainer (10 gün) | 2028 | Ekosistem büyümesi için son aşama |
| 9+ | C1, C2, C4, B2, D2, D3, A2-short, A2-extended | Talebe göre | Sırayla açılır |

**Brief v2 çelişkisi notu (güncel durum — 13 Mayıs 2026 ana repo yedirmeleri sonrası):** HMDK tarih hizalaması yapıldı — Brief v2.1 ile HMDK Stuttgart pilotu Faz 3 Milestone 3.1'den çıkarılıp Faz 2 Milestone 2.7'ye (25-29 Ocak 2027) taşındı. Brief v2.2 ile Karar 16 (FKA Eş Kurucu) ekosistem geneline yansıtıldı. **HMDK 13 madde bağlam kanonu ana Decision Log'a Karar 17 olarak yedirildi (Spine v1.8, 13 Mayıs 2026).** **Berlin Eylül 2026 pilotu ana Decision Log'a Karar 18 olarak yedirildi (Spine v1.8, 13 Mayıs 2026); marka geçişi («Character Design» → «Inside The Character Berlin») kanonlandı.** **Hâlâ yapılması gereken:** Brief v2 → v2.3 revizyonu bekliyor — HMDK 13 madde detay yazımı Brief'e + Berlin yeni Milestone 1.8 + Karar 20 önsöz §1 yöntem tarihçesi (ana Spine §3.17) + tüm sıralama denetimi (her geçişte BE → FKA). Bütünleşik tek paket olarak sonraki turda yedirilir.

---

## 10 · Güncelleme Protokolü

Bu doküman canlı belge. Her yeni format prototiplendiğinde, valide edildiğinde ya da iptal edildiğinde versiyon atlar. ITC Ekosistem Spine v1.7+ §5 ile çapraz referanslıdır.

Versiyonlama: Aile yapısı değişirse major (v2.0). Format eklenir/çıkarılırsa minor (v1.1, v1.2). Açık karar çözülürse patch notu eklenir.

### Sürüm Geçmişi

- **v1.0** — 8 Mayıs 2026 (sabah) — İlk sürüm. Ekosistem Spine v1.1'e referansla. 5 aile + 13 format envanteri. A2 = 5 gün/Hamlet/12 oyuncu/BE+FKA tek format konumunda.
- **v1.1** — 8 Mayıs 2026 (akşam) — Ekosistem Spine v1.3'ün getirdiği 8 stratejik kararla yeniden hizalandı. A2 format ailesi (base, intensive, short, extended). 9 adım × 3 Giriş Kapısı matrisi A2 omurgası. HMDK Stuttgart 25-29 Ocak 2027 üretim sırasının çapası. Travma matrisi 8×4 düzeltmesi. Dijital Araç Sınırı İlkesi.
- **v1.2** — 12 Mayıs 2026 — Dört karar dalgası entegre: (1) **Karar 9-10 (Çift Üçlü kanonu)** — §5'te iki matris atölyede öğretim yeri tanımlandı; (2) **Karar 11 (HMDK Bağlam)** — 13 madde onaylı, üretim sırası HMDK Ocak 2027 hizalı; (3) **Karar 12 (FKA Eş Kurucu)** — başlıkta ve §2'de yeni formülasyon, ünvanın tüm dokümana yansıması; (4) **Berlin Chubbuck Studio Eylül 2026** A2'nin ilk gerçek pilotu olarak konumlandı; **A2-Berlin-Variant** alt-formatı eklendi (Auditor + Participant + Advance üç kademe). Üretim sırası §9'da yeniden hizalandı.
- **v1.3** — 13 Mayıs 2026 — **Workshop Sonuç Paketi: 3 karar entegre** (Karar 20 ana Spine §3.17 olarak yedirildi; Workshop Spine sıralama uyumluluğu zaten korunuyor). (1) **Karar 17** ile HMDK 13 madde bağlam kanonu ana Decision Log'a yedirildi: §1 editör notu Karar 11 → 17 satırı kapatıldı; §8 HMDK başlığı "Karar 17 — alt-maddeler"; pilot paket iskeleti `workshop/kurumsal-pilot-paketleri/hmdk-stuttgart-ocak-2027/` açıldı. (2) **Karar 18** ile Berlin Eylül 2026 pilotu ana repoya yedirildi: §1 editör notu Berlin açık karar kapatıldı; §8 Berlin bölümü "Karar 18 — alt-maddeler"; §9 Brief çelişkisi notu Berlin yedirme satırıyla güncellendi; pilot paket iskeleti `workshop/kurumsal-pilot-paketleri/berlin-eylul-2026/` açıldı. (3) **Karar 19** ile §4 A2 ortak omurga "Yolculuk" satırında süre referansları 45-60 dk aralığına revize edildi; §2 Etik koruma listesine "karakter spektrumu sınırı yok" maddesi eklendi (Filiz klinik onayı bekleniyor); §8'e ses kayıtları arşivleme onay formu maddesi eklendi (Filiz onayı bekleniyor); tarihsel kayıt arşivi iskeleti `workshop/karakter-dosyalari/tarihsel-kayit-referanslari/` açıldı. v1.2'nin tüm içeriği aynen korundu.

---

## 11 · Bu Spine'ın Kullanımı

- ITC Workshop projesinin canlı kanonudur. GitHub'da güncellenir, projeye yüklenir.
- Yeni bir Claude sohbeti açıldığında bu doküman + Ekosistem Spine v1.7+ + Decision Log v1+ birlikte okunur.
- Workshop'a özel bir karar verildiğinde Beyti bu Spine'ı günceller, projeye yeniden yükler.
- Spine ile dış üretim (master outline, facilitator notes, pazarlama materyali) arasında çelişki çıkarsa **Spine kazanır** (single source of truth).

---

*— ITC Workshop Spine v1.3 sonu —*
*Inside The Character · Beyti Engin & Filiz Kaya Ataklı — Eş Kurucular ve Eş Eğitmenler, 2005'ten bu yana*
