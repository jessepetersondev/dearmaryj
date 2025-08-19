# My Cannabis Journal — One Puff Rating
A lightweight, privacy-first cannabis journal. Data is stored locally (browser `localStorage`).

## Features
- Add entries with date, strain/product, method, notes.
- **One Puff Rating** slider (1.0–10.0, step 0.1) with dynamic display.
- Ratings rendered as marijuana leaf icons + numeric value.
- Edit and delete entries.
- No backend required. Deploy anywhere (GitHub Pages, Netlify, static hosting).

## Run Locally
Open `index.html` in any modern browser.

## Deploy to GitHub Pages
1. Create a new repo and add these files.
2. Push to `main` branch.
3. In repo Settings → Pages: set Source to `main` / root.
4. Visit the provided Pages URL.

## Notes
- Leaf icons are simple SVGs bundled in `assets/`.
- Because storage is local to the browser, entries don't sync across devices.
