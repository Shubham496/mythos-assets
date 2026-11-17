# Mythos Digital Assets & Dataset Vault

This repository hosts decoupled binary assets, large datasets, and downloadable digital products for [mythostech.in](https://mythostech.in) to keep the core FastAPI application lightweight on Render.io.

## Directory Structure

```text
mythos-assets/
├── images/             # Visual diagrams, notes infographics, screenshots (WebP/SVG/PNG)
│   ├── sql/
│   ├── python/
│   └── bi/
├── datasets/           # Curated CSV, SQLite, and Excel practice datasets
│   └── ecommerce_50k/
└── downloads/          # Downloadable PDF guides, solved viva sets, capstone zip archives
    ├── books/
    └── viva/
```

## CDN & Access Conventions

* **Images via jsDelivr CDN (Fast, Cached, Zero-Egress):**
  `https://cdn.jsdelivr.net/gh/Shubham496/mythos-assets@main/images/<category>/<filename>`

* **Direct Dataset & File Downloads:**
  `https://github.com/Shubham496/mythos-assets/raw/main/datasets/<filename>`
