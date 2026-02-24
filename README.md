# 🤰 40Weeks – Pregnancy Week-by-Week Guide

An interactive, privacy-friendly pregnancy week guide as a **single HTML file** – no backend, no cookies, no tracking.

Enter your due date and get a personalized week-by-week guide with fruit size comparisons, development info, and tips.

🇩🇪 **Deutsch** | 🇬🇧 **English** – more languages welcome!

## ✨ Demo

👉 **[Live Demo 🇬🇧](https://Hubref.github.io/40Weeks/?et=2026-10-26&lang=en)** | **[Live Demo 🇩🇪](https://Hubref.github.io/40Weeks/?et=2026-10-26&lang=de)**

## 🎯 Features

- 🍇➡️🍉 **40 weeks** with fun fruit & size comparisons
- 👶 **Development info** for each week (medically sourced)
- 👩 **Mom tips** – what's happening in the body
- 💡 **Fun facts** for every week
- 📍 **Automatic highlighting** of the current week
- ⏳ **Live countdown** to due date
- 📅 **Personalized dates** for each week
- 🔗 **Shareable link** – due date passed as URL parameter
- 📤 **Share box** with WhatsApp, Telegram & email buttons
- 🌍 **Multi-language** (DE/EN) with auto-detection & switcher
- 🎨 Inline SVG illustrations for each fruit
- 📱 **Responsive** – works on mobile, tablet & desktop
- 🔐 **Zero tracking** – no cookies, no analytics, no data stored

## 🌍 Languages

Currently supported:
- 🇩🇪 Deutsch (German)
- 🇬🇧 English

The language is detected automatically from the browser, or set via URL parameter `?lang=de` / `?lang=en`. A language switcher is also available on the page.

### Adding a new language

All translations live in the `<script>` section of `index.html`. To add e.g. French:

1. Add `'fr'` to the `LANGS` array
2. Add `L.fr = { ... }` with all UI strings (copy `L.en` as template)
3. Add `W_LANG.fr = [ ... ]` with 40 week entries (copy `W_LANG.en` as template)
4. That's it – the language switcher updates automatically!

Pull requests for new languages are very welcome! 🙌

## 🔐 Privacy

- **No cookies**
- **No tracking / analytics**
- **No data stored or sent anywhere**
- The due date only exists in the URL parameter and the user's browser
- Works completely offline

## 🚀 Usage

### Option 1: GitHub Pages (recommended)
1. Fork this repository
2. Enable GitHub Pages (Settings → Pages → Source: `main`)
3. Open `https://YOUR-USERNAME.github.io/40Weeks/?et=YYYY-MM-DD`

### Option 2: Local
1. Download `index.html`
2. Open in browser: `file:///path/to/index.html?et=2026-10-26`

### Option 3: Self-hosted
Just put `index.html` on any web server. No dependencies, no build step.

## 📖 URL Parameters

| Parameter | Format | Example | Description |
|-----------|--------|---------|-------------|
| `et` | `YYYY-MM-DD` | `2026-10-26` | Due date |
| `lang` | `de`, `en` | `en` | Language (optional, auto-detected) |

Without `?et=` a landing page with a date input is shown.

**Example:** `https://Hubref.github.io/40Weeks/?et=2026-10-26&lang=en`

## 📚 Sources

Medical information is based on:

- [familienplanung.de](https://www.familienplanung.de) – BZgA (German Federal Centre for Health Education)
- [Embryotox](https://www.embryotox.de) – Charité Berlin
- [ACOG](https://www.acog.org/womens-health/pregnancy) – American College of Obstetricians and Gynecologists
- [NHS UK](https://www.nhs.uk/pregnancy/week-by-week/) – Week-by-week Guide
- [Cleveland Clinic](https://my.clevelandclinic.org/health/articles/7247-fetal-development) – Fetal Development
- Moore, Persaud & Torchia: *The Developing Human*, 11th Ed., Elsevier 2020

## ⚕️ Disclaimer

**This is not medical advice.** All information is carefully researched but provided without warranty. It does not replace a visit to your doctor or midwife. Every pregnancy is unique – consult your healthcare provider with any questions or concerns.

## 🤝 Contributing

Contributions are welcome! Especially:
- 🌍 Translations into more languages
- 🎨 Better SVG illustrations
- 📝 Medical corrections (with source please)
- ♿ Accessibility improvements

Just open a pull request or create an issue.

## 📄 License

[MIT](LICENSE) – Free to use, even commercially.

---

*Made with ❤️ for expecting parents.*
