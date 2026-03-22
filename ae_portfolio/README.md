# ae-portfolio

Analytics engineering portfolio built on the [Olist Brazilian E-Commerce dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## Dataset
~100k orders from a Brazilian e-commerce marketplace (2016–2018). Includes orders, customers, products, sellers, payments, and reviews.

## Project Structure
- `seeds/` — raw Olist CSVs loaded as dbt seeds
- `models/staging/` — light cleaning and renaming of raw sources
- `models/marts/` — dimensional models (facts + dims)

## Phases
- [x] Phase 0 — Project setup, seeds loaded
- [ ] Phase 1 — Dimensional modeling (star schema)
- [ ] Phase 2 — Snapshots, advanced Jinja, semantic layer
- [ ] Phase 3 — CI/CD, testing, Elementary