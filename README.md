# Fiber Optic CC — install guide

## Put it online (GitHub Pages, free)
1. Make a free account at github.com.
2. Click **+ → New repository**. Name it `fiber-cc`, set it **Public**, click **Create repository**.
3. On the new repo page click **uploading an existing file**. Drag in everything from this zip
   (index.html, manifest.webmanifest, sw.js, README.md, and the `icons` folder). Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Branch* pick **main** and **/(root)**, click **Save**.
5. Wait 1–2 minutes. Your app is live at:
   `https://YOUR-USERNAME.github.io/fiber-cc/`

## Install on a phone
- **Android (Chrome):** open the link → ⋮ → **Install app** (or Add to Home screen).
- **iPhone (Safari):** open the link → Share → **Add to Home Screen**.

Open it once with signal. After that it works with no service.

## Updating it later
1. Upload the changed file(s) to the repo (same names, overwrite).
2. In `sw.js`, change `fcc-v1` to `fcc-v2` (then v3, etc.) and commit.
3. Phones pick up the new version the next time they open the app with signal (may take two launches).

## Google Play later
Go to pwabuilder.com, paste your GitHub Pages link, and choose **Android**. It builds the
package for the Play Store, or an APK you can sideload on crew phones.
