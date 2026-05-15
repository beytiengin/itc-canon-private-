# Karar 21 — Yıldız Oyuncu Matrisi ve Travma Sistemi Ayrılması

**Tarih:** 15 Mayıs 2026
**Tip:** Tip 1 — Kanon Değişikliği
**Spine sürümü:** v1.8 → v1.9
**Karar veren:** Beyti Engin + Filiz Kaya Ataklı (eş onaylı)
**Tasarım eş yazımı:** Claude (Anthropic)

## Tetikleyici

ITC App'in temel yapısı incelendiğinde, Yıldız Oyuncu Matrisi'nin yalnızca *psikolojik* boyutunun travma erişim eşiği olarak kullanıldığı, matrisin 6 boyutlu pedagojik amacının (öz-farkındalık + karaktere çoklu eksenden yaklaşım) sistemde gerçek karşılığının olmadığı tespit edildi. Bu yapı pedagojik kayıp yaratıyordu; aynı zamanda Substitution Yasağı (§3.1) ile yapısal gerilim içindeydi — oyuncu profili karakterin verisinin önüne geçen bir gate kuruyordu.

## İçerik

- `01-karar-21-yildiz-travma-ayrismasi.md` — Ana karar metni (decision-log.md'ye yedirilen kayıt)
- `02-spine-guncellemesi.md` — spine.md v1.8 → v1.9 değişiklikleri (10+ alt-bölüm)
- `03-etik-cerceve-guncellemesi.md` — `.claude/rules/etik-cerceve.md` değişiklikleri (§2 + §3 + §4)
- `04-app-degisiklik-listesi.md` — App tarafında yapılacak refactor kapsamı (ayrı iş paketi olarak kuyrukta; bu pakette kanon değişikliği yapıldı, kod henüz yapılmadı)

## Özet

Yıldız Oyuncu Matrisi (Spine §3.9) ile Travma Sistemi (§3.3) arasındaki bağ tamamen koparıldı. Mevcut "Yıldız Profil Eşleşme Matrisi" alt-bölümü (v1.0'dan beri kanonik FKA klinik tasarımı) kanondan geri çekildi.

**Yeni mimari (üç bağımsız sistem):**

1. **Yıldız Matrisi** — sadece pedagojik. 6 boyutlu öz-farkındalık haritası + karaktere yaklaşım katmanı (VAK'ın `vakDili` örüntüsünde).
2. **Travma Sistemi** — sahne-level etiketleme + oyuncuya uyarı. Profil-bağımsız.
3. **Topraklanma** — yoğunluk 2 (Tanıklık) ve 3 (İcra) sahneler sonrası otomatik tetiklenir. Profil-bağımsız, kategori-bağımsız.

**Gerekçe:** Substitution Yasağı (§3.1) ile yapısal uyum. Karakter, oyuncudan bağımsız bir veri yapısıdır; oyuncu profili karakteri biçimlendirmez.

**Filiz Kaya Ataklı'nın 2005'ten beri klinik tasarımı olan Yıldız Profil Eşleşme Matrisi'nin geri çekilmesi kendi eş kurucu onayıyla yapılmıştır.**
