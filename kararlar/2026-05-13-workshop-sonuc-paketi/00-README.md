# 13 Mayıs 2026 — Workshop Sonuç Paketi (Karar 17–20)

**Tarih:** 13 Mayıs 2026
**Karar veren:** Beyti Engin
**Tasarım eş yazımı:** Claude (Anthropic)
**Tetikleyici:** Workshop sohbeti 11-13 Mayıs 2026 — Kanon Hatırlatma belgesi maddeleri.

---

## Bu paket ne içerir

Workshop sohbetinin sonunda kompoze hâlde gelen **dört karar** tek pakette yedirildi. Hepsi 13 Mayıs 2026 tarihli, hepsi ana Spine v1.7 → v1.8 sürüm bandında. Brief v2.2 → v2.3 yedirmesi bu paketin kapsamı dışında — ayrı oturuma bırakıldı.

| # | Karar | Tip | Birincil etki |
|---|---|---|---|
| 17 | HMDK Stuttgart 25-29 Ocak 2027 Bağlam Kanonu (13 madde) | Tip 2 | Workshop kurumsal akademik pilot |
| 18 | Berlin Chubbuck Studio Eylül 2026 A2-Berlin-Variant Pilotu | Tip 2 + Tip 4 | Workshop ilk gerçek pilot + marka geçişi |
| 19 | Berlin Tarihsel Ses Kayıtları + Yolculuk Süresi Kanonu | Tip 1 + Tip 2 | Spine §3.16 süre parametresi + arşiv etiği |
| 20 | ITC Tarihsel Çizgi Kanonu + İsim Sıralaması | Tip 1 | Spine §3.17 yeni alt-bölüm + meta-çerçeve |

## Dosyalar

