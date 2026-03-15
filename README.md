# EdgeFlow — iOS Install Guide

## What's in this package

| File | Purpose |
|------|---------|
| `index.html` | The complete app |
| `manifest.json` | Makes it installable as a PWA |
| `sw.js` | Service worker (offline support) |
| `icon-192.png` | App icon |
| `icon-512.png` | App icon (high-res) |

---

## How to install on your iPhone

### Option A — Host for free on GitHub Pages (recommended)
1. Create a free account at **github.com**
2. Create a new repository (e.g. `edgeflow`)
3. Upload all 5 files to the repo root
4. Go to **Settings → Pages → Source: main branch / root**
5. GitHub gives you a URL like `https://yourname.github.io/edgeflow`
6. Open that URL in **Safari** on your iPhone
7. Tap the **Share button** (box with arrow) → **"Add to Home Screen"**
8. Tap **"Add"** — EdgeFlow now appears as an app icon!

### Option B — Netlify Drop (instant, no account needed)
1. Go to **netlify.com/drop** in your browser
2. Drag the entire `edgeflow` folder onto the page
3. Netlify gives you a live URL instantly
4. Open that URL in Safari on iPhone → Share → Add to Home Screen

### Option C — Use a local server (for testing)
If you have Node.js: run `npx serve .` inside the edgeflow folder, then open your local IP in Safari.

---

## Features

- **Sessions tab** — Live open/closed status for Sydney, Tokyo, London, New York with overlap detection and toast alerts
- **Checklist tab** — 12-point ICT/Smart Money pre-trade checklist with progress bar
- **Journal tab** — Log trades with pair, direction, entry/exit, SL/TP, P&L, result & notes. Win rate + P&L stats auto-calculated. Persists across sessions via localStorage.

---

## Notes
- Push notifications are available on iOS 16.4+ after adding to Home Screen
- All trade data is stored locally on your device
- Works offline once installed

