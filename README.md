# Netflix Content Strategy Analysis
**Quantifying the platform's shift from catalogue volume to serialised, retention-focused content (2013-2021)**

![Python](https://img.shields.io/badge/Python-blue) ![Pandas](https://img.shields.io/badge/Pandas-lightblue) ![Excel](https://img.shields.io/badge/Excel-green) ![Domain: Streaming & Strategy](https://img.shields.io/badge/Domain-Streaming%20%26%20Strategy-red)

---

## The Problem

Netflix's content library grew at extraordinary speed through the 2010s, but raw volume alone does not tell the full strategic story. The more revealing question is whether the platform was acquiring content indiscriminately, or deliberately shifting its mix toward serialised formats to drive long-term viewer retention.

This analysis examines 8,000+ titles added between 2013 and 2021 to identify the precise inflection point where that strategic shift occurred and confirm whether it represents a sustained commitment or a temporary fluctuation.

---

## Key Findings

| Finding | Detail |
|---|---|
| Peak growth | Content additions grew by over 18,000% between 2013 and 2019 (11 titles to 2,016 in a single year) |
| Post-peak deceleration | Additions fell to 1,498 by 2021, signalling a shift from volume acquisition to selective, quality-driven content |
| Strategic pivot confirmed | TV Shows grew from 21% of new additions in 2014 to a sustained 29-34% share from 2019 onwards |
| Four consecutive years of growth | TV Show share rose every year from 2015 to 2019 (25% to 29% to 32% to 34%), confirming deliberate strategy, not fluctuation |

> **Core insight:** Netflix has matured from a broad content aggregator into a platform optimising for hours retained, not titles added. The value of the library is no longer measured in volume.

---

## Business Questions

- How has the composition of the Netflix library evolved between 2013 and 2021?
- Can we identify the specific point where the platform prioritised serialised content over movies?
- Is the shift in content mix a sustained strategic commitment or a temporary fluctuation?
- Does the post-2019 deceleration in total additions signal a broader change in acquisition philosophy?

---

## Dataset

- **Source:** [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) (public, Kaggle)
- **Scope:** 8,000+ titles, 2013-2021
- **Integrity filters:** 10 null date entries removed to maintain time series integrity across the full analysis window

---

## Methodology

### Phase 1 - Strategic analysis (Excel)
Built PivotTable-based dashboards to model library growth and identify inflection points in acquisition strategy. Kept outputs accessible for non-technical stakeholders without sacrificing analytical depth.

### Phase 2 - Reproducibility pipeline (Python / pandas)
Reproduced the entire Excel workflow in Python to eliminate manual steps, reduce human error, and enable the same analysis to be refreshed against new data in minutes rather than hours. Logical parity was maintained between the Excel PivotTables and Python DataFrames throughout.

### Feature engineering
Extracted year-based features from acquisition dates to enable granular temporal grouping and year-on-year comparison across content types.

---

## Strategic Recommendations

**1. Test the retention hypothesis**
The sustained rise in TV Show share strongly suggests serialised content drives viewer retention, but this dataset cannot confirm it alone. Cross-referencing this content shift against subscriber churn data would validate whether the pivot is delivering measurable results.

**2. Apply to competitor benchmarking**
The same methodology can be applied to rival streaming platforms to identify which competitors are over-indexing on movies versus series. The Python pipeline makes this replication straightforward with any comparable dataset, giving strategy teams a repeatable tool for competitive intelligence.

**3. Use the deceleration curve for operational forecasting**
The post-2019 slowdown provides a defensible baseline for capacity planning. Applying a linear regression to this trajectory would generate a 3-5 year projection for infrastructure and storage scaling.

---

## Files

| File | Description |
|---|---|
| `netflix_content_mix.xlsx` | Primary Excel model including PivotTables and dashboards |
| `notebooks/` | Python reproduction pipeline for automated reporting |
| `outputs/` | Cleaned and transformed yearly content mix data exported from the Python pipeline |
| `images/` | Screenshots of core content trend visualisations for stakeholder review |



## Skills Demonstrated

`Python` `Pandas` `Excel` `PivotTables` `Feature engineering` `Time series analysis` `Data cleaning` `Strategic communication` `Workflow automation`
