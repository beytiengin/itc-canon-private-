# Brief v2.0 → v2.1 Güncellemesi — HMDK Stuttgart Tarih Düzeltmesi

**Hedef:** Brief sürümü v2.0 → v2.1
**Tarih:** 12 Mayıs 2026
**Karar referansı:** Karar 15 (Workshop Geri Besleme Paketi)
**Tip:** İçerik Güncellemesi (Tip 3) + Açık Karar Çözüldü (Tip 4)

---

## Karar Özeti

Brief v2'de HMDK Stuttgart pilotu **Faz 3 Milestone 3.1 (Ay 15–18, Ağustos–Kasım 2027)** olarak yer alıyor. Gerçek pilot tarihi **25–29 Ocak 2027** — bu tarih **Faz 2'nin ortası** (Ay 8) ve bambaşka bir stratejik pozisyon taşır.

Bu düzeltme tarih tashihinden fazlasıdır: HMDK pilotunun ekosistemdeki **rolü değişir** — "Faz 3 olgunluk hedefi" değil, "Faz 2 ortasında akademik meşruiyet enjeksiyonu" haline gelir. Brief'in genel mantığı değişmez, yalnızca bir milestone'un faz konumu değişir.

## Operasyonel Sonuçlar

### Schlegel-Tieck Hamlet Adaptasyonu — Kritik Darboğaz

HMDK Stuttgart pilotu Almanca yapılır. Brief v2'de bu Almanca versiyon Ay 12–18 (Faz 2 sonu — Faz 3 başı) yazılı. Yeni takvimde:

**Schlegel-Tieck Hamlet adaptasyonu Mayıs–Temmuz 2026'da bitmiş olmalı** — yani önümüzdeki üç ayda. Bu Faz 1'in başında, App Hamlet refactor'üyle paralel sprint.

Bu darboğazın çözümü Faz 1 zaman çizelgesini etkiler — Method Book Bölüm III prototip yazımı (Milestone 1.7) ile Schlegel-Tieck adaptasyonu arasında öncelik kararı verilmesi gerekir. Olası strateji: ikisini paralel yürütmek, Schlegel-Tieck için ayrı bir çevirmen/dramaturg desteği almak.

### Faz 2 Strateji Değişikliği

HMDK pilotu Faz 2'nin ortasına geldiğinde Faz 2'nin diğer milestone'larıyla **koordinasyon** kritikleşir:

- **Milestone 2.2 (Method Book ana yazım fazı, Ay 7–14):** Pilot sırasında ana bölümler hâlâ yazım fazında. Pilot deneyimi Method Book Bölüm E'ye (Uygulama Vakaları) **canlı vaka** olarak girer.
- **Milestone 2.4 (Akademik makale yazımı, Ay 8–12):** Pilot makale yazımının veri kaynağı olur. Pilot sonu rapor (Şubat 2027) makaleyi hızlandırır.
- **Milestone 2.3 (İngilizce App versiyonu, Ay 9–12):** HMDK Almanca pilot deneyimi i18n altyapısının test ortamı olur (Almanca eklenirse İngilizce daha kolay gelir).

### Faz 3 Boşluğu

Brief v2'de Faz 3 Milestone 3.1 (HMDK Stuttgart Pilot) artık boş kalır. Bu boşluk Faz 3 yapısının yeniden değerlendirilmesini gerektirir — Karar 15'in dolaylı bir sonucu. Olası dolgu: Royal Central, RADA, Stella Adler gibi ikinci dalga akademik pilotlardan biri Faz 3'te konumlanır.

---

## Brief'te Yapılacak Düzeltmeler

### Düzeltme 1 — Üst Meta

**Mevcut:**
```markdown
**v2.0**
**Hazırlayan:** Beyti Engin
[...]
**Tarih:** Mayıs 2026
```

**Yeni:**
```markdown
**v2.1**
**Hazırlayan:** Beyti Engin
[...]
**Tarih:** Mayıs 2026 (v2.1: 12 Mayıs 2026)
**Spine Sürümü Referansı:** v1.6 (12 Mayıs 2026 itibarıyla) — dört katmanlı yapı (Method Book / Workbook / App / Workshop) operasyonel, §3'te dört yeni kanon alt-bölümü (§3.13–3.16) eklendi.
```

(Eski "Spine Sürümü Referansı: v1.1 ... v1.3" satırı bu yeni satırla yer değiştirir.)

### Düzeltme 2 — Önsöz Notu

