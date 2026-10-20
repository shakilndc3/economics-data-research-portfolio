# Internet Use Across World Bank Regions — 2019

## Overview
This project uses Microsoft Excel for the web to explore differences in Internet-use percentages across World Bank geographic regions in 2019.

It demonstrates an introductory research workflow: obtaining public data, cleaning observations, matching metadata, creating PivotTables, visualising results, and interpreting descriptive statistics.

## Research questions
1. How does average country-level Internet use vary across geographic regions?
2. Which regions show the greatest minimum-to-maximum spread in country-level Internet use?
3. Which countries have the highest and lowest Internet-use percentages within each region?

## Data source
- **Provider:** World Bank
- **Dataset:** World Development Indicators
- **Indicator code:** `IT.NET.USER.ZS`
- **Indicator:** Individuals using the Internet (% of population)
- **Reference year:** 2019
- **Source URL:** https://data.worldbank.org/indicator/IT.NET.USER.ZS

## Data structure
The analysis dataset contains:
- `Country Name`
- `Country Code`
- `Region`
- `Internet Use (%)`

## Methods
- Clean and validate country-level observations.
- Match geographic regions using World Bank country metadata.
- Exclude regional and income-group aggregates from country-level analysis.
- Exclude missing Internet-use values and unresolved region classifications from the regional calculations.
- Calculate regional means, minimums, maximums, and ranges.
- Use PivotTables and charts to compare the results.

## Interpretation principles
Regional means describe the average of available country-level percentages. They are not necessarily population-weighted regional rates.

A minimum-to-maximum range measures the distance between the two extremes; it does not describe the full distribution or establish the causes of regional differences.

## Limitations
The analysis is descriptive and restricted to one reference year. Results depend on data availability, the geographic classification, and the inclusion rules. Associations or regional differences do not establish causation.

## Workbook contents
- `Data`: downloaded World Bank observations
- `Metadata - Countries`: country and region metadata
- `WB_CLEAN`: cleaned working data
- `WB_ANALYSIS_DATA`: final analytical subset, if present
- `WB_PIVOT`: PivotTables, charts, and interpretations

*Confirm that these worksheet names match the final workbook.*

## Skills demonstrated
Excel for the web, XLOOKUP, data cleaning, metadata matching, PivotTables, descriptive statistics, visualisation, and research interpretation.

## Reproducibility
The project documents the source, indicator, reference year, and inclusion rules. Before final publication, record the download date, final number of included economies, and verified regional results.

## Future improvements
- Reproduce the summary statistics in R.
- Compare results across multiple years.
- Combine Internet-use data with additional socioeconomic indicators to investigate possible explanations for cross-country differences.
