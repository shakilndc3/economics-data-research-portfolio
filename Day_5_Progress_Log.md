# Day 5 Progress Log — Excel, Data Analysis & Research

**Date:** 20 October 2026  
**Status:** Completed  
**Focus:** PivotTables, PivotCharts, descriptive analysis, data cleaning, and research interpretation

## Project 1: ISP Customer Analysis

### Objective
Practise summarising customer data and answering business questions using Excel PivotTables and charts.

### Work completed
- Organised a 20-record fictional ISP customer dataset.
- Created a PivotTable comparing Active and Cancelled customers by region.
- Summarised total monthly bill values and customer counts by subscription plan.
- Compared average monthly bills and customer counts by acquisition channel.
- Created charts to visualise regional customer status, bill values by plan, and average bills by acquisition channel.
- Wrote findings, interpretations, and limitations for the analyses.
- Reviewed chart design to ensure that totals, averages, and counts were not misleadingly combined.

### Key analytical lessons
- PivotTable fields must match the research or business question.
- Counts, sums, and averages answer different questions.
- Chart titles, axes, units, and selected data ranges affect interpretation.
- Descriptive patterns do not establish causation.
- Fictional practice data demonstrate analytical skills but cannot support claims about actual ISP performance.

### Next improvement
Continue refining chart formatting and document the analysis workflow so the project can be reproduced by another person.

## Project 2: World Bank Internet Use Analysis — 2019

### Objective
Use a published international dataset to compare Internet-use percentages across World Bank geographic regions.

### Data source
- **Provider:** World Bank
- **Dataset:** World Development Indicators
- **Indicator:** `IT.NET.USER.ZS`
- **Measure:** Individuals using the Internet (% of population)
- **Reference year:** 2019
- **Source:** https://data.worldbank.org/indicator/IT.NET.USER.ZS

### Work completed
- Reviewed the downloaded World Bank data and country metadata.
- Created a cleaned worksheet with Country Name, Country Code, Region, and Internet Use (%).
- Used country metadata and XLOOKUP to retrieve regional classifications.
- Identified regional aggregates, missing Internet-use values, and missing region classifications.
- Developed inclusion rules to distinguish valid observations from records excluded from the regional analysis.
- Designed PivotTable analyses for regional averages, variation between countries, and country-level comparisons.
- Planned visualisations and drafted interpretation structures covering findings, meaning, and limitations.

### Key analytical lessons
- Missing values must not be treated as zero.
- Regional aggregates should not be counted as individual countries in a country-level regional average.
- A regional average, a minimum–maximum range, and a country-level comparison answer different analytical questions.
- The mean of country-level percentages is not necessarily the population-weighted Internet-use rate for a region.
- Data cleaning rules and the number of valid observations should be documented.

### Important reporting note
Record the final number of valid observations and the calculated regional results after checking the completed PivotTables. Do not report unverified values.

## Skills practised
- Excel for the web
- PivotTables and PivotCharts
- Data cleaning and validation
- XLOOKUP and metadata matching
- Descriptive statistics
- Chart selection and interpretation
- Research-question formulation
- Documentation and reproducibility

## Reflection
Day 5 connected spreadsheet skills with practical business questions and a public-data research exercise. The main lesson was that reliable analysis requires more than producing a chart: the source data, inclusion rules, calculations, and limitations must also be clear.

## Next session
- Verify the final World Bank analysis dataset and regional PivotTable.
- Finish the range summary and country-level comparison.
- Save both workbooks and document their contents in README files.
- Begin preparing data for reproducible analysis in R.