Mevcut önsözün altına, "Brief'in stratejik tonu..." paragrafından sonra eklenir:

```markdown
**v2.1 revizyon notu (12 Mayıs 2026):** Bu revizyon Brief v2.0'ın genel yapısını korur. Tek stratejik değişiklik HMDK Stuttgart pilotunun faz konumudur — Faz 3 Milestone 3.1'den çıkarılıp Faz 2 ortasına (Ocak 2027, Ay 8) taşındı. Bu değişiklik Schlegel-Tieck Hamlet adaptasyonunu Mayıs–Temmuz 2026 (Faz 1 başı) kritik bir sprint hâline getirir. Ayrıca Spine v1.6 referansı güncellendi.
```

### Düzeltme 3 — §2.1 Method Book Durumu Notu

Mevcut §2.1 sonuna eklenir:

```markdown
*Not (v2.1): Method Book Bölüm E (Uygulama Vakaları), HMDK Stuttgart pilotunun (Ocak 2027) verisini canlı vaka olarak alacak. Bölüm E yazımı Faz 2 boyunca pilotla paralel ilerler.*
```

### Düzeltme 4 — §5 Faz 2 Milestone 2.X Bölümüne Yeni Milestone

Mevcut Faz 2 milestone'larına Milestone 2.7 olarak eklenir (Milestone 2.6'dan sonra):

```markdown
#### Milestone 2.7 — HMDK Stuttgart Pilot (Ay 7–9 — Yeni Konum, Karar 15) ← v2.1'de eklendi

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
```

### Düzeltme 5 — §5 Faz 3 Milestone 3.1 Bölümü

**Mevcut:**
```markdown
#### Milestone 3.1 — HMDK Stuttgart Pilot (Ay 15-18)

**Çıktılar:**
- HMDK ile resmi pilot anlaşması (1 yarıyıl, 1 sınıf)
- Almanca versiyon (Schlegel çevirisi, Ay 12-18 paralel çalışma)
- HMDK öğretim üyesi ile haftalık koordinasyon
- Pilot sonu rapor (akademik makaleyi ve Method Book Bölüm V'i besler)

**Kabul kriteri:** HMDK pilot tamamlandı, en az 12 öğrenci kullandı, pozitif geri bildirim (≥4/5).
```

**Yeni (yer değiştirir):**
```markdown
#### Milestone 3.1 — İkinci Dalga Akademik Pilot (Ay 15-18, Karar 15 sonrası yeniden konumlandı)

**v2.1 notu:** HMDK Stuttgart pilotu Faz 2 Milestone 2.7'ye taşındı (gerçek pilot tarihi 25–29 Ocak 2027). Faz 3 Milestone 3.1 boşalan konum için "ikinci dalga akademik pilot" hedefli — Royal Central, RADA, veya Stella Adler bağlantılarından biri. Spesifik kurum kararı Faz 2 sonunda HMDK pilot raporundan sonra alınır.

**Çıktılar:** [İkinci dalga kurum belirlendiğinde detaylanacak]
- İkinci akademik kurumla pilot anlaşması
- HMDK pilot raporu pazarlama materyali olarak kullanılır
- Yeni dil/çeviri ihtiyacı (kurum İngilizce ya da farklı dilde olursa)

**Kabul kriteri:** İkinci kurumda pilot tamamlandı, HMDK ile karşılaştırmalı veri elde edildi (akademik makale için iki vakalık bir dataset).
```

### Düzeltme 6 — §10.4 Akademik Kabul Kriterleri

**Mevcut:**
```markdown
- [x] HMDK Stuttgart pilot tamamlanmış
```

**Yeni:**
```markdown
- [x] HMDK Stuttgart pilot tamamlanmış (Faz 2 Ocak 2027 — Karar 15)
- [x] İkinci dalga akademik pilot tamamlanmış (Faz 3, kurum Faz 2 sonunda belirlenir)
```

### Düzeltme 7 — §9.4 Ekosistem Açık Kararları

Mevcut listenin sonuna eklenir:

```markdown
- **İkinci dalga akademik kurum kararı** (Faz 3 Milestone 3.1 için): Royal Central, RADA, Stella Adler arasından hangisi — HMDK pilot raporu sonrası karar
```

### Düzeltme 8 — §11 Sonuç Paragrafına Ek

Mevcut "**Brief'in en kritik tek mesajı:**..." cümlesinden önce eklenir:

