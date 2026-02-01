# Netflix Content Mix Over Time (Excel Analysis)

## Project Overview

This project looks at how Netflix’s content offering has changed over time, focusing on the balance between Movies and TV Shows. The aim is to demonstrate clear analysis and simple communication using Excel, without unnecessary complexity.

## Business Question

How has Netflix’s mix of Movies and TV Shows changed over time?

## Dataset

Source: Netflix Movies and TV Shows dataset (Kaggle)

Each row represents a title available on Netflix.

This analysis looks at the year each film or TV programme was added to Netflix, rather than when it was originally made.

## Tools Used

Microsoft Excel (data preparation, PivotTables and charts)

## Approach

Created a year field from the date each title was added to Netflix.

Analysed how many Movies and TV Shows were added each year.

Looked separately at:

Overall growth in content added each year

The share of Movies compared to TV Shows

Used two charts to keep the analysis clear and easy to understand.

## Key Findings

The number of titles added to Netflix increased quickly from the mid-2010s, reaching a peak around 2019.

Movies remained the largest type of content added each year.

Over time, TV Shows made up a larger share of new additions, settling at roughly one third of content added in recent years.

This suggests a gradual but sustained shift towards series content.

## Charts Included

Netflix content additions by year (Movies vs TV Shows)

Share of Netflix content additions by year

Screenshots of both charts are included in this repository so the findings can be viewed without opening the Excel file.

## Assumptions and Limitations

Titles with missing dates were excluded from the time-based analysis.

The project is descriptive only and does not attempt to predict future trends.

## Files

- netflix_content_mix.xlsx – Excel-based analysis and charts  
- images/ – screenshots of Excel charts  
- notebooks/ – Python notebook reproducing the analysis  
- outputs/ – Python-generated tables and charts

## Python Extension (Reproducibility & Automation)

This analysis was later reproduced in Python using pandas to demonstrate date cleaning, aggregation, and reproducible reporting. The Python workflow mirrors the original Excel-based logic and confirms the same conclusions about Netflix’s evolving content mix over time.

The purpose of this extension was to show how a business-focused analysis can be translated from Excel into code to support automation and scalability, while keeping the insight and conclusions consistent.


