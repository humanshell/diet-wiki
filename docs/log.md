# Wiki Log

> Chronological record of all wiki actions. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`

## [2026-05-16] create | Wiki initialized
- Domain: Heart healthy diet and nutrition for post heart attack recovery
- Structure created with SCHEMA.md, index.md, log.md

## [2026-05-17] ingest | Heart-Healthy Diet for Recovery Deep Research.md
- Created entities: [mediterranean-diet](entities/mediterranean-diet.md), [dash-diet](dash-diet.md)
- Created concepts: [secondary-cardiovascular-prevention](concepts/secondary-cardiovascular-prevention.md), [systemic-inflammation](concepts/systemic-inflammation.md)

## [2026-05-17] ingest | Lyon_Diet_Heart_Study_and_ALA.md
- Created entities: [alpha-linolenic-acid](entities/alpha-linolenic-acid.md), [omega-3-fatty-acids](entities/omega-3-fatty-acids.md), [lyon-diet-heart-study](entities/lyon-diet-heart-study.md)
- Created concepts: [anti-inflammatory-environment](concepts/anti-inflammatory-environment.md), [anti-thrombotic-environment](concepts/anti-thrombotic-environment.md)
- Created comparison: [mediterranean-vs-western-diet](comparisons/mediterranean-vs-western-diet.md)
- Updated: [mediterranean-diet](entities/mediterranean-diet.md)

## [2026-05-17] ingest | NHLBI_DASH_Eating_Plan_Menu.md
- Created entities: [sodium](entities/sodium.md), [potassium](entities/potassium.md), [magnesium](entities/magnesium.md), [calcium](entities/calcium.md)
- Created concepts: [blood-pressure-reduction](concepts/blood-pressure-reduction.md), [sodium-reduction](concepts/sodium-reduction.md)
- Created comparison: [sodium-intake-targets](sodium-intake-targets.md)
- Updated: [dash-diet](dash-diet.md)

## [2026-05-17] ingest | Ornish_Lifestyle_Heart_Trial.md
- Created entities: [ornish-lifestyle-heart-trial](entities/ornish-lifestyle-heart-trial.md), [very-low-fat-vegetarian-diet](entities/very-low-fat-vegetarian-diet.md)
- Created concepts: [plaque-regression](concepts/plaque-regression.md), [lifestyle-modification](concepts/lifestyle-modification.md)
- Created comparison: [lifestyle-intervention-vs-usual-care](comparisons/lifestyle-intervention-vs-usual-care.md)
- Updated: [secondary-cardiovascular-prevention](concepts/secondary-cardiovascular-prevention.md)

## [2026-05-17] ingest | CORDIOPREV_Trial_Protocol_and_Results.md
- Created entities: [cordioprev-trial](entities/cordioprev-trial.md), [extra-virgin-olive-oil](entities/extra-virgin-olive-oil.md), [tree-nuts](entities/tree-nuts.md)
- Created concepts: [major-adverse-cardiovascular-events](concepts/major-adverse-cardiovascular-events.md), [chronic-kidney-disease](concepts/chronic-kidney-disease.md)
- Created comparison: [mediterranean-vs-low-fat-diet](comparisons/mediterranean-vs-low-fat-diet.md)
- Updated: [mediterranean-diet](entities/mediterranean-diet.md), [secondary-cardiovascular-prevention](concepts/secondary-cardiovascular-prevention.md)

## [2026-05-17] ingest | 2026_ACC_AHA_Dyslipidemia_Guidelines.md
- Created entities: [apolipoprotein-b](entities/apolipoprotein-b.md), [lipoprotein-a](entities/lipoprotein-a.md), [statin-therapy](entities/statin-therapy.md), [atherosclerotic-cardiovascular-disease](entities/atherosclerotic-cardiovascular-disease.md)
- Created concepts: [dyslipidemia-management](concepts/dyslipidemia-management.md), [risk-stratification](concepts/risk-stratification.md), [residual-risk-assessment](concepts/residual-risk-assessment.md)
- Created comparison: [ldl-c-calculation-formulas](comparisons/ldl-c-calculation-formulas.md)
- Updated: [secondary-cardiovascular-prevention](concepts/secondary-cardiovascular-prevention.md)

## [2026-05-17] lint | Full wiki repair and expansion pass
- Fixed 7 broken wikilinks (created [2026-acc-aha-dyslipidemia-guidelines](entities/2026-acc-aha-dyslipidemia-guidelines.md) and [lipid-lowering-therapy](concepts/lipid-lowering-therapy.md))
- De-orphaned 10 pages by adding backlinks from relevant hub pages
- Expanded 5 thin comparison pages with structured tables and verdicts
- Rewrote index.md with descriptive one-line summaries
- Bumped updated dates on all modified pages

## [2026-05-17] research | Expanded DASH and Mediterranean diet pages
- Sources: Wikipedia DASH diet, Wikipedia Mediterranean diet via web research
- Updated: [mediterranean-diet](entities/mediterranean-diet.md) with historical context, core principles, cardiovascular benefits, cognitive health, and recognition standards
- Updated: [dash-diet](dash-diet.md) with detailed serving guidelines, BP effects, OmniHeart variations, and clinical risk reduction data
- Added raw sources: research-dash-diet-wikipedia.md, research-mediterranean-diet-wikipedia.md
- Rewrote index.md with updated descriptive summaries

## [2026-05-18] create | Added 9 new Mediterranean food entries
- Created: whole-grains, cheese, yogurt, eggplant, tahini, mediterranean-herbs, wine, poultry, eggs, canola-oil
- All entries include YAML frontmatter, cardiovascular properties, and Mediterranean context
- Sources used: research-mediterranean-diet-wikipedia.md, Lyon_Diet_Heart_Study_and_ALA.md
- Redesigned index.md as a Wikipedia-style homepage with: masthead + domain description, "Start Here" section linking 3 foundational pages, organized topic sections with descriptive prose (The Mediterranean Pattern, Key Clinical Evidence table, Core Concepts, Supporting Nutrients), recipe collection with rating table, and an "All Pages" compressed reference section

## [2026-05-18] remove | Removed DASH diet content, refocused on Mediterranean
- Deleted: entities/dash-diet.md, entities/omniheart-diet.md, comparisons/sodium-intake-targets.md
- Deleted source files: raw/articles/NHLBI_DASH_Eating_Plan_Menu.md, raw/articles/research-dash-diet-wikipedia.md
- Rewrote: sodium-reduction.md, blood-pressure-reduction.md, hypertension.md (Mediterranean-focused)
- Patched 13 entity/concept files to remove DASH references and broken source links
- Updated index.md: removed DASH entries, sodium-intake-targets comparison, updated page count from 46 to 41
- Updated sources in: nuts, fruit, vegetable, legumes, fish, red-meat, potassium, calcium, magnesium, sodium

## [2026-05-17] research | Created supporting entity stubs for expanded diet pages
- Created entities: [fish](entities/fish.md), [fruit](entities/fruit.md), [vegetable](entities/vegetable.md), [legumes](entities/legumes.md), [nuts](entities/nuts.md), [red-meat](entities/red-meat.md), [omniheart-diet](omniheart-diet.md)
- Created concept: [hypertension](concepts/hypertension.md)
- Fixed: Removed [World Health Organization](World Health Organization.md) wikilink (not central to domain)
- Updated index.md

## [2026-05-18] recipe | Created recipes subdirectory and 5 curated recipe pages
- Created `recipes/` directory with `README.md` index
- Sources: Olive Tomato (Elena Paravantes, MS RD), The Mediterranean Dish (Suzy Karadsheh), Downshiftology (Lisa Bryan)
- Recipe 1: [fasolakia-lathera](fasolakia-lathera.md) — Greek Green Beans (Fasolakia Lathera) ★5.0, 73 ratings
- Recipe 2: [everyday-mediterranean-salad](everyday-mediterranean-salad.md) — Everyday Mediterranean Salad ★4.87, 29 ratings
- Recipe 3: [greek-chicken-salad](greek-chicken-salad.md) — Greek Chicken Salad ★5.0, 20 ratings
- Recipe 4: [baba-ganoush](baba-ganoush.md) — Baba Ganoush (Authentic & Smoky) ★4.96, 42 ratings
- Recipe 5: [mediterranean-white-bean-soup](mediterranean-white-bean-soup.md) — White Bean Soup ★4.93, 103 ratings
- All recipes verified with AggregateRating schema data (20+ reviews minimum)
- Updated index.md with new Recipes section

## [2026-05-19] recipe | Added 5 new recipes focused on one-pot, stove top, air fryer, and rice cooker
- Created 5 new recipe pages for a 50-year-old man cooking for one — quick prep, short cook times
- Recipe 1: [shakshuka](shakshuka.md) — Shakshuka (Poached Eggs in Tomato Pepper Sauce) ★4.98, 215 ratings, The Mediterranean Dish — stovetop, 40 min
- Recipe 2: [air-fryer-salmon-capers](air-fryer-salmon-capers.md) — Air Fryer Salmon with Capers ★5.0, 135 ratings, Downshiftology — air fryer, 20 min
- Recipe 3: [air-fryer-chicken-wings-lemon-pepper](air-fryer-chicken-wings-lemon-pepper.md) — Air Fryer Chicken Wings (Lemon Pepper) ★5.0, 26 ratings, Downshiftology — air fryer, 30 min
- Recipe 4: [air-fryer-falafel-tahini](air-fryer-falafel-tahini.md) — Air Fryer Falafel with Tahini Sauce ★4.94, 508 ratings, Downshiftology — air fryer, 75 min (includes soak)
- Recipe 5: [greek-green-beans-fasolakia](greek-green-beans-fasolakia.md) — Greek Green Beans (Fasolakia Lathera) ★5.0, 73 ratings, Olive Tomato — stovetop, 60 min
- All ratings verified from Schema.org JSON-LD aggregateRating data
- Updated recipes/README.md with new sections organized by cooking method (Stove Top, Air Fryer)

## [2026-05-23] infrastructure | GitHub Actions CI/CD pipeline fix
- Error: `mkdocs: command not found` (exit code 127) — MkDocs not installed in runner
- Fix: `.github/workflows/deploy.yml` — added `pip install mkdocs` before `mkdocs gh-deploy`
- Added `GITHUB_TOKEN` env var to `mkdocs gh-deploy` step for `gh-pages` branch authentication
- Note: MkDocs gh-deploy uses the token automatically; no manual secret needed

## [2026-05-23] config | Rebuilt mkdocs.yml navigation structure
- Rebuilt nav section with full section index pages: Concepts (15 pages), Entities (34 pages, 4 sub-groups), Recipes (11 pages), Comparisons (4 pages)
- Added `docs/concepts/index.md` and `docs/comparisons/index.md` section landing pages
- `recipes/README.md` already existed; `recipes/` section index uses it as-is
- Restored `Home: index.md` and `Log: log.md` top-level nav entries

## [2026-05-23] lint | Converted 391 wikilinks to standard Markdown across 58 files
- Replaced all `[[target]]`, `[[target|display]]`, and `[[path\\|display]]` (escaped pipe) patterns
- Cross-section links resolved with correct relative paths (e.g., entities → concepts = `../concepts/`)
- Same-section links use bare relative filenames
- Updated SCHEMA.md convention: `[[wikilinks]]` → standard Markdown link syntax
- SCHEMA.md version bumped 1.0.0 → 1.1.0

## [2026-05-23] theme | Switched from readthedocs to MkDocs Material
- `mkdocs.yml`: `name: readthedocs` → `name: material`
- Replaced `color_mode/user_color_mode_toggle` with Material `palette` (OS-preference-aware light/dark with sun/moon toggle)
- Added Material features: `navigation.collapse`, `navigation.instant`, `navigation.sections`, `search.highlight`, `content.code.copy`
- `.github/workflows/deploy.yml`: `pip install mkdocs` → `pip install mkdocs-material`

## [2026-05-27] create | Brunch Power Shake recipe added
- Created: [docs/recipes/brunch-power-shake.md](recipes/brunch-power-shake.md) — personal performance & longevity formula with EVOO, omega-3s (chia, hemp), creatine, collagen, whey, and berries
- Updated: `docs/recipes/README.md` — added "Smoothies & Meal Replacements" section, blender method to cooking methods table
- Updated: `docs/index.md` — added shake to recipe table, bumped page count (50 → 51), updated recipe count
- Updated: `mkdocs.yml` — added "Brunch Power Shake" to Recipes nav
- Updated: [docs/entities/alpha-linolenic-acid.md](entities/alpha-linolenic-acid.md) — added chia seeds and hemp hearts as dietary ALA sources

## [2026-06-09] create | Added sourdough-bread entity page
- Created: [docs/entities/sourdough-bread.md](entities/sourdough-bread.md) — comprehensive entity on sourdough bread's cardiovascular benefits including lower glycemic index, improved mineral bioavailability through phytate reduction, prebiotic SCFA production (butyrate, acetate), enhanced antioxidant activity, and partial gluten degradation
- Sources: Healthline, Cleveland Clinic, WebMD, PMC, Da Ros et al. human trial (2024), Springer (2025)
- Updated: [docs/entities/whole-grains.md](entities/whole-grains.md) — added sourdough-bread link reference
- Updated: `mkdocs.yml` — added Sourdough Bread to Foods nav
- Updated: `docs/index.md` — added to entities list, bumped page count (51 → 52)

## [2026-06-09] create | Added calisthenics exercise entity
- Created: [docs/entities/calisthenics.md](entities/calisthenics.md) — comprehensive calisthenics / bodyweight resistance training entity covering cardiovascular benefits (BP reduction, lipid profile, glycemic control, VO₂max, HRV, inflammation), cardiac rehabilitation guidelines, progressive exercise tables, and synergy with Mediterranean diet
- Expanded: [docs/concepts/lifestyle-modification.md](concepts/lifestyle-modification.md) — added dedicated Diet, Exercise (with calisthenics cross-link), and Stress Management sections; previously a thin stub
- Updated: `mkdocs.yml` — added Exercise & Lifestyle nav subsection with Calisthenics
- Updated: `docs/index.md` — added Physical Activity section to Core Concepts, entities list (34→35), page count (52→53)
