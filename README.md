# Ethan's North Pole Tree Countdown

A tiny static website / PWA for Ethan's Christmas tree countdown.

## Fastest GitHub Pages setup

1. Create a new public GitHub repository, for example `ethan-north-pole`.
2. Upload **all files and folders from this ZIP** to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then Save.
6. Wait about 1–2 minutes. GitHub will show the public site URL.
7. Open that URL in Safari on Ethan's iPad.
8. Tap **Share → Add to Home Screen → Add**.

The site is fully static and uses no external libraries.

## What it does

- Live countdown to November 1, 2026 at 12:00 AM using the iPad's local time.
- One mission per day from October 9 through October 31.
- Future missions stay hidden.
- Mission completion is stored on the device using localStorage.
- On November 1 the screen automatically becomes TREE AUTHORIZED.
- Can be installed to the iPad Home Screen and works offline after the first load.

## Important

If you change files later, GitHub Pages may take a minute to refresh.  
If an installed Home Screen version seems stale after an update, open the site once in Safari and refresh.
