# 🥛 Milk Tracker

**Developed by Ajeet Parmar**

A simple offline Progressive Web App to track daily milk (Cow / Buffalo), quantity, cost, monthly & yearly reports, and PDF export.

## Features

- Daily entry with date picker
- Cow / Buffalo / None
- Quantity dropdown (250ml – 5L)
- Locked price from Settings
- **Auto daily fill** – missing days filled automatically when you open the app (works offline)
- Edit & Delete any entry
- Swipe left/right to change tabs
- Monthly & Yearly summary
- PDF export (1 month = 1 page, page numbers, developer name on every page)
- JSON backup / restore
- Fully offline, data stays on your device only
- Installable on mobile (Add to Home Screen)

## Privacy

All data is stored in **localStorage** on the user’s device.  
If you share the app files with someone else, they start with a **blank** app. Your data never leaves your phone.

## How to put on GitHub & install

1. Create a new **public** repository on GitHub (e.g. `milk-tracker`)
2. Upload **all files** from this folder (including `icons/`)
3. Go to **Settings → Pages**
4. Source: Deploy from a branch → `main` → `/ (root)` → Save
5. After 1–2 minutes open:  
   `https://YOUR_USERNAME.github.io/milk-tracker/`
6. On mobile Chrome/Safari → menu → **Add to Home Screen / Install app**

## Files

```
index.html
manifest.json
sw.js
README.md
LICENSE
icons/
  icon.svg
  icon-192.png
  icon-512.png
```

## License

MIT
