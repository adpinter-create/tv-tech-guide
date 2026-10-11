# The Physics of the Picture

A course-length field guide to TV display technology (2025–2026) for andreipinter.com: transmissive vs emissive, LCD and Mini-LED, OLED and QD-OLED, RGB-LED backlights, MicroLED and QDEL, a comparison matrix, cost per technology and buying picks.

One self-contained `index.html` (inline CSS, SVG figures and the canvas blooming demo; only Google Fonts load from outside). Published to GitHub Pages by a GitHub Action, same setup as PulseNews and the hiring dashboard. Nothing refreshes on a schedule: the page redeploys whenever `main` changes.

## Setup

1. Settings → Pages → Source: **GitHub Actions**.
2. Settings → Pages → Custom domain: `tv.andreipinter.com`.
3. DNS (Squarespace → Domains → DNS): CNAME, host `tv`, data `adpinter-create.github.io`.
4. Actions → Deploy TV tech guide → Run workflow (or push any change).
5. When the domain verifies, tick **Enforce HTTPS**.

## Editing

Edit `index.html` and push. Preview locally with `python -m http.server`, then open localhost:8000.
