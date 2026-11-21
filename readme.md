# Mythos Digital Assets & Dataset Vault (mythos-assets)

This repository hosts decoupled binary assets, large datasets, and downloadable open-source educational products for [mythostech.in](https://mythostech.in) to keep the core FastAPI application lightweight on Render.io.

## Directory Structure

```text
mythos-assets/
├── notes/              # Curated open-source cheatsheets & study notes across 34 subjects
├── datasets/           # Curated CSV, SQLite, and Excel practice datasets
├── downloads/          # Downloadable PDF guides, solved viva sets, and reference cheat sheets
├── images/             # Visual diagrams, notes infographics, and screenshots (WebP/SVG/PNG)
├── MANIFEST.json       # Complete asset catalog, source URLs, and open license attributions
└── fetch_assets.py     # Automated vault curation and synchronization pipeline
```

## CDN & Access Conventions

* **Images & Notes via jsDelivr CDN (Fast, Cached, Zero-Egress):**
  `https://cdn.jsdelivr.net/gh/Shubham496/mythos-assets@main/images/<category>/<filename>`
  `https://cdn.jsdelivr.net/gh/Shubham496/mythos-assets@main/notes/<subject>/<filename>`

* **Direct Dataset & File Downloads:**
  `https://github.com/Shubham496/mythos-assets/raw/main/datasets/<filename>`
  `https://github.com/Shubham496/mythos-assets/raw/main/notes/<subject>/<filename>`

## Curation Standard: Open Educational Resources (OER)
1. **Source Attribution**: All materials are curated from high-reputation open-source repositories under permissive licenses (MIT, Apache 2.0, Open Data).
2. **Editorial Protocol**: When promoting materials from this vault to `app/content/`, apply light rewrites to enforce:
   - The **Skipped Foundations & Production Truth** pedagogy (contrasting textbook definitions with production execution).
   - The **A4 PDF print-width invariant** (code line length capped at <= 75–80 chars, tables 3–4 concise columns).

## Inventory Summary
* **Curated Subjects**: 34 subjects
* **Total Assets Curated**: 61 files
* **Practice Datasets**: Indian E-Commerce Orders, Delhi Metro Ridership, Digital Marketing Campaign ROAS
* **Manifest**: See `MANIFEST.json` for full URL mappings, file sizes, and licensing source credits.
