# Decision Log Yeni Kayıt Formatı

Yeni karar geldiğinde `decision-log.md`'nin **üstüne** (en yeni üstte) bu formatla eklenir:

```markdown
## [Tarih, örn: 8 Mayıs 2026] — [Karar Başlığı]

**Tip:** Tip [1/2/3/4] — [açıklama]
**Etkilenen katmanlar:** [Method Book / Workbook / App / Workshop arasından]
**Spine sürümü:** vX.X → vX.X+Y (varsa)
**Karar veren:** Beyti [veya başka]
**Tasarım eş yazımı:** Claude (Anthropic) [varsa]

### Karar

[Karar metni — net, tek paragrafta özetlenebilir hâlde]

### Gerekçe

[Niçin bu karar — kısa]

### Uygulama Detayları

- **[Katman 1]** — [ne yapılacak]
- **[Katman 2]** — [ne yapılacak]
- ...

### Notlar

- [Önemli not]
- ...
```

## Tip Açıklamaları

- **Tip 1 — Kanon Değişikliği** (Yüksek Öncelik): kanonik bir kavram değişti
- **Tip 2 — Yapısal Karar** (Orta Öncelik): bir projede yapısal karar verildi
- **Tip 3 — İçerik Güncellemesi** (Düşük Öncelik): içerik değişti, yapı aynı kaldı
- **Tip 4 — Açık Karar Çözüldü** (Orta Öncelik): Spine §5'teki açık kararlardan biri çözüldü

## Çapraz Etki

Her yeni kayıt eklendikten sonra:

1. Spine'da etkilenen bölüm varsa güncelle (§3 sabit ilkeler / §2 güncel durum / §4 çapraz tablo / §5 açık kararlar)
2. Sürüm numarası değiştiyse Spine'ın "Sürüm Geçmişi"ne satır ekle
3. Etkilenen projelerin (Method Book / Workbook / App / Workshop) ilgili dokümanlarına yansıt
4. Workbook 2. baskıyı etkiliyorsa `workbook/errata-listesi.md`'ye satır ekle
