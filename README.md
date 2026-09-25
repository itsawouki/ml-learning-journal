# ML Learning Journal

Personal notebooks from learning machine learning fundamentals from scratch,
starting with simple linear regression. Practice datasets under `datasets/`
are synthetic (generated for practice, not scraped real-world data) — the
generator scripts are included for transparency.

## Progress

### 01 — Simple Linear Regression
- `01-engine-size-co2.ipynb` — Engine size vs CO2 emissions (real FuelConsumption dataset)
- `02-cylinders-co2.ipynb` — Cylinders vs CO2 emissions
- `03-cpu-benchmark.ipynb` — CPU cores vs benchmark score (synthetic)
- `04-gaming-fps-challenge.ipynb` — Picking the best/worst predictor of FPS from 5 candidate columns

### 02 — Multi-Linear Regression
- `01-gaming-fps-multi.ipynb` — First multi-input model (GPU VRAM + RAM + resolution)
- `02-youtube-views-capstone.ipynb` — Full pipeline: exploration, feature selection,
  simple vs multi-linear comparison, testing "noise" variables

## Status

- [x] Simple linear regression
- [x] Multi-linear regression
- [ ] Classification (logistic regression)
- [ ] Image data fundamentals
- [ ] Neural network fundamentals
- [ ] CNNs
- [ ] Final goal: animal detection AI

## Notes to self

- Name variables by what they represent, not just `x`/`y`/`train`/`test` reused
  everywhere — a near-identical variable name caused a real bug (wrong R² from
  a typo'd `ss_tot` calculation) that took a while to track down.
- Always verify a suspicious result before trusting it — several bugs here
  were caught specifically because a number looked "too good" or didn't match
  intuition, and turned out to be a real error, not luck.
