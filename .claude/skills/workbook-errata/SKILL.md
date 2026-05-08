---
name: workbook-errata
description: Hamlet Workbook 2. baskı için biriken errata listesini yönetir. Yeni hata/eklenti/çapraz referans isteği geldiğinde errata-listesi.md'ye yapılandırılmış olarak ekler. Önceliklendirme ve klinik onay durumunu takip eder.
---

# Skill: Workbook Errata

## Ne Zaman Tetiklenir

- "Workbook 2. baskıya şunu ekle"
- "s.XX'de hata var"
- "Workbook errata'ya kayıt at"

## Errata Madde Formatı

Her madde `workbook/errata-listesi.md`'ye şu yapıyla eklenir:

```markdown
## [#] [Sayfa/Bölüm referansı] — [Kısa başlık]

**Eklenme tarihi:** [Tarih]
**Kategori:** [Errata düzeltmesi / Klinik güvenlik / Çapraz atıf / Kanon güncellemesi / Tasarım]
**Öncelik:** 🔴 Kritik / 🟡 Yüksek / 🟢 Orta / ⚪ Düşük
**FKA klinik onayı:** Gerekli / Var / Gerek yok

### Sorun

[Mevcut hâli, ne yanlış/eksik]

### Çözüm

[Ne yapılacak — somut]

### Bağlantılı Karar

[Decision Log kaydı: Tarih + Başlık]
```

## Önceliklendirme

- 🔴 Kritik: Klinik güvenlik / kanon hatası / etik ihlal — basıma izin vermez
- 🟡 Yüksek: Yapısal hata / TOC tutarsızlığı / Method Book çapraz referans
- 🟢 Orta: Ekosistem güncellemesi (App durumu, MBTI QR, vb.)
- ⚪ Düşük: Stilistik, tipografik

## Çapraz Etki

Errata güncellemesi yapıldığında:

1. Yeni Decision Log kaydı (Tip 3 — İçerik Güncellemesi) — eğer henüz yoksa
2. Eğer kanon güncellemesi sonucuysa Spine'a da yansıt
3. Workbook 2. baskı manuscript şu an yazılıyorsa hemen Beyti'ye haber ver
