# Focus & Form — Workout Tracker

A 3-day Upper / Lower / Full Body split tracker. Installs as an app on your phone, works offline, no accounts or backend needed. All data is saved in your phone's browser storage.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `workout-tracker`) — public or private both work for Pages.
2. Upload these files to the repo root: `index.html`, `manifest.json`, `sw.js`, and the `icons/` folder.
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch".
5. Set **Branch** to `main` (or `master`) and folder to `/ (root)`. Save.
6. Wait 1–2 minutes, then refresh the Pages settings page — it will show your live URL, something like:
   `https://<your-username>.github.io/workout-tracker/`

## Install on your phone

**iPhone (Safari):**
1. Open your GitHub Pages URL in Safari.
2. Tap the Share icon (square with arrow up).
3. Tap "Add to Home Screen" → Add.

**Android (Chrome):**
1. Open your GitHub Pages URL in Chrome.
2. Tap the ⋮ menu → "Add to Home screen" (or you may see an automatic "Install app" prompt).
3. Confirm.

It'll now appear as an app icon on your home screen, opens full-screen without browser bars, and works without signal once loaded once.

## Notes

- Data is stored only on this device/browser via `localStorage`. Clearing Safari/Chrome site data will erase your logs.
- No login, no server, no ongoing costs.
