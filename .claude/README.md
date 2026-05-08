# Claude Code Konfigürasyonu — ITC Canon

Bu repo Inside The Character ekosisteminin kanon dokümanlarını barındırır.

## Claude'un Bilmesi Gerekenler

Bu repo'da çalışırken:

1. **Kanon dokümanlar** sürüm numaralı tutulur — `spine.md`, `decision-log.md`, `brief-v2.md`. Bunları güncellerken sürüm geçmişi bloğuna satır ekle.

2. **Karar paketleri** `kararlar/YYYY-MM-DD-konu/` klasörlerinde durur. Yeni bir karar geldiğinde bu yapıyla aç.

3. **Etik çerçeve** mutlak. `rules/etik-cerceve.md`'yi her oturum başında oku — substitution kullanılmaz, travma matrisi 8×4, "sahip değil — misafir" ilkesi.

4. **Terminoloji** `rules/terminoloji.md`'de tanımlı — kanonik terimler ekosistem boyunca tutarlıdır.

5. **Decision Log formatı** `rules/decision-log-format.md`'de — yeni kayıt eklerken bu formata uy.

## Çalışma Tarzı

- Her büyük değişiklik **ayrı commit** olarak yazılır
- Commit mesajları Türkçe yazılır (proje dili)
- Değişiklik birden fazla dosyaya yayılırsa her dosya kendi commit'inde
- Kanon değişikliği (Tip 1) için Decision Log + Spine + ilgili proje dokümanları üçü birden güncellenir
