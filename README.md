# Personal site (static)

This folder is a ready-to-publish static website (no build tools).

## Customize
- Edit the text placeholders in:
  - `index.html`
  - `updates/index.html`
  - `publications/index.html`
  - `projects/index.html`
- Optional: adjust typography/colors in `assets/style.css`.

## Publish on GitHub Pages (no custom domain)
1. Create a public repo named exactly: `<your-username>.github.io`.
2. Copy the contents of this folder into that repo’s root (so `index.html` is at the repo root).
3. Commit + push.
4. On GitHub: Repo → Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` (or `master`) and folder `/ (root)`
5. After 1–3 minutes, your site will be at: `https://<your-username>.github.io/`

## Local preview
Open `index.html` in a browser, or run a tiny web server:

```bash
cd <your-username>.github.io
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.
