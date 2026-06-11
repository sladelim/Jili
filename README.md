# Jili — PWA

A spaced repetition app for clinical scenarios. Works fully offline once installed.

## How to install on your phone

### iPhone (Safari)
1. Open Safari and navigate to your hosted URL
2. Tap the **Share** button (box with arrow) at the bottom
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — the app icon will appear on your home screen

### Android (Chrome)
1. Open Chrome and navigate to your hosted URL
2. Tap the **⋮ menu** (top right)
3. Tap **"Add to Home screen"** or **"Install app"**
4. Tap **Add**

## Hosting options (free)

### Option A — Netlify Drop (easiest, 2 minutes)
1. Go to https://app.netlify.com/drop
2. Drag the entire `Jili` folder onto the page
3. Netlify gives you a free HTTPS URL instantly

### Option B — GitHub Pages
1. Create a GitHub repo, upload all files
2. Go to Settings → Pages → Deploy from main branch
3. Your URL: `https://<username>.github.io/<repo>/`

## Files
- `index.html` — main app
- `manifest.json` — PWA metadata (name, icon, theme)
- `sw.js` — service worker (offline caching)
- `icon-192.png` / `icon-512.png` — home screen icons

## Features
- Branching multi-step clinical scenarios
- SM-2 spaced repetition (Again / Hard / Good / Easy)
- Multiple choice and open-ended question types
- Activity heatmap and per-deck progress stats
- Import / export decks as JSON (share with colleagues)
- Fully offline after first load
- Data stored in localStorage on your device
