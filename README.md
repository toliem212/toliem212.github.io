# To Thanh Liem — Quantitative Finance Portfolio

A bilingual (English/Vietnamese), responsive static website for GitHub Pages.

## Publish with GitHub Pages

1. On GitHub, create a **public** repository named exactly `toliem212.github.io`.
2. Upload `index.html`, `.nojekyll` and the `assets/` folder to the repository's root folder on the `main` branch (or let ChatGPT add these files using the linked GitHub connection after the repository exists).
3. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then **main** and **/(root)**. Save.
4. Visit `https://toliem212.github.io/` after GitHub finishes publishing.

No build tools, external scripts, API keys, or paid hosting are required.

## Structure

- `index.html` — complete website, styles, and bilingual toggle
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing
- `assets/favicon.svg` — local TL monogram
- `assets/social-card.png` — 1200 × 630 social sharing card

## Content policy

- Public project links point to existing user-controlled projects.
- VN30 ETF research is described without sharing private data, proprietary research parameters, or code.
- Illustrative chart is explicitly marked as illustrative, not real financial performance.
- No private email address, phone number, or personal documents are disclosed.

## Changes

Use a separate branch and pull request for changes. Keep the English and Vietnamese `data-*` values in sync, including accessible labels. Check both languages at desktop, tablet and mobile widths; test language persistence, menu close/Escape, anchors and external links before merging. GitHub Pages republishes from `main`.

The language preference is stored locally when browser storage is available. Navigation and the default English content remain usable without JavaScript. Sharing crawlers receive the static English metadata and local social card; no separate translated URLs are advertised.
