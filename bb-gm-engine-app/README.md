# Brimstone GM Engine — Web App

Packaged as a Progressive Web App (PWA): works offline, installable on phones and desktops, no account required.

## Install
- **Host it** (GitHub Pages, itch.io, any static host) and open the URL — or open `index.html` locally to use it un-installed.
- **Phone:** open the hosted URL → browser menu → **Add to Home Screen / Install App**.
- **Desktop:** Chrome/Edge show an install icon in the address bar.

## Files
- `index.html` — the entire app, single file
- `manifest.webmanifest` — app metadata
- `sw.js` — offline caching service worker
- `icon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — icons

*Note: service workers require hosting over HTTPS (or localhost). Opened as a plain file, the app still works fully — it just won't install or cache.*
