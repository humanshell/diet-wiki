---
name: llm-wiki
description: "Heart healthy diet and nutrition for post heart attack recovery"
version: 1.0.0
---

# Wiki Schema

## Domain
Heart healthy diet and nutrition for post heart attack recovery.

## Conventions
- File names: lowercase, hyphens, no spaces (e.g., `mediterranean-diet.md`)
- Every wiki page starts with YAML frontmatter
- Use `[[wikilinks]]` to link between pages
- When updating a page, always bump the `updated` date
- Every new page must be added to `index.md` under the correct section
- Every action must be appended to `log.md`
- **Provenance markers:** On pages that synthesize 3+ sources, append `^[raw/articles/source-file.md]`

## Frontmatter
```yaml
---
title: Page Title
created: 2026-05-16
updated: 2026-05-16
type: entity | concept | comparison | query | summary
tags: [from taxonomy below]
sources: [raw/articles/source-name.md]
confidence: high | medium | low
contested: true
contradictions: [other-page-slug]
---
```

## Tag Taxonomy
- **Foods/Ingredients:** `fruit`, `vegetable`, `whole-grain`, `lean-protein`, `healthy-fat`, `sodium`, `sugar`, `fiber`, `micronutrient`
- **Health/Conditions:** `cholesterol`, `blood-pressure`, `inflammation`, `weight-management`, `cardiovascular-risk`
- **Diet Patterns:** `mediterranean`, `plant-based`, `low-sodium`
- **Recipe Tags:** `stove-top`, `air-fryer`, `rice-cooker`, `one-pot`, `quick-prep`, `meal-prep`
- **Entities:** `doctor`, `nutritionist`, `medical-study`, `organization`
- **Core Concepts:** `macronutrient`, `micronutrient`, `glycemic-index`, `lipid-profile`

## Page Thresholds
- **Create a page** when an entity/concept appears in 2+ sources OR is central to one source
- **Add to existing page** when a source mentions something already covered
- **Split a page** when it exceeds ~200 lines