# ITC Canon — Claude Code Rehberi

Bu repo, **Inside The Character** ekosisteminin kanon dokümanlarıdır — yavaş evrilen, yüksek-otoriteli kaynaklar. ITC Actor's Gym uygulaması bu repo'nun içinde `app/` submodule'u olarak yaşar.

---

## Yapı

İki katmanlı:

**Kanon belgeleri (root)** — yavaş evrilir, dikkatli güncellenir
- `spine.md` — ITC ekosistem omurgası (sürüm numaralı, canlı belge)
- `decision-log.md` — kronolojik karar arşivi
- `brief-v2.md` — 24 aylık yol haritası
- `kararlar/` — karar paketleri (tarih bazlı)
- `workbook/` — Hamlet Workbook'a özel notlar
- `method-book/` — Method Book'a özel notlar
- `workshop/` — Workshop modüllerine özel notlar (D1, D2, C2, E1)

**Uygulama (`app/` submodule)** — hızlı evrilir, kendi repo'su
- `app/` → `github.com/beytiengin/itc-app` (Vercel'e bağlı, canlı)
- Stack: Next.js 14+ · Supabase · Vercel
- Kendi `CLAUDE.md`'si var (`app/CLAUDE.md`) — teknik detaylar orada

---

## Çalışma akışı

### Canon belgesi düzenliyorsan (root'taki `.md` dosyaları)

- **Sürüm/tarih notunu güncelle** — spine ve decision-log canlı belgeler, her güncellemede tarih + sürüm
- **decision-log'a yansıtması gerekiyor mu?** Stratejik bir karar ise mutlaka oraya da işlenir
- **Filiz Kaya Ataklı'nın** (eş kurucu, klinik psikolog) ilgilendiği konularda (klinik kuram, etik koruma, terminoloji) yazılı onayını bekle ya da kullanıcıya hatırlat

### App'te kod yazıyorsan (`app/` içinde)

- `app/CLAUDE.md`'deki kurallara uy (kapsamlı — stil, mimari, ITC pedagojik ilkeleri orada)
- Submodule'da commit atınca **iki yerde commit gerekir**:
  ```bash
  # 1. App içinde
  cd app
  git add . && git commit -m "..." && git push origin main
  # 2. Canon'a dön, pointer'ı tazele
  cd ..
  git add app && git commit -m "bump app to ..." && git push origin main
  ```
- Pointer commit'ini atmazsan canon, app'in eski commit'ini "referans" olarak göstermeye devam eder

---

## Eş kurucular

- **Beyti Engin** — oyuncu/eğitmen, ITC metodolojisinin kurucusu (2005-)
- **Filiz Kaya Ataklı** — klinik psikolog, eş kurucu (Karar 16, 2026-05-12 ile kanonlandı; yazılı onay süreci için `decision-log.md`'ye bak)

---

## Pedagojik ilkeler (özet)

`app/CLAUDE.md`'de detayı var; hızlı referans:

1. **Karakter kişisel travmayla inşa edilmez** — ITC, Method Acting'in tersi. Etik koruma kritik.
2. **Oyuncu eş-yazardır** — yazarın sustuğu yerleri oyuncu yazar (boşluklar bu ilkenin somut karşılığı).
3. **Metot görünmez, oyuncu görünür** — kişiselleştirme sessiz olur, meta-açıklama yapılmaz.
4. **Hız ile derinlik sacayağı** — kısa adımlar, derin imkan birlikte.
5. **Çıkış da bir performans** — deroling/topraklanma sıradan UI değil, pedagojik olarak kritik.

---

## Dil ve ton

- **Türkçe.** UTF-8 (ı, İ, ş, ğ, ü, ö, ç)
- Akademik ama mesafeli değil — pedagojik bir kanon
- Commit mesajlarında Türkçe karakter kullanma (bazı git ortamları sorun yaşıyor)

---

**Güncel ekosistem durumu için `spine.md` baş başlığına bak.**
