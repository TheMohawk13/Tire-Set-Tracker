# Tire Set Tracker

A single-page tracker for tire sets used across a race weekend (dry and wet allocation, sessions, laps, saved events).
Plain HTML, CSS and JavaScript with no build step. Data is stored in each person's own browser (localStorage).

Created by Ryne Hoover Transportation.

## Files (upload all of them to the repository root)

- `index.html` - the app
- `manifest.webmanifest` - lets phones install it like an app
- `sw.js` - saves the app for offline use
- `icon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` - home screen icons

## Put it on GitHub Pages

1. Create a new **public** repository on GitHub (for example `tire-tracker`).
2. Upload every file in this folder to the repository root (Add file > Upload files), then commit.
3. Go to **Settings > Pages**. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/tire-tracker/`.

## Install it on a phone

- iPhone: open the link in Safari, tap Share, then **Add to Home Screen**.
- Android: open the link in Chrome, tap the menu, then **Install app** or **Add to Home Screen**.

Open it once with a connection so it can save itself for offline use.
iPhones save the icon at the moment you add it, so delete any old shortcut and add it again to see a new icon.

## Updating

Upload the changed files, then raise the version number in `sw.js` (for example `tire-tracker-v6` to `tire-tracker-v7`)
so phones fetch the new version.
