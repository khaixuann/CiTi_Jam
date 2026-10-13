# CiTi Jam website

Static site (no build step). Files:

- `index.html` — the whole page
- `images/` — product photos
- `.nojekyll` — tells GitHub Pages to serve the files as-is

## Publish on GitHub Pages
1. Create a new **public** repository on github.com (e.g. `citi-jam`).
2. Click **Add file → Upload files** and drag in everything from this folder (`index.html`, the `images` folder, `.nojekyll`). Commit.
3. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. After 1–2 minutes the site is live at `https://<your-username>.github.io/<repo-name>/`.
5. Optional: add your own domain under **Settings → Pages → Custom domain**.
