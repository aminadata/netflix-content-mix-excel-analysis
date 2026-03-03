# Netflix Content Strategy Analysis

## Executive Summary: Tracking the Shift in Content Mix
This project provides a longitudinal analysis of Netflix’s content acquisition strategy. By examining the year over year additions of Movies versus TV Shows, the analysis quantifies the platform’s strategic pivot toward serialised content. The findings provide clear visibility into how Netflix matured its library from a film dominant catalogue to a balanced ecosystem, demonstrating a capability to extract actionable trends from unstructured time series data.

## Business Questions
How has the composition of the Netflix library evolved over the last decade?

Can we identify the specific point where the platform prioritised serialised content?

Does the growth trajectory of new additions suggest a shift toward long term viewer retention?

## My Approach: Bridging Excel and Python
To ensure consistency and scalability, this project was executed in two phases.

Phase 1: Strategic Analysis in Excel. Using PivotTables and visual dashboards, I modelled the growth of the content library to identify inflection points in acquisition strategy. This ensured the findings were accessible to non technical stakeholders.

Phase 2: Reproducibility through Python. To demonstrate automation capabilities, I reproduced the entire Excel workflow using Python and pandas. This transition shows how a manual analysis can be scaled into a robust, repeatable pipeline, reducing the risk of human error in recurring reports.

## Key Findings
The Growth Peak: The platform’s content acquisition accelerated significantly in the mid 2010s, reaching a peak deployment in 2019.

The Strategic Pivot: While Movies remain the primary volume driver, TV Shows now consistently represent approximately one third of all new content. This sustained shift highlights a clear strategy to drive recurring engagement through serialised storytelling.

Scalable Insights: The analysis confirms that data backed trends identified in Excel are fully reproducible through automated scripts, allowing for real time monitoring as new data becomes available.

## Strategic Recommendations
The data highlights a clear pivot from volume based acquisition to retention focused content strategy. Based on this analysis, I have identified three strategic implications:

Retention via Serialisation: The shift toward TV shows confirms that the platform is betting on long term viewer retention rather than immediate acquisition. We should investigate if this correlates with reduced subscriber churn rates in specific regions.

Competitor Benchmarking: This methodology can be applied to competitive intelligence. By performing the same analysis on rival streaming services, we can identify which competitors are over indexing on movies versus series, allowing for targeted content procurement strategies.

Operational Forecasting: The established growth trajectory provides a baseline for future capacity planning. We should use this model to forecast the required server and storage scaling based on the projected shift in content mix.

## Conclusion: The "So What?"
The primary insight is that Netflix has matured from a broad content aggregator into a specialised platform prioritising bingeable content. For a business stakeholder, this means the value of the platform is no longer just in the number of titles added, but in the engagement duration those titles generate. Any future data projects should shift focus from content quantity to viewer engagement metrics to better align with the platform's current strategic direction.

## Technical Methodology
Data Cleansing: Filtered null date entries to maintain time series integrity.

Feature Engineering: Extracted year based features from acquisition dates to enable granular temporal grouping.

Reproducibility: Maintained logical parity between Excel visualisations and Python based data frames.

## Files Included
netflix_content_mix.xlsx – The primary Excel based analytical model.

notebooks/ – The Python reproduction pipeline for automated reporting.

images/ – Visualisations of the core content trends for quick stakeholder review.

#### This analysis demonstrates a commitment to both clear data storytelling and the technical rigour required to automate business reporting.
