# DONALD — Pump Intelligence

Real-time crypto pump & dump tracker. Spot new coins early, track your bankroll live.

---

## 🔗 Your Live URL (once deployed)

**`https://justinbellxr-ops.github.io/donald/`**

Open this on iPhone → tap **Share** → **Add to Home Screen** → DONALD icon appears.

---

## 🚀 Deploy to GitHub Pages (5 min)

### Step 1 — Create the repo
1. Go to [github.com](https://github.com) → sign in as **justinbellxr-ops**
2. Click **New repository**
3. Name it exactly: **`donald`**
4. Set to **Public**
5. Click **Create repository**

### Step 2 — Upload all files
1. On the new repo page → click **"uploading an existing file"**
2. Drag and drop ALL of these:
   - `index.html`
   - `manifest.json`
   - entire `icons/` folder (all 6 PNG files)
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to repo **Settings** → **Pages** (left sidebar)
2. Under **Source** → select **Deploy from a branch**
3. Under **Branch** → select **main** → **/ (root)**
4. Click **Save**

### Step 4 — Wait 60 seconds
Visit: **`https://justinbellxr-ops.github.io/donald/`**

Real data loads instantly. No Node, no server, no setup.

---

## 📱 Add to iPhone Home Screen

1. Open Safari on iPhone
2. Go to `https://justinbellxr-ops.github.io/donald/`
3. Tap the **Share** button (box with arrow)
4. Scroll down → tap **"Add to Home Screen"**
5. Tap **"Add"** — DONALD icon appears on your home screen
6. Opens full-screen, no browser chrome — just like a native app

---

## 📁 File Structure

```
donald/
├── index.html        ← The entire app
├── manifest.json     ← PWA config (home screen install)
├── README.md
└── icons/
    ├── icon-76.png
    ├── icon-120.png
    ├── icon-152.png
    ├── icon-180.png  ← iPhone home screen icon
    ├── icon-192.png  ← Android home screen icon
    └── icon-512.png  ← PWA splash
```

---

## Features
- **Real live data** from DexScreener — ETH, BSC, Solana, Base, Arbitrum, Polygon
- **Refreshes every 20s** automatically
- **Bankroll tracker** — tap the $ number, type your size, hit I'm In
- **Live bankroll chart** — grows/falls in real-time
- **Exit signals** — color-coded, plain language
- **Watchlist** — saved locally on your device
- **Mobile-first** — 3-tab navigation on iPhone
- **PWA** — installs to home screen, runs full-screen
