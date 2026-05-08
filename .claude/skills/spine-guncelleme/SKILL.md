---
name: spine-guncelleme
description: ITC Spine dosyasını güncellerken sürüm numarasını artırır, sürüm geçmişine satır ekler, ilgili bölümü değiştirir. Spine canon belgesidir; her değişiklik dikkatli yapılır ve Decision Log'la senkron çalışır.
---

# Skill: Spine Güncelleme

## Ne Zaman Tetiklenir

- "Spine'a şunu ekle"
- "§X.Y'yi güncelle"
- "Spine sürümünü yükselt"

## Kritik Kural

**Spine bağımsız güncellenmez.** Her Spine güncellemesi bir karara bağlıdır:
- Önce Decision Log'a kayıt
- Sonra Spine güncelleme
- İkisi aynı commit setinde

Eğer Beyti Decision Log kaydı yapmadan Spine güncellemesi isterse: önce kaydı oluşturmasını öner.

## Sürüm Numaralandırma

- **Major (vX.0):** Tam revizyon — birden fazla bölüm değişti, yapı yeniden çizildi
- **Minor (vX.Y):** Tek bölüm değişti, içerik güncel hale geldi
- **Patch:** Tipo, format düzeltmesi — sürüm numarası değişmez

Çoğu güncelleme Minor'dur (vX.Y → vX.Y+1).

## Adımlar

### 1. Mevcut Sürümü Tespit Et

`spine.md` üst kısmında "Sürüm: vX.Y" yazılı. Bu numarayı oku.

### 2. Yeni Bölüm Metnini Hazırla

Karar paketindeki yeni metni al, format ve başlık tutarlılığını kontrol et.

### 3. Eski Bölümü Değiştir

`spine.md`'de §X.Y'yi tamamen yeni metinle değiştir. **Eski metni silme — yer değiştir.**

### 4. Sürüm Numarasını Güncelle

Üstteki "Sürüm: vX.Y" → "Sürüm: vX.Y+1"
"Son güncelleme: [yeni tarih]"

### 5. Sürüm Geçmişi'ne Satır Ekle

`spine.md`'nin en altındaki "Sürüm Geçmişi" bloğunda **en üste** (en yeni en üstte):

```
v[YENİ] — [TARİH] — [Kısa açıklama: hangi §X.Y değişti, neden, hangi karara dayanıyor]
```

### 6. Commit

```
git add spine.md
git commit -m "spine: vX.Y → vX.Y+1, §X.Y güncellendi ([konu])"
```

## Edge Cases

- **Birden fazla bölüm aynı anda değişiyorsa:** Her bölüm için ayrı satır, ama tek bir sürüm artırımı (örn. v1.3 → v1.4 olur, v1.5 değil).
- **Bölüm tamamen kaldırılıyorsa:** Önce karar paketinde gerekçesi olmalı. Numarası boş kalmaz, alttakiler kaydırılır ve §4'teki çapraz tabloda da güncellenir.
- **Yeni bölüm ekleniyorsa:** §3.X numarası kullanılır (örn. §3.12). İçindekilere de eklenir.