```markdown
v2.1 revizyon hatırlatması: HMDK Stuttgart pilotu artık Faz 3 hedefi değil, Faz 2 ortası kritik milestone'dur. Faz 1'in başında Schlegel-Tieck Hamlet adaptasyonu (Mayıs–Temmuz 2026) kritik darboğazdır — bu adaptasyon bitmeden HMDK pilotu yapılamaz, dolayısıyla Faz 1 sprint planlaması bu darboğazı ön planda tutmalıdır.
```

### Düzeltme 9 — EK C Acil İlk Adım Listesine Ek

Mevcut "1. Decision Log dosyası kur..." listesinin başına (yeni 1. madde olarak) eklenir:

```markdown
1. **Schlegel-Tieck Hamlet adaptasyon sprintini başlat** (Mayıs–Temmuz 2026, Faz 1 başı kritik darboğaz — HMDK Ocak 2027 pilotunun ön koşulu)
```

Mevcut maddeler 2'den itibaren numaralanır.

### Düzeltme 10 — Brief Sonu Üst Meta

**Mevcut:**
```markdown
*Versiyon: v2.0*
*Tarih: Mayıs 2026*
*Önerilen revizyon: Çeyreklik (üç ayda bir)*
```

**Yeni:**
```markdown
*Versiyon: v2.1*
*Tarih: Mayıs 2026 (v2.1: 12 Mayıs 2026 — HMDK pilotu Faz 3 → Faz 2 taşındı)*
*Önerilen revizyon: Çeyreklik (üç ayda bir)*
```

---

## Spine'a Yansıma

Karar 15 doğrudan Spine'ı etkilemez (Spine'da HMDK tarih ya da faz referansı yok). Ancak:

- **Spine §5 (Açık Karar Noktaları) Ekosistem Geneli:** "App'in yurt dışına açılma stratejisi (Stuttgart, RADA bağlantıları)" maddesi Karar 15 sonrası kısmen netleşir — Stuttgart Ocak 2027 olarak sabit, RADA hâlâ açık.

Bu netleşme Spine v1.6 güncelleme paketinde işlenir mi? Hayır — Spine ekosistem genel sürümlerinden bahseder, takvim detaylarını Brief tutar. Brief v2.1 ile takvim güncellenir, Spine §5 açık kararı genel haliyle korunur.

---

## Decision Log'a Yansıma

Karar 15 Decision Log'a **ayrı kayıt olarak girmez** çünkü:
1. Brief güncellemesi olduğu için Spine'ı etkilemez
2. Karar 11–14 paketinin yan ürünü konumunda

Ancak Workshop Geri Besleme Paketi'nin (`00-README.md`) "Paketteki Kararlar" bölümünde Karar 15 olarak işaretlenir; bu Beyti'nin gelecek oturumlarda paket içeriğini hatırlamasına yardımcı olur.

Decision Log'un "ÖNEMLİ TARİHLER" tablosuna iki satır eklenir (Karar 11–14 eklentisinde belirtildiği gibi):
```
| 12 Mayıs 2026 | Workshop geri besleme paketi (Karar 11–14) — Spine v1.6 yayımlandı |
| 12 Mayıs 2026 | Brief v2.1 yayımlandı — HMDK Stuttgart pilotu Faz 3 → Faz 2 (Ocak 2027) |
```

---

## Schlegel-Tieck Sprint Notu (Karar 15'in Operasyonel Çıktısı)

Bu paketin dışında ama Karar 15'in doğrudan sonucu olarak, Faz 1'in ilk üç ayında Schlegel-Tieck Hamlet adaptasyon sprint'inin ayrı bir iş paketi olarak yürütülmesi gerekir. Bu sprint için:

- Almanca dramaturg/çevirmen kontağı (önümüzdeki haftalarda)
- Schlegel-Tieck Hamlet'inin ITC 13 bölüm yapısına eşleştirilmesi (§3.15 taksonomisiyle uyumlu)
- Bölüm IX (Çapa No 3, "Sein oder Nichtsein") özel klinik koruma katmanının Almanca dilinde formüle edilmesi (Filiz klinik onayıyla)

Bu sprint Workshop projesi sohbetinde ayrı yönetilir; Decision Log'a Schlegel-Tieck kararları geldikçe eklenir.

---

*Brief v2.0 → v2.1 güncellemesi sonu. Yedirme commit'i: `git commit -m "brief: v2.0 → v2.1, HMDK Stuttgart pilotu Faz 3 → Faz 2 (25-29 Ocak 2027), Schlegel-Tieck darboğazı işaretlendi"`*
