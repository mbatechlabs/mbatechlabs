<div align="center">

<img src="icon.png" alt="Quran Word Puzzle" width="96" height="96" style="border-radius:22px" />

# MBA Tech Labs

### Official website & flagship app showcase — **Quran Word Puzzle**

[![Website](https://img.shields.io/badge/Live-Website-0F4D3A?style=for-the-badge)](https://mbatechlabs.example.com)
[![Google Play](https://img.shields.io/badge/Google_Play-Quran_Word_Puzzle-A7F3D0?style=for-the-badge&logo=googleplay&logoColor=0F4D3A)](https://play.google.com/store/apps/details?id=com.mba.quranpuzzle)
[![Made with HTML & CSS](https://img.shields.io/badge/Made_with-HTML_%26_CSS-C9A06A?style=for-the-badge)](#)

</div>

---

A lightweight, dependency-free static site for **MBA Tech Labs**, the studio behind **Quran Word Puzzle** — a word-puzzle game for memorizing the Holy Quran in Arabic, English & Urdu.

This repo also satisfies three Google requirements for the app:

- 🌐 **Developer website** (required by AdMob app verification)
- 🔒 **Privacy Policy** (required by the Google Play listing)
- 📄 **app-ads.txt** (lifts AdMob's *limited ad serving* cap)

---

## 📂 Repository structure

```
.
├── index.html            # MBA Tech Labs landing page (features Quran Word Puzzle)
├── privacy-policy.html   # Privacy policy
├── app-ads.txt           # AdMob ownership verification  (must stay at root)
├── icon.png              # App icon used on the landing page
├── feature-graphic.png   # Spare asset (optional)
└── README.md
```

> ⚠️ Keep every file **flat at the repo root**. `index.html` loads `icon.png`
> by relative path, and `app-ads.txt` **must** be reachable at `/app-ads.txt`.

---

## 🚀 Deploy with GitHub Pages

1. Create a **public** repository — name it `<your-username>.github.io` for a root site, or any name for a project site.
2. Upload all files (**Add file → Upload files → Commit**), keeping them at the root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source: Deploy from a branch**, **Branch: `main` / `/(root)`** → **Save**.
5. Wait ~1–2 minutes. Your site goes live at:
   - Root site: `https://<your-username>.github.io/`
   - Project site: `https://<your-username>.github.io/<repo-name>/`

### Using a custom (sub)domain
- Add your domain in **Settings → Pages → Custom domain** (e.g. `mbatechlabs.yourdomain.com`).
- Create a `CNAME` DNS record pointing the subdomain to `<your-username>.github.io`.
- Enable **Enforce HTTPS**.

---

## ✅ Verify it works

Open each URL and confirm it loads:

| URL | Expected |
|-----|----------|
| `https://YOUR-DOMAIN/` | Landing page |
| `https://YOUR-DOMAIN/privacy-policy.html` | Privacy policy |
| `https://YOUR-DOMAIN/app-ads.txt` | The single line below |

```text
google.com, pub-8785614447841587, DIRECT, f08c47fec0942fa0
```

---

## 🔗 Wire it up (3 places)

1. **Play Console → Store listing → Store settings → Contact details → Website** → `https://YOUR-DOMAIN`
2. **Play Console → Policy → App content → Privacy policy** → `https://YOUR-DOMAIN/privacy-policy.html`
3. **AdMob → Apps → Quran Word Puzzle → app-ads.txt → Check for updates**

> The domain set as your Play **developer website** must **exactly match** the host serving `app-ads.txt` — that's how AdMob finds the file.

---

## 🎮 About Quran Word Puzzle

| | |
|---|---|
| 🧩 **Three modes** | Words · Choice · Cipher |
| 🌍 **Dual Language** | Arabic (RTL) · English |
| 📖 **1000+ verses** | Hand-picked, with translations |
| 🏆 **Leaderboard** | Global ranking via Google Play Games |
| 🌙 **Daily challenge** | A fresh verse every day |
| 💸 **Free** | Ad-supported, no paywalls |

<div align="center">

[**▶ Download on Google Play**](https://play.google.com/store/apps/details?id=com.mba.quranpuzzle)

</div>

---

## 🛠 Customize

- **Contact email** — `mbatechlabs@gmail.com` in `index.html` & `privacy-policy.html` (find & replace).
- **Live badge URL** — replace `https://mbatechlabs.example.com` at the top with your real domain.
- **Colors / copy** — edit the inline `<style>` and text in `index.html`.

---

<div align="center">

© 2026 **MBA Tech Labs**. All rights reserved.

</div>
