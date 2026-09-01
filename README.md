# CEREC Learning System — GitHub Pages

This folder is ready to publish with GitHub Pages.

## Upload these items to the root of the repository
- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `icons/`

## Turn on GitHub Pages
1. Create a GitHub repository, for example `cerec-learning`.
2. Upload all files and the `icons` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**.
6. Click **Save**.
7. Wait for GitHub Pages to show the published site address.
8. Open that address in Safari on the iPhone.
9. Tap **Share → Add to Home Screen**.

## Personal notes
Your notes are stored locally in that browser/device using IndexedDB, with localStorage fallback.
They are not uploaded to GitHub and are not visible to other visitors.

Notes on one device do not automatically sync to another device.

## Updating the app later
Replace `index.html` with the newer app and change the cache name near the top of `sw.js`
(for example from `cerec-learning-v21` to `cerec-learning-v22`).


## File-size note
This slim package keeps `index.html` below GitHub's 25 MB browser-upload limit without reducing the embedded PDF image resolution.
