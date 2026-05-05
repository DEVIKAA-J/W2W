# 🌙 W2W - What To Watch

> *Find the perfect movie or show for tonight, based on your mood.*

A cozy, mood-driven movie & TV discovery app powered by the [TMDB API](https://www.themoviedb.org/). No accounts, no algorithms - just pick a vibe and get personalized recommendations in seconds.

---

## ✨ Features

- **Mood-first discovery** — Choose how you're feeling tonight (happy, cozy, thrilled, romantic, etc.) and the app narrows down genres to match
- **Genre blend picker** — Select a curated genre combo like *Psychological Thriller*, *Cozy Drama*, or *Animated Delight*
- **Flexible filters** — Filter by language (English, Hindi, Malayalam, Tamil, Korean, Japanese), content type (Movies, TV Shows, Anime), and duration
- **Live TMDB results** — Fetches real-time data including posters, ratings, and descriptions
- **Guided 3-step wizard** — A clean, step-by-step UI walks you from mood → genre → results
- **Zero dependencies** — Pure HTML, CSS, and vanilla JavaScript. No frameworks, no build step

---

## 🚀 Getting Started

Since this is a single-file app with no build process, getting started is as simple as:

```bash
# Clone the repo
git clone https://github.com/your-username/w2w.git
cd w2w

# Open in your browser
open index.html
```

Or just drag `index.html` into any browser — it works immediately.

---

## 🗂️ Project Structure

```
w2w/
└── index.html    # The entire app — HTML, CSS, and JS in one file
```

---

## 🔑 API Key

This app uses the [TMDB Discover API](https://developer.themoviedb.org/reference/discover-movie). A public API key is included for demo purposes.

To use your own key:

1. Create a free account at [themoviedb.org](https://www.themoviedb.org/)
2. Go to **Settings → API** and request a key
3. Replace the key at the top of the `<script>` block in `index.html`:

```js
const API_KEY = 'your_tmdb_api_key_here';
```

---

## 🎭 Mood → Genre Mapping

| Mood | Available Genre Blends |
|---|---|
| ☀️ Light & Happy | Rom-Com, Adventure Comedy, Family Fun, Animated Delight |
| 🕯️ Relaxed & Cozy | Cozy Drama, Nature & Doc, Fantasy Adventure, Rom-Com |
| 🌧️ Emotional | Emotional Drama, Romantic Melodrama, War & History, Biopic |
| 🌑 Thrill & Dark | Action Thriller, Horror Thriller, Crime Mystery, Psychological Thriller |
| 🌹 Romantic | Rom-Com, Romantic Melodrama, Dramedy, Fantasy Romance |
| 🚀 Mind-blowing Sci-Fi | Sci-Fi Adventure, Sci-Fi Thriller, Sci-Fi Drama, Fantasy Action |
| 😂 Fun / Comedy Night | Adventure Comedy, Rom-Com, Animated Delight, Action Comedy |

---

## 🛠️ Tech Stack

| Layer | Details |
|---|---|
| **UI** | Vanilla HTML5 + CSS3 |
| **Fonts** | Cormorant Garamond + Jost (Google Fonts) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Data** | [TMDB Discover API v3](https://developer.themoviedb.org/reference/discover-movie) |
| **Hosting** | Any static host (GitHub Pages, Netlify, Vercel) |

---

## 🌐 Deploying

## 🌐 Live Demo

**[→ w2wtonight.netlify.app](https://w2wtonight.netlify.app/)**

---

## 🚀 Deploy Your Own

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start)

### Netlify
1. Fork this repo
2. Go to [netlify.com](https://netlify.com) → **Add new site → Import from Git**
3. Select your fork — no build settings needed
4. Hit **Deploy** — live in seconds

### GitHub Pages
1. Go to **Settings → Pages**
2. Set source to `main` branch, `/ (root)`
3. Live at `https://your-username.github.io/w2w/`

### Netlify Drop *(quickest)*
Drag `index.html` into [app.netlify.com/drop](https://app.netlify.com/drop) — done.

## 📸 Preview

<img width="800" height="350" alt="Screenshot (421)" src="https://github.com/user-attachments/assets/d70f4320-ec1a-41a6-83c3-5921afcc3c73" /> <img width="800" height="350" alt="Screenshot (422)" src="https://github.com/user-attachments/assets/8bbf59a7-d137-4948-aad7-76964736876b" /> <img width="800" height="350" alt="Screenshot (425)" src="https://github.com/user-attachments/assets/d97e348a-f016-4c88-ac1b-0d0219511df9" />
<img width="800" height="350" alt="Screenshot (426)" src="https://github.com/user-attachments/assets/ab5f5273-d56a-4728-8ed2-21b886980cd7" />




## 🤝 Contributing

Pull requests are welcome! Here are some ideas for improvements:

- [ ] Add "Watch Now" links (JustWatch integration)
- [ ] Support streaming platform filters (Netflix, Prime, etc.)
- [ ] Add a "Surprise me" random pick mode
- [ ] Dark/light theme toggle
- [ ] Save favourites to localStorage

---

## 📄 License

[MIT](LICENSE) — free to use, remix, and share.

---

<p align="center">
  Powered by <a href="https://www.themoviedb.org">TMDB</a> &nbsp;·&nbsp;
  Built with 🌿 and vanilla JS
</p>
