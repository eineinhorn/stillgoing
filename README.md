# Stillgoing — Streak PWA

A small installable, offline-capable streak tracker designed for phones and GitHub Pages.

## Features
- Ongoing streaks start on creation and count calendar days automatically; no daily check-in.
- End a streak whenever you want; ended streaks remain in Finished.
- Delete any streak.
- Optional day-goal streaks show progress toward a chosen number of days (they do not auto-end).
- Data stored locally in the browser.

## Publish on GitHub Pages
1. Create a GitHub repository (for example `stillgoing`).
2. Upload **all four app files** (`index.html`, `manifest.json`, `sw.js`, `icon.svg`) to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Wait for the Pages URL, typically `https://YOUR-USERNAME.github.io/REPO-NAME/`.
6. Open that URL in your phone's browser. On iPhone: Safari → Share → **Add to Home Screen**. On Android: Chrome menu → **Install app** or **Add to Home screen**.

## Notes
- HTTPS is required for PWA installation and service workers; GitHub Pages supplies it.
- Your streaks are stored on that device/browser. Clearing site data can erase them. Use a browser/device backup if needed.
- The day count includes the start date as day 1. Goal progress is based on calendar dates.
