# Singaaravel R P — Portfolio

A personal portfolio site built from resume + project content, styled around an
engineering "blueprint / spec sheet" theme (roll cage race plates, CAD renders, mono type).

## Structure
- `index.html` — all page content
- `style.css` — design system + layout
- `script.js` — mobile nav + scroll-reveal animations
- `assets/` — images + resume PDF

## How to publish on GitHub Pages
1. Create a new GitHub repo (e.g. `portfolio`).
2. Upload all files in this folder to the repo root (keep the `assets/` folder structure).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source: Deploy from a branch**, branch: `main`, folder: `/ (root)`.
5. Save — GitHub will publish it at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Editing content
Open `index.html` in any text editor — text is plain HTML, organized by section
(`#about`, `#racing`, `#drone`, `#skills`, `#education`, `#contact`). Swap images in `assets/img/`.
