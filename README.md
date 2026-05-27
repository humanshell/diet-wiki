# Diet Wiki

> A curated, evidence-based knowledge base on Mediterranean diet and nutrition for post-heart-attack recovery and secondary cardiovascular prevention.

**Live site:** [diet.d5c.me](https://diet.d5c.me)

## Overview

The Diet Wiki is a structured knowledge base built with [MkDocs](https://www.mkdocs.org/) and the [Material theme](https://squidfone.github.io/mkdocs-material/). It captures clinical evidence, dietary patterns, food-level guidance, and recipes — all organized around a single therapeutic question: *What should someone eat after a heart attack?*

The content synthesizes landmark clinical trials (Lyon Diet Heart Study, CORDIOPREV, Ornish Lifestyle Heart Trial), the 2026 ACC/AHA Dyslipidemia Guidelines, and authoritative dietary references into a browsable, interlinked wiki.

## Content Structure

| Section | Description | Entries |
|---|---|---|
| **Concepts** | Clinical and dietary mechanisms underpinning heart-healthy eating — inflammation, plaque regression, blood pressure reduction, lipid management, and more | 15 |
| **Entities** | Foods, nutrients, biomarkers, clinical trials, and diet patterns — the "nodes" of the knowledge graph | 34 |
| **Recipes** | Curated, highly-rated Mediterranean diet recipes with verified aggregate ratings (20+ reviews minimum) | 10 |
| **Comparisons** | Head-to-head analyses of dietary patterns, clinical formulas, and intervention strategies | 4 |

### Subjects Covered

- **Diet patterns** — Mediterranean diet, very-low-fat vegetarian diet
- **Foods** — Extra-virgin olive oil, fish, legumes, whole grains, vegetables, fruit, nuts, poultry, eggs, cheese, yogurt, wine, herbs, and more
- **Nutrients** — Omega-3 fatty acids, alpha-linolenic acid, sodium, potassium, magnesium, calcium
- **Biomarkers** — Apolipoprotein B, lipoprotein(a)
- **Clinical evidence** — Lyon Diet Heart Study, CORDIOPREV Trial, Ornish Lifestyle Heart Trial, 2026 ACC/AHA Dyslipidemia Guidelines, statin therapy

## Key Clinical Evidence

The wiki is grounded in landmark research:

| Trial | Key Finding |
|---|---|
| **Lyon Diet Heart Study** (1999) | 50–70% reduction in recurrent cardiac events on a Mediterranean-style diet enriched in alpha-linolenic acid |
| **CORDIOPREV Trial** | 28.1% lower risk of recurrent major adverse cardiovascular events vs. low-fat diet over 7 years |
| **Ornish Lifestyle Heart Trial** | Intensive lifestyle change (very-low-fat vegetarian diet, exercise, stress management) promoted selective coronary plaque regression |

## Tech Stack

- **Static site generator:** [MkDocs](https://www.mkdocs.org/)
- **Theme:** [Material for MkDocs](https://squidfone.github.io/mkdocs-material/) with OS-preference-aware light/dark mode
- **CI/CD:** GitHub Actions — auto-builds and deploys to GitHub Pages on push to `master`
- **Domain:** `diet.d5c.me`

### Local Development

```bash
# Install dependencies
pip install mkdocs-material

# Serve locally with live reload
mkdocs serve

# Build static site
mkdocs build
```

## Project Conventions

- **File names:** Lowercase with hyphens (e.g., `extra-virgin-olive-oil.md`)
- **Frontmatter:** Every page includes YAML frontmatter (`title`, `created`, `updated`, `type`, `tags`, `sources`, `confidence`)
- **Linking:** Standard Markdown links between pages — cross-section references use relative paths
- **Logging:** All changes recorded chronologically in [`docs/log.md`](docs/log.md)
- **Provenance:** Pages synthesizing 3+ sources carry provenance markers linking to original source files

## Repository Structure

```
diet-wiki/
├── docs/                    # Content root
│   ├── index.md             # Homepage / table of contents
│   ├── log.md               # Chronological change log
│   ├── CNAME                # Custom domain (diet.d5c.me)
│   ├── concepts/            # Clinical and dietary concepts (15 pages)
│   ├── entities/            # Foods, nutrients, trials, patterns (34 pages)
│   ├── recipes/             # Curated recipe collection (10 pages)
│   └── comparisons/         # Head-to-head analyses (4 pages)
├── mkdocs.yml               # MkDocs configuration
├── SCHEMA.md                # Wiki schema and conventions
├── .github/workflows/       # CI/CD pipeline
└── README.md                # This file
```

## Contributing

1. Create or edit the relevant markdown file under `docs/`
2. Add or bump the `updated` field in YAML frontmatter
3. Add a record to [`docs/log.md`](docs/log.md)
4. If creating a new page, add it to the navigation in `mkdocs.yml` and link it from `docs/index.md`
5. Push to `master` — the GitHub Action automatically deploys

## License

© humanshell — personal research wiki.
