# Daily Quranic Ayah App

A beautiful, responsive web application that displays a new Quranic Ayah every day with authentic Arabic text and English translation.

## ✨ Features

- 📖 **Daily Ayah**: Different authentic Quranic Ayah each day
- 🌙 **Dark Mode**: Beautiful dark theme support
- 🎨 **6 Themes**: Light, Dark, Sunset, Forest, Ocean, Midnight
- 🌍 **Bilingual**: Arabic and English interface **pending**
- 📱 **Fully Responsive**: Works on all devices
- 💡 **Daily Dua**: Islamic supplication with each Ayah
- ⚡ **Zero Dependencies**: Pure HTML, CSS, JavaScript
- 🚀 **Fast & Lightweight**: Instant loading
- 📊 **Visit Counter**: Track your visits


## 🚀 Getting Started

### Option 1: Direct Deployment to GitHub Pages

1. Fork this repository
2. Rename to `daily-quran-Ayah` (for GitHub Pages)
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose main branch
6. Your site is live at: `https://siteq8.github.io/daily-Ayah`

### Option 2: Local Testing

Simply open `index.html` in your browser - no server required!

## 📁 Repository Structure

```
daily-quran-Ayah/
├── index.html          # Main application
├── README.md           # This file
└── docs/              # GitHub Pages folder (optional)
    └── index.html     # Copy of main for GitHub Pages
```

## 🎯 How to Use

1. **Daily Ayah**: Opens automatically - same Ayah for all users each day
2. **Random Ayah**: Click "Another Ayah" button to see a random Ayah
3. **Copy**: Click "Copy" to copy Ayah to clipboard
4. **Share**: Click "Share" to share Ayah (on supported devices)
5. **Language**: Toggle between Arabic and English
6. **Theme**: Choose from 6 beautiful themes
7. **Dark Mode**: Perfect for night reading

## 🔧 Customization

### Adding More Ayahs

Edit the `AyahS` object in the script:

```javascript
const AyahS = {
    SURAH_NUMBER: {
        ar: "اسم السورة",
        ref: "السورة X:Y",
        Ayahs: [
            {
                v: Ayah_NUMBER,
                ar: "النص العربي الكامل",
                en: "Complete English translation"
            }
        ]
    }
};
```

### Adding More Duas

Edit the `QUOTES` array:

```javascript
const QUOTES = [
    {ar: "الدعاء العربي", en: "English supplication"}
];
```

## 🎨 Themes

- **Light** - Soft blue and white (default)
- **Dark** - Dark blue background
- **Sunset** - Warm orange and red tones
- **Forest** - Green nature theme
- **Ocean** - Cool blue theme
- **Midnight** - Deep dark blue theme

## 📱 Browser Support

- Chrome/Chromium
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🙏 Islamic Authenticity

All Quranic Ayahs are authentic from the Holy Quran with verified English translations. Duas are from authentic Islamic sources.

## 📄 License

Free to use and modify. Perfect for:
- Islamic education websites
- Personal daily reflection
- Community groups
- Quran study apps

## 🤝 Contributing

Feel free to:
- Add more authentic Quranic Ayahs
- Improve translations
- Add new languages
- Report bugs
- Suggest themes

## 👨‍💻 Developer

Created by **@SiteQ8**

## 📞 Support

For issues or suggestions, please create an issue in the repository.

## ✅ Features Checklist

- ✅ Arabic & English bilingual
- ✅ 6 Premium themes
- ✅ Dark mode
- ✅ Mobile responsive
- ✅ Copy to clipboard
- ✅ Share functionality
- ✅ Visit counter
- ✅ Authentic Quranic Ayahs
- ✅ Islamic duas
- ✅ No dependencies
- ✅ Fast loading
- ✅ Beautiful animations

---

**حفظك الله - May Allah protect you**

"Indeed, with hardship comes ease" - Quran 94:5
