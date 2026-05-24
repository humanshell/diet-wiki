# Wiki Log

> Chronological record of all wiki actions. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`

## [2026-05-16] create | Wiki initialized
- Domain: Heart healthy diet and nutrition for post heart attack recovery
- Structure created with SCHEMA.md, index.md, log.md

## [2026-05-17] ingest | Heart-Healthy Diet for Recovery Deep Research.md
- Created entities: [[mediterranean-diet]], [[dash-diet]]
- Created concepts: [[secondary-cardiovascular-prevention]], [[systemic-inflammation]]

## [2026-05-17] ingest | Lyon_Diet_Heart_Study_and_ALA.md
- Created entities: [[alpha-linolenic-acid]], [[omega-3-fatty-acids]], [[lyon-diet-heart-study]]
- Created concepts: [[anti-inflammatory-environment]], [[anti-thrombotic-environment]]
- Created comparison: [[mediterranean-vs-western-diet]]
- Updated: [[mediterranean-diet]]

## [2026-05-17] ingest | NHLBI_DASH_Eating_Plan_Menu.md
- Created entities: [[sodium]], [[potassium]], [[magnesium]], [[calcium]]
- Created concepts: [[blood-pressure-reduction]], [[sodium-reduction]]
- Created comparison: [[sodium-intake-targets]]
- Updated: [[dash-diet]]

## [2026-05-17] ingest | Ornish_Lifestyle_Heart_Trial.md
- Created entities: [[ornish-lifestyle-heart-trial]], [[very-low-fat-vegetarian-diet]]
- Created concepts: [[plaque-regression]], [[lifestyle-modification]]
- Created comparison: [[lifestyle-intervention-vs-usual-care]]
- Updated: [[secondary-cardiovascular-prevention]]

## [2026-05-17] ingest | CORDIOPREV_Trial_Protocol_and_Results.md
- Created entities: [[cordioprev-trial]], [[extra-virgin-olive-oil]], [[tree-nuts]]
- Created concepts: [[major-adverse-cardiovascular-events]], [[chronic-kidney-disease]]
- Created comparison: [[mediterranean-vs-low-fat-diet]]
- Updated: [[mediterranean-diet]], [[secondary-cardiovascular-prevention]]

## [2026-05-17] ingest | 2026_ACC_AHA_Dyslipidemia_Guidelines.md
- Created entities: [[apolipoprotein-b]], [[lipoprotein-a]], [[statin-therapy]], [[atherosclerotic-cardiovascular-disease]]
- Created concepts: [[dyslipidemia-management]], [[risk-stratification]], [[residual-risk-assessment]]
- Created comparison: [[ldl-c-calculation-formulas]]
- Updated: [[secondary-cardiovascular-prevention]]

## [2026-05-17] lint | Full wiki repair and expansion pass
- Fixed 7 broken wikilinks (created [[2026-acc-aha-dyslipidemia-guidelines]] and [[lipid-lowering-therapy]])
- De-orphaned 10 pages by adding backlinks from relevant hub pages
- Expanded 5 thin comparison pages with structured tables and verdicts
- Rewrote index.md with descriptive one-line summaries
- Bumped updated dates on all modified pages

## [2026-05-17] research | Expanded DASH and Mediterranean diet pages
- Sources: Wikipedia DASH diet, Wikipedia Mediterranean diet via web research
- Updated: [[mediterranean-diet]] with historical context, core principles, cardiovascular benefits, cognitive health, and recognition standards
- Updated: [[dash-diet]] with detailed serving guidelines, BP effects, OmniHeart variations, and clinical risk reduction data
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
- Created entities: [[fish]], [[fruit]], [[vegetable]], [[legumes]], [[nuts]], [[red-meat]], [[omniheart-diet]]
- Created concept: [[hypertension]]
- Fixed: Removed [[World Health Organization]] wikilink (not central to domain)
- Updated index.md

## [2026-05-18] recipe | Created recipes subdirectory and 5 curated recipe pages
- Created `recipes/` directory with `README.md` index
- Sources: Olive Tomato (Elena Paravantes, MS RD), The Mediterranean Dish (Suzy Karadsheh), Downshiftology (Lisa Bryan)
- Recipe 1: [[fasolakia-lathera]] — Greek Green Beans (Fasolakia Lathera) ★5.0, 73 ratings
- Recipe 2: [[everyday-mediterranean-salad]] — Everyday Mediterranean Salad ★4.87, 29 ratings
- Recipe 3: [[greek-chicken-salad]] — Greek Chicken Salad ★5.0, 20 ratings
- Recipe 4: [[baba-ganoush]] — Baba Ganoush (Authentic & Smoky) ★4.96, 42 ratings
- Recipe 5: [[mediterranean-white-bean-soup]] — White Bean Soup ★4.93, 103 ratings
- All recipes verified with AggregateRating schema data (20+ reviews minimum)
- Updated index.md with new Recipes section

## [2026-05-19] recipe | Added 5 new recipes focused on one-pot, stove top, air fryer, and rice cooker
- Created 5 new recipe pages for a 50-year-old man cooking for one — quick prep, short cook times
- Recipe 1: [[shakshuka]] — Shakshuka (Poached Eggs in Tomato Pepper Sauce) ★4.98, 215 ratings, The Mediterranean Dish — stovetop, 40 min
- Recipe 2: [[air-fryer-salmon-capers]] — Air Fryer Salmon with Capers ★5.0, 135 ratings, Downshiftology — air fryer, 20 min
- Recipe 3: [[air-fryer-chicken-wings-lemon-pepper]] — Air Fryer Chicken Wings (Lemon Pepper) ★5.0, 26 ratings, Downshiftology — air fryer, 30 min
- Recipe 4: [[air-fryer-falafel-tahini]] — Air Fryer Falafel with Tahini Sauce ★4.94, 508 ratings, Downshiftology — air fryer, 75 min (includes soak)
- Recipe 5: [[greek-green-beans-fasolakia]] — Greek Green Beans (Fasolakia Lathera) ★5.0, 73 ratings, Olive Tomato — stovetop, 60 min
- All ratings verified from Schema.org JSON-LD aggregateRating data
- Updated recipes/README.md with new sections organized by cooking method (Stove Top, Air Fryer)