| Dosya | İçerik |
|---|---|
| `00-README.md` | Bu dosya — paketin meta-özeti |
| `01-karar-17-hmdk-stuttgart.md` | Karar 17 tam metni (Beyti'nin gönderdiği hâliyle) |
| `02-karar-18-berlin-chubbuck.md` | Karar 18 tam metni |
| `03-karar-19-yolculuk-suresi-arsiv.md` | Karar 19 tam metni (üç alt-karar: A süre, B spektrum, C arşiv) |
| `04-karar-20-tarihsel-cizgi-siralamasi.md` | Karar 20 tam metni (A tarihsel çizgi, B sıralama, C özgeçmiş hâlleri) |
| `05-spine-guncellemesi.md` | Spine v1.7 → v1.8 entegre değişiklik notu (4 karar birleşik) |
| `06-workshop-spine-guncellemesi.md` | Workshop Spine v1.2 → v1.3 entegre değişiklik notu (3 karar: 17+18+19) |

## Yedirme Adımları (Bu Pakette Yapıldı)

1. ✓ Arşiv klasörü açıldı: `kararlar/2026-05-13-workshop-sonuc-paketi/`
2. ✓ `decision-log.md` — 4 karar girişi en üste eklendi (Karar 20 → 19 → 18 → 17 sırasıyla, hepsi Karar 16'nın üstünde), kronoloji tablosuna paket satırı
3. ✓ `spine.md` — v1.7 → v1.8: yeni "v1.8'de neler değişti" bloğu (4 karar), §1 ekosistem haritası eş kurucu paragrafına Karar 20 sıralama eki, §3.16'ya Karar 19 süre parametresi, §3.17 yeni alt-bölüm (Karar 20 — Yöntem Tarihsel Çizgisi), Sürüm Geçmişi v1.8 satırı, footer
4. ✓ `workshop/spine.md` — v1.2 → v1.3: §1 editör notunda Karar 11/Berlin açık karar tablosu kapatıldı, "v1.3'te Neler Değişti" bloğu, §4 Modül III süreleri 45-60 dk aralığına revize (Karar 19), §6 yolculuk slot süreleri güncellendi, §8 HMDK başlığı (Karar 17) ve Berlin bölümü (Karar 18) güncellendi, §9 Brief v2 çelişkisi notu HMDK + Berlin yedirme satırlarıyla güncellendi, Sürüm Geçmişi v1.3 satırı, footer
5. ✓ Workshop yeni klasörler iskelet hâlinde açıldı:
   - `workshop/kurumsal-pilot-paketleri/hmdk-stuttgart-ocak-2027/` (Karar 17)
   - `workshop/kurumsal-pilot-paketleri/berlin-eylul-2026/` (Karar 18)
   - `workshop/karakter-dosyalari/tarihsel-kayit-referanslari/` (Karar 19)

## Bilerek Yedirilmedi (Sonraki Tura Bırakıldı)

- **Brief v2.2 → v2.3** — Karar 17 (HMDK Faz 2 Milestone 2.7 detay) + Karar 18 (Faz 1 yeni Milestone 1.8 Berlin) + Karar 20 (önsöz §1 yöntem tarihçesi + tüm sıralama denetimi). Bütünleşik tek yedirme olarak ayrı oturumda yapılır (büyük dosya, ayrı odak).
- **Method Book Project Instructions + Workshop Project Instructions** — Karar 20 §3.17 çizgisi + C maddesi sabit özgeçmiş hâlleriyle güncelleme (gelecek iş).
- **Çeviri paketi (BE/FKA özgeçmiş EN + DE)** — Karar 20 C maddesinin EN ve DE versiyonları FKA onay turunda ayrı kanonlanır.
- **Karakter dosyaları** — `workshop/karakter-dosyalari/hamlet-atolye-dosyasi.md` Günther DE versiyonu (Karar 17) ayrı görev.

## Açık [DOLDUR] Alanları (Paket Genelinde Takipte)

**Karar 17 (HMDK):**
- Prof. Katherina'nın soyadı (HMDK koordinasyon)
- Anlık DE çevirmen adı + iletişim (atölye öncesi terminoloji oturumu)
- Saatlik ücretlendirme tutarı (HMDK ile mutabakat sonrası)
- Pre-work temas anketi tasarımı (BE + Claude ayrı oturum)

**Karar 18 (Berlin):**
- Eylül 2026 spesifik tarih (Chubbuck koordinasyonu — Eylül başı/ortası/sonu)
- Berlin Chubbuck Studio kontak adı (koordinasyon)
- Hamlet metin EN versiyonu durumu (Workbook 2. baskı EN ne kadar hazır)
- Berlin paketi gönderim tarihi (Mayıs sonu hedef, gerçek deadline netleşmedi)
- Participant Advance ön koşul tanımı (A2 mezunu zorunlu mu, profesyonel deneyim eşdeğer mi)
- Participant Advance ücretlendirmesi (~€150-200 üstü Participant'tan, Chubbuck onayı)

**Karar 19 (Tarihsel kayıtlar):**
- Bianca/Sofia ses kaydı yeniden export tekniği
- Karakter spektrumu ek tarihsel/dramatik örnekler (varsa)

**Karar 20 (Tarihsel çizgi):**
- 2022 başlangıç tarihi netleştirme (HMDK + Chubbuck Berlin işbirliği için kesin tarih varsa)

## Karar 19 Filiz Klinik Onayı Notu

Karar 19 B (Karakter Spektrumu Sınırı Yok) ve C (Ses Kayıtları Arşivleme Etiği) klinik kararlardır — Filiz klinik onayı turunda gözden geçirilmesi natural. Karar 19 metni Spine'a girer ama Decision Log Notlar'da **"⚠ Filiz klinik onayı bekleniyor (B + C maddeleri)"** flag'i taşır. A maddesi (45-60 dk süre kanonu) operasyonel parametre; flag dışı.

Karar 16 (FKA Eş Kurucu) hâlâ provisional — Karar 17, 18, 20 içinde de provisional flag dolayısıyla taşınır.

## İlişkili Önceki Kararlar

- **Karar 11** (Workshop sohbeti, ana repoda farklı içerik = Transmisyon Mimarisi BE × FKA): Karar 17'nin Workshop sohbetindeki orijinal numarası
- **Karar 12** (Workshop sohbeti = ana Karar 16): Karar 18 marka geçişi Karar 16 EN formülasyonu üzerine kuruluyor
- **Karar 14** (§3.16 Yolculuk Geometrisi, Filiz klinik onayı bekleniyor): Karar 19 §3.16'ya süre parametresi ekleyerek bu çerçeveyi genişletiyor
- **Karar 15** (Brief v2.1 HMDK tarih düzeltmesi): Karar 17'nin ön zemini
- **Karar 16** (FKA Eş Kurucu, Filiz yazılı onayı bekleniyor): Karar 18'in ilk profesyonel oyuncu stüdyosu uygulaması; Karar 20'nin sıralama kuralı eki

---

*13 Mayıs 2026 Workshop Sonuç Paketi · Beyti Engin & Filiz Kaya Ataklı — Eş Kurucular ve Eş Eğitmenler · Claude (operasyonel eş yazım)*
