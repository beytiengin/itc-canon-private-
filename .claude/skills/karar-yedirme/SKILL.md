---
name: karar-yedirme
description: Beyti'den yeni bir karar paketi geldiğinde repo'ya yedirir. Decision Log + Spine + ilgili proje dokümanları üçünü senkron günceller. Karar tarihi YYYY-MM-DD formatında bir klasör altında arşivlenir, ana belgelere ilgili kısımlar yansıtılır.
---

# Skill: Karar Yedirme

## Ne Zaman Tetiklenir

Beyti şu şekilde bir şey dediğinde:

- "Şu kararı sisteme yedir"
- "Bu karar paketini repo'ya işle"
- "Yeni bir karar var, kayıt et"
- "[Tarih]'in kararını commit'le"

## Adımlar

### 1. Karar Paketini Tanımla

Beyti'nin verdiği karar paketinde şunlar olmalı:
- Karar başlığı
- Tip (1/2/3/4)
- Spine sürüm değişimi (varsa)
- Etkilenen katmanlar
- Karar metni
- Üretilen dosyalar (eklentiler, güncellemeler, errata revizyonları)

Eğer eksik bilgi varsa Beyti'ye sor — yedirme öncesi netleşsin.

### 2. Arşiv Klasörü Oluştur

```
kararlar/YYYY-MM-DD-konu-kısa-isim/
├── 01-decision-log-eklentisi.md
├── 02-[varsa-spine-guncellemesi].md
├── 03-[varsa-errata-revizyonu].md
└── ... (paket içindeki diğer dosyalar)
```

Slug temiz olsun: Türkçe karakter yok, küçük harf, tire ile ayrılmış.

### 3. Decision Log'a Yeni Kayıt Ekle

`decision-log.md`'yi aç. **En üste** (Kararlar başlığının hemen altına) yeni kaydı ekle. Format için `.claude/rules/decision-log-format.md`'yi referans al.

### 4. Spine Güncellemesi (Varsa)

Eğer paket Spine güncellemesi içeriyorsa:
- `spine.md`'de ilgili §X.Y bölümünü değiştir
- "Sürüm" başlığında numarayı güncelle (vX.X → vX.X+Y)
- "Sürüm Geçmişi" bloğuna yeni satır ekle (en yeni en üstte)
- Eski sürümün tam metnini SİLME — sadece §X.Y'nin yeni hâliyle yer değiştir

### 5. Etkilenen Proje Dokümanları

Karar paketinde belirtilen etkilenen katmanlara göre:

- **Workbook** etkileniyorsa → `workbook/errata-listesi.md` ve/veya `workbook/karsilastirma-raporu.md` güncelle
- **Method Book** etkileniyorsa → `method-book/` altındaki ilgili dosya
- **Workshop** etkileniyorsa → `workshop/` altındaki ilgili dosya
- **App** etkileniyorsa → not düş ama doğrudan App repo'sunu değiştirme (App ayrı repo)

### 6. Commit Stratejisi

**Her dosya değişikliği ayrı commit.** Bundle'lama. Commit mesajları Türkçe:

```
git add kararlar/YYYY-MM-DD-konu/
git commit -m "kararlar: YYYY-MM-DD [konu] paketi eklendi"

git add decision-log.md
git commit -m "decision-log: [konu] kararı eklendi"

git add spine.md
git commit -m "spine: vX.X → vX.X+Y, §X.Y güncellendi ([konu])"

git add workbook/errata-listesi.md
git commit -m "workbook: errata listesine [madde] eklendi"

git push
```

### 7. Onay

Tüm commit'ler push'landıktan sonra Beyti'ye özet ver:
- Hangi commit'ler atıldı
- Hangi dosyalar değişti
- GitHub'da bakmak için link
- Açık kalan iş varsa (örn. Filiz klinik onayı bekleniyor) hatırlat

## Edge Cases

- **Aynı gün birden fazla revizyon:** Kararlar tarih sırasına göre Decision Log'a eklenir, en yeni en üstte. Spine'da sadece son sürüm yaşar (eski metin yer değiştirir, ama Decision Log'da iki kayıt da kalır).
- **Filiz onayı bekliyorsa:** Decision Log'a kayıt girer ama Notlar'da "**Filiz onayı bekleniyor**" işareti olur. Yayına/baskıya gitmeyecek dosyalar `kararlar/` klasöründe DRAFT olarak kalır.
- **Açık karar çözüldüyse:** Spine §5'teki açık kararlar listesinden silinir, ilgili bölüme yerleşir.
