# Nexie Demo

Interactive HTML prototype of the Nexie app, designed for live demo use on phones and desktops.

## How to host on GitHub Pages

1. Create a new repository on GitHub (e.g. `nexie-demo`). Make it public.
2. Upload **all the files in this folder** to the repo (`index.html`, `.nojekyll`, `README.md`).
   - In the GitHub web UI: click **Add file → Upload files**, drag in the files, then **Commit changes**.
3. In your repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`), folder `/ (root)`
5. Click **Save**. Wait ~1 minute for the deploy.
6. Your demo will be live at: `https://<your-username>.github.io/nexie-demo/`

Open that URL in Mobile Safari on your iPhone — it will work just like on desktop.

## Files

- **`index.html`** — the entire prototype (all images, fonts, and logic embedded inline)
- **`.nojekyll`** — tells GitHub Pages to serve files as-is, without Jekyll processing
- **`README.md`** — this file

## Notes

- The prototype loads React, ReactDOM, and Babel from `unpkg.com` CDN — these need internet access at runtime.
- All other assets (images, scripts, logic) are embedded as data URLs in `index.html` — no other files required.
