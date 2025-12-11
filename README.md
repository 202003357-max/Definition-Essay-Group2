# The Misleading Promise of “Stability” — Static Site (Essay + Visualizations)

This repository contains a static, GitHub-ready visualization companion to the essay *The Misleading Promise of “Stability”: Rethinking the Definition of Stablecoins*.  
It combines the original essay text (verbatim) with curated visual assets to help readers understand why the label “stablecoin” can be misleading and what actually underpins stability.

## Contents
- `index.html` — main static page (essay + visual resources)
- `styles.css` — stylesheet for responsive layout
- (images are currently hotlinked to external sources; optionally replace with local copies)

## How to use
1. Create a new GitHub repository (public or private).
2. Add the files above (`index.html`, `styles.css`) to the repository.
3. Option A — View locally: open `index.html` in your browser.
   - Or run a simple static server, e.g. `python -m http.server` in the repo folder and visit `http://localhost:8000`.
4. Option B — Deploy with GitHub Pages:
   - Push to repository and enable GitHub Pages (use `main` branch / `gh-pages` branch).
   - After Pages is active, your site will be published.

## Notes & suggestions
- For production or offline usage, download the images and replace the `src` attributes in `index.html` with the local file paths (e.g., `assets/img/usdc-reserve.png`).
- Add license/attribution files if any visual asset requires them.
- If you'd like, I can:
  - Convert this into a multi-page site (separate assets, case study, references).
  - Provide a Figma mockup or a fully coded responsive HTML/CSS/JS site with lightbox and image local assets.
  - Generate an accessible PDF version.

## Credits & sources
Images and charts in the sample page are hotlinked from publicly available reports and articles (chainalysis, glassnode, ledgerinsights, easypeasyfinance, etc.). When deploying, ensure compliance with source licenses and optionally replace with local licensed copies.

---
Built 2025 — Prepared as a GitHub-ready static visualization.
