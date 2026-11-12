# Madame Gihan 1.0 — beginner setup

## What you have
- `index.html` — the complete working app
- `manifest.webmanifest` — lets you add Gihan to your phone's Home Screen
- `icon.svg` — temporary beaker icon
- `sw.js` — basic offline caching after first load

## Put Gihan on GitHub (free)
1. Sign in at https://github.com or create a free account.
2. Select the **+** menu (top right) > **New repository**.
3. Name it `gihan-app`, select **Public**, then select **Create repository**. Do not upload personal log backups to this public repository.
4. Open your new repository, select **Add file** > **Upload files** (or the **uploading an existing file** link).
5. Unzip the Gihan download first. Upload the FOUR files inside the `gihan-v1` folder, not the folder itself. Commit the changes.
6. Go to **Settings** > **Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select `main`, folder `/(root)`, then **Save**.
7. Wait a few minutes and revisit **Settings** > **Pages**. Your address will look like `https://YOUR-USERNAME.github.io/gihan-app/`.
8. Open that address in Safari on your iPhone. Tap **Share** > **Add to Home Screen** > **Add**.

## How to test
1. Enter a milliliter amount and tap **Log ml**.
2. Confirm the clock counts up from the latest entry.
3. Set an interval (for example 1 hour 50 minutes) and save.
4. Try recording another entry early to see Gihan's warning; choose Cancel or Record anyway.
5. Try **5 minutes ago** and an exact date/time to test backdated entries.
6. Check today's total, history, delete, and **Export backup**.
7. Close and reopen the app: your entries should remain on that same device/browser.

## Important limitations
- Version 1.0 does NOT send background notifications or work as a native Apple Watch app.
- Every device/browser has separate local records. No accounts or cross-device sync.
- Browser storage can be cleared. Export backups regularly and keep them somewhere safe (e.g. Dropbox).
- The timer tracks your chosen interval; it does NOT establish that another drink or dose is safe.
- The beaker icon is temporary; we can replace it with a licensed/authorized portrait later.
- If you update files on GitHub, the service worker may need a reload before the newest version appears.

## Updating later
Upload the revised files to the SAME `gihan-app` repository and commit. GitHub Pages will update the existing link. Before testing major updates, export a backup of your entries.
