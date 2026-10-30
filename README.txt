# Winter Arc Plus

A lightweight, installable web app (PWA) for daily habits, morning routine, study focus and fitness consistency.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser. The core tracker works locally.
3. For install/offline PWA features, host the folder on an HTTPS static host.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a new public repository.
2. Upload `index.html`, `manifest.json`, `icon.svg`, and `sw.js` to the repository root.
3. Open Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Wait for the published HTTPS URL. Open it on your phone and choose Add to Home Screen / Install.

## Data and privacy
- Habits, routine steps, and progress are stored in this browser using localStorage.
- Data is not synced between devices and is not uploaded to a server.
- Use Progress → Export backup to save a JSON backup.
- Import backup restores a previously exported JSON file.

## Customize
Open `index.html` in a code editor. Edit the `defaultHabits` and `defaultRoutine` arrays to change the starting checklist and morning schedule.
