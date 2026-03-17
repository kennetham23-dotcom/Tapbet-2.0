# ⚡ Tap Buzzer Arena

A fast-paced, competitive real-time tapping game where two players race to tap the golden buzzer the most times in 60 seconds. The highest tapper wins the staked amount.

![Game Preview](https://img.shields.io/badge/Status-Ready%20to%20Deploy-gold?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-Single%20File-orange?style=for-the-badge)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-green?style=for-the-badge)

## 🎮 Features

- **60-Second Tapping Challenge** — Race against an opponent in real time
- **Simulated Matchmaking** — Automatic opponent search with animated status
- **Stake System** — Set your wager before each match
- **Premium Multipliers** — x1 / x2 / x3 / x4 multiplier system (Silver, Bronze, Gold tiers)
- **Deposit & Withdraw** — Balance management via mobile money
- **Dark Mode / Light Mode** — Toggle between themes
- **Glassmorphism UI** — Liquid glass hover effects throughout
- **Fully Responsive** — Works on mobile and desktop
- **Zero Dependencies** — Pure HTML, CSS, and vanilla JavaScript

## 🚀 Deploy to GitHub Pages

### Option 1: Via GitHub Web Interface

1. Create a new repository on [github.com](https://github.com/new)
2. Name it `tap-buzzer-arena` (or any name you like)
3. Click **"uploading an existing file"**
4. Upload `index.html`
5. Go to **Settings → Pages**
6. Under **Source**, select `main` branch and `/ (root)`
7. Click **Save** — your site will be live at `https://yourusername.github.io/tap-buzzer-arena`

### Option 2: Via Git CLI

```bash
# Initialize and push
git init
git add index.html README.md
git commit -m "Initial commit: Tap Buzzer Arena"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/tap-buzzer-arena.git
git push -u origin main

# Then enable GitHub Pages in repo Settings → Pages
```

### Option 3: Drag & Drop on GitHub

1. Create a new repo on GitHub
2. Drag `index.html` directly into the repository file list
3. Enable GitHub Pages in Settings

## 📁 File Structure

```
tap-buzzer-arena/
└── index.html       ← The entire game (single file)
└── README.md        ← This file
```

## 🎯 How to Play

1. **Set Stake** — Tap "SET STAKE" and enter your wager amount
2. **Find Match** — Tap "⚡ FIND MATCH" to search for an opponent
3. **Tap the Buzzer** — Once matched, tap the golden buzzer as fast as possible!
4. **Win** — The player with the most taps after 60 seconds wins the stake

## ⭐ Premium Multipliers

| Plan   | Price    | Multiplier | Effect                        |
|--------|----------|------------|-------------------------------|
| Silver | $4.99/mo | x2         | Doubles each tap for 30s      |
| Bronze | $8.99/mo | x3         | Triples tap value             |
| Gold   | $14.99/mo | x4        | Quadruples tap value          |

## 🛠️ Customization

Open `index.html` and edit the `<script>` section:

```js
let balance = 250.00;  // Starting balance
// Opponent speed (lower = faster opponent)
const taps = Math.floor(Math.random() * 3) + 2;  // taps per 500ms
```

---

Built with pure HTML, CSS & JavaScript. No frameworks, no build tools, no backend required.
