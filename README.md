# Netflix Content Strategy Analysis

## Executive Summary: Tracking the Shift in Content Mix

This project provides a longitudinal analysis of Netflix's content acquisition strategy between 2013 and 2021. By examining year-on-year additions of Movies versus TV Shows across 8,000+ titles, the analysis identifies the precise inflection point at which TV Shows grew from 21% to a sustained ~33% of all new content, signalling a platform-wide pivot from volume-based acquisition to long-term viewer retention.

## Business Questions

1. How has the composition of the Netflix library evolved over the last decade?
2. Can we identify the specific point where the platform prioritised serialised content?
3. What is the quantified magnitude of that shift, and is it a sustained strategic commitment or a temporary fluctuation?
4. Does the growth trajectory of new additions suggest a shift toward long-term viewer retention?

## My Approach: Bridging Excel and Python

To ensure consistency and scalability, this project was executed in two phases.

**Phase 1: Strategic Analysis in Excel.** Using PivotTables and visual dashboards, I modelled the growth of the content library to identify inflection points in acquisition strategy. This ensured the findings were accessible to non-technical stakeholders.

**Phase 2: Reproducibility through Python.** To demonstrate automation capabilities, I reproduced the entire Excel workflow using Python and pandas. This transition eliminates manual steps from the reporting process, reducing human error and enabling the same analysis to be refreshed against new data in minutes rather than hours.

## Key Findings

**Finding 1: The Growth Peak**
Content additions grew by over 18,000% between 2013 and 2019, from 11 titles to a peak of 2,016 in a single year, representing the platform's most aggressive expansion period. A clear deceleration followed post-2019, with additions falling to 1,498 by 2021, suggesting a strategic shift from broad catalogue expansion to selective, quality-driven acquisition.

**Finding 2: The Strategic Pivot**
TV Shows grew from 21% of new additions in 2014 to a sustained 29–34% share from 2019 onwards. Crucially, this share increased every year for four consecutive years (25% to 29% to 32% to 34%), confirming this is a deliberate strategic commitment rather than a temporary fluctuation.

**Finding 3: The Strategic Implication**
The post-2019 deceleration in total content, combined with the sustained rise in TV Show share, signals that Netflix is no longer competing on catalogue volume. The platform has pivoted to retention-focused content, a signal with direct implications for competitor benchmarking and capacity planning.

## Strategic Recommendations

**1. Retention via Serialisation**
The sustained rise in TV Show share confirms that the platform is betting on long-term viewer retention rather than immediate acquisition. Cross-referencing this content shift against publicly available subscriber churn data would test whether serialised content drives measurable retention improvements, a hypothesis this dataset strongly suggests but cannot confirm alone.

**2. Competitor Benchmarking**
This methodology can be applied directly to competitive intelligence. By performing the same analysis on rival streaming services, we can identify which competitors are over-indexing on movies versus series, enabling targeted content procurement strategy. The Python pipeline makes this replication straightforward with any comparable dataset.

**3. Operational Forecasting**
The established growth and post-2019 deceleration curve provides a baseline for capacity planning. Applying a linear regression to the post-2019 trajectory would generate a defensible projection for infrastructure and storage scaling over a 3–5 year horizon.

## Conclusion

The primary insight is that Netflix has matured from a broad content aggregator into a platform prioritising bingeable, serialised content. The value of the library is no longer measured in titles added, but in hours retained. Any future analysis should therefore prioritise engagement duration and return-viewing rates over catalogue volume, metrics that would directly inform both content investment decisions and subscriber growth modelling.

## Technical Methodology

**Data Cleansing:** Filtered 10 null date entries to maintain time series integrity across the 2013–2021 analysis window.

**Feature Engineering:** Extracted year-based features from acquisition dates to enable granular temporal grouping.

**Reproducibility:** Maintained logical parity between Excel PivotTable visualisations and Python-based DataFrames, enabling automated refresh as new data becomes available.

## Files Included

`images/` – Screenshots of the core content trend visualisations for quick stakeholder review.

`notebooks/` – The Python reproduction pipeline for automated reporting.

`outputs/` – The cleaned and transformed yearly content mix data exported from the Python pipeline.

`README.md` – Project documentation and strategic analysis write-up.

`netflix_content_mix.xlsx` – The primary Excel-based analytical model including PivotTables and dashboards.
