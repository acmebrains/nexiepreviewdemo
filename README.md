# Nexie Demo — Mobile Build

Mobile-optimized version of the Nexie interactive prototype, fixed for real iPhone behavior:

- **Coach mark spotlights** now position correctly on a scaled phone frame (recompute on resize/rotation).
- **iOS soft keyboard suppressed** — every input/textarea is marked `readonly` + `inputmode="none"` so taps never trigger the system keyboard. The prototype's own on-screen keyboard remains visible as part of the demo.

## Deploying to GitHub Pages

1. Create a new public repository on GitHub.
2. Upload these files to the repo root:
   - `index.html`
   - `.nojekyll`
   - `README.md` (optional)
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, branch **main** (or **master**), folder **/ (root)**, and **Save**.
5. Wait ~1 minute. Your live URL will appear at the top of the Pages settings: `https://<your-username>.github.io/<repo-name>/`
6. Open that URL on iPhone Safari.
