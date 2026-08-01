# KTEDM Website — Kolej Tingkatan Enam Desa Mahkota

A single-page, bilingual (Bahasa Melayu / English) website for KTEDM, built with plain HTML/CSS/JS — no build tools, no cost.

## Files
- `index.html` — the entire site (structure + styling + interactivity in one file)
- `assets/logo.jpg` — the college badge/logo

## How to publish for free on GitHub Pages

1. Create a free GitHub account at https://github.com if you don't have one.
2. Create a **new repository** — name it anything, e.g. `ktedm-website`. Make it **Public**.
3. Upload these files:
   - Click **Add file → Upload files**
   - Drag in `index.html` and the whole `assets` folder (keep the folder structure)
   - Commit the changes
4. Turn on GitHub Pages:
   - Go to the repo's **Settings → Pages**
   - Under "Branch", choose `main` and `/ (root)`, then **Save**
   - Wait ~1 minute — GitHub will give you a live URL like:
     `https://your-username.github.io/ktedm-website/`
5. Share that link — the site is now live, free, forever (as long as the repo stays public).

## Notes for next steps

- **Gallery & principal photo currently hotlink to the old WordPress site** (kt6dm.wordpress.com). This works today, but if that WordPress site is ever taken down, those images will break. Recommended: download the real photos and place them in `assets/gallery/`, then update the `<img src="...">` paths in `index.html` to point locally (e.g. `assets/gallery/dewan.jpg`).
- To use a custom domain (e.g. `www.ktedm.edu.my`) instead of the github.io address, add a `CNAME` file — ask if you'd like help with this once you have a domain.
- The language toggle (BM/EN) is done with a simple show/hide pattern — every bilingual line of text has a Bahasa Melayu and English version already written in; switching is instant, no reload.
