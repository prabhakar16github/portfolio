# Prabhakar Joshi — Portfolio

A single-page portfolio site built from my CV: senior Salesforce engineering experience across fintech/payments, healthcare, and financial services.

## Publish it on GitHub Pages (no build step needed)

1. **Create a new repository** on GitHub.
   - You can name it anything, e.g. `portfolio`.
   - If you want it at `https://<your-username>.github.io` directly (no sub-path), name the repo exactly `<your-username>.github.io`.

2. **Add these files to the repo root, keeping the folder structure intact:**
   - `index.html`
   - `README.md` (optional, this file)
   - `assets/logos/` folder — see `assets/logos/ADD_LOGOS_HERE.md` for exactly which logo files to drop in

   Easiest way — on the repo page, click **Add file → Upload files**, drag in the whole folder (or `index.html` plus the `assets` folder), and commit.

   Or via git:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   # copy index.html, README.md, and the assets/ folder into this directory
   git add .
   git commit -m "Add portfolio site"
   git push
   ```

3. **Turn on GitHub Pages:**
   - Go to your repo → **Settings → Pages**.
   - Under "Build and deployment", set **Source** to `Deploy from a branch`.
   - Set **Branch** to `main` and folder to `/ (root)`. Save.

4. **Visit your site** (may take 1–2 minutes to go live):
   - `https://<your-username>.github.io/<repo-name>/`
   - or `https://<your-username>.github.io/` if you used the special repo name in step 1.

## Editing later

Everything — content, colors, layout — lives in the one `index.html` file: HTML in the body, all styling in the `<style>` block at the top. No build tools, no dependencies beyond two Google Fonts loaded via CDN link tags.

To update content (new role, new stat, new cert), search for the relevant text in `index.html` and edit directly.
