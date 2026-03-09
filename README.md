# 📖 آية اليوم | Daily Ayah

<p align="center">
  <a href="https://siteq8.github.io/daily-ayah"><img src="https://img.shields.io/badge/🚀-Live_Demo-10b981?style=flat-square" alt="Live Demo"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Quran-6236_Ayahs-c9a961?style=flat-square" alt="Ayahs"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Surahs-114-1a3a52?style=flat-square" alt="Surahs"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Script-Uthmani-3b82f6?style=flat-square" alt="Uthmani"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Translation-Sahih_International-059669?style=flat-square" alt="Translation"/></a>
  <a href="#"><img src="https://img.shields.io/badge/lang-AR%20%7C%20EN-c9a961?style=flat-square" alt="Bilingual"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-gold?style=flat-square" alt="License"/></a>
</p>

**The complete Holy Quran — 114 Surahs, 6,236 Ayahs** — in a beautiful, responsive daily ayah web app with authenticated Arabic text (Uthmani script) and verified English translation (Sahih International).

🔗 **Live Demo:** [https://siteq8.github.io/daily-ayah](https://siteq8.github.io/daily-ayah)

---

## 📋 Quran Text Sources & Validation

> **All Quran text in this app is sourced from authenticated, trusted origins. The Arabic text is never manually typed — it is fetched from validated API sources.**

| Component | Source | Validation |
|-----------|--------|------------|
| **Arabic Text** | Uthmani Script (خط عثماني) | King Fahd Complex for Printing the Holy Quran, Madinah |
| **English Translation** | Sahih International | Authenticated translation reviewed by qualified scholars |
| **Data API** | [AlQuran Cloud API](https://alquran.cloud) | Open-source Quran API serving the Uthmani edition |
| **Surah Metadata** | 114 surahs, ayah counts, revelation types | Verified against King Fahd Mushaf (total: 6,236 ayahs) |
| **Duas** | Quran & Sahih Hadith collections | With source reference (surah/hadith citation) |

The app includes a runtime assertion that validates the total ayah count across all 114 surahs equals exactly **6,236** — the authenticated count of the Holy Quran.

---

## ✨ Features

### v2.0 (Current)
- 📖 **Complete Quran** — All 114 surahs, all 6,236 ayahs accessible
- 🕌 **Daily Ayah** — Deterministic daily ayah cycling through the entire Quran (one new ayah per day)
- 📚 **Surah Browser** — Browse all 114 surahs with search, view complete surah text
- 🔤 **Uthmani Script** — Authentic Arabic text using `Amiri Quran` font
- 🌍 **Sahih International** — Verified English translation
- 🌙 **Dark Mode** — Toggle with localStorage persistence
- 🔀 **Random Ayah** — Load any random ayah from the entire Quran
- 📋 **Copy & Share** — Copy ayah text or use Web Share API
- 💡 **Daily Dua** — Authentic supplications from Quran & Hadith with source citations
- 📱 **Fully Responsive** — Desktop, tablet, mobile optimized
- ⚡ **Zero Dependencies** — Pure HTML/CSS/JS (API for Quran text)
- ℹ️ **Source Attribution** — Full sources tab with links to Quran.com, AlQuran.cloud, Tanzil.net, QuranEnc.com

---

## 🚀 Quick Start

### GitHub Pages (Recommended)
1. Fork this repository
2. Go to **Settings → Pages**
3. Select source: `main` branch and `/docs` folder
4. Your site publishes at `https://[username].github.io/daily-ayah/`

### Local
```bash
git clone https://github.com/SiteQ8/daily-ayah.git
cd daily-ayah
open docs/index.html
```

> **Note:** The app requires internet connection to fetch Quran text from the AlQuran Cloud API. Surah metadata (names, ayah counts) is embedded for offline browsing.

---

## 🏗️ Architecture

```
daily-ayah/
├── docs/
│   └── index.html        # Complete app (HTML + CSS + JS)
├── README.md              # This file
├── LICENSE                # MIT License
└── SECURITY.md            # Security policy
```

### How It Works

1. **Daily Ayah**: Calculates a deterministic index from today's date, maps it to one of 6,236 ayahs, fetches from API
2. **Surah Browser**: Renders 114 surah cards from embedded metadata, fetches full surah text on demand
3. **API Source**: `api.alquran.cloud/v1` — fetches `quran-uthmani` (Arabic) + `en.sahih` (English) editions
4. **Validation**: Console assertion verifies total ayah count = 6,236 on every page load

---

## 📚 Quran API Details

The app uses the [AlQuran Cloud API](https://alquran.cloud/api):

| Endpoint | Purpose |
|----------|---------|
| `/v1/ayah/{surah}:{ayah}/editions/quran-uthmani,en.sahih` | Fetch single ayah (Arabic + English) |
| `/v1/surah/{number}/editions/quran-uthmani,en.sahih` | Fetch complete surah |

The `quran-uthmani` edition provides the text as printed in the King Fahd Complex Mushaf.

---

## 🤝 Contributing

Contributions welcome — especially:
- 🌐 Additional translations (Urdu, French, Turkish, Malay, etc.)
- ♿ Accessibility improvements
- 🎨 Additional themes
- 🔊 Audio recitation integration
- 📖 Tafsir (exegesis) overlay

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<p align="center">
  <sub>بِسْمِ ٱللَّهِ ٱلرَّحْمَٰنِ ٱلرَّحِيمِ</sub><br>
  <sub>Built with ❤️ by <a href="https://github.com/SiteQ8">@SiteQ8</a> — Ali AlEnezi 🇰🇼</sub><br>
  <sub>"إِنَّ مَعَ الْعُسْرِ يُسْرًا" — الشرح 94:5</sub>
</p>
