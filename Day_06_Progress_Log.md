# Day 6 Progress Log — Research Foundations and Real-World Data

**Project:** Study Abroad 2027 / Research Initiative / Excel  
**Research project ID:** `BD-DIGITAL-01`  
**Date recorded:** 25 October 2026  
**Status:** Exploratory learning and preliminary research design

## 1. Learning objectives

- Understand what a research question and hypothesis do.
- Identify dependent, independent and control variables.
- Read an official development indicator and its metadata.
- Distinguish internet users from internet subscriptions.
- Interpret data cautiously and identify what the data cannot establish.
- Organize a research workbook and begin a descriptive visualization.

## 2. Data exercise: Bangladesh internet use

- **Publisher/database:** World Bank, World Development Indicators (WDI)
- **Indicator:** Individuals using the Internet (% of population)
- **Indicator code:** `IT.NET.USER.ZS`
- **Country:** Bangladesh (`BGD`)
- **Latest nonblank year in the workbook:** 2024
- **Recorded value:** `53.42171316` (% of population; approximately 53.42%)
- **Underlying source organization:** International Telecommunication Union (ITU), World Telecommunication/ICT Indicators Database

Sources:
- [World Bank indicator page](https://data.worldbank.org/indicator/IT.NET.USER.ZS?locations=BD)
- [WDI indicator metadata](https://databank.worldbank.org/metadataglossary/world-development-indicators/series/IT.NET.USER.ZS)
- [ITU DataHub](https://datahub.itu.int/)

The indicator refers to people who used the internet from any location during the preceding three months. It is a people-based measure, not a count of subscriptions or connections.

## 3. Industry arithmetic exercise

AMTOB industry statistics for July 2026 were used for an arithmetic check:

- Mobile internet subscriptions: 121.52 million
- ISP + PSTN subscriptions: 15.23 million
- Calculated total: 136.75 million
- Published total: 136.75 million
- Difference at displayed precision: 0.00 million

Source: [AMTOB industry statistics](https://www.amtob.org.bd/home/industrystatics)

**Interpretation caution:** These are subscription counts, not unique people. The arithmetic match does not prove the categories represent unique individuals.

## 4. Preliminary research design

**Topic:** Digital connectivity and the transformation of cable TV businesses in Bangladesh.

**Research question:** What factors are associated with declining cable TV subscriptions among local providers in Bangladesh?

**Preliminary hypothesis:** Cable TV providers experiencing greater competition from streaming-video services may experience larger declines in subscriptions, after accounting for factors such as price, service outages, provider size and local internet availability.

| Role | Proposed variable |
|---|---|
| Dependent variable | Annual percentage change in active cable TV subscriptions for each provider |
| Main independent variable | A measurable indicator of streaming-video competition or customer use of online video services |
| Potential controls | Monthly price, service outages, provider size and local internet availability |
| Unit of analysis | A cable TV provider observed over a defined period, if consistent provider-level data can be obtained |

This is a preliminary design, not a tested model or established result.

## 5. Skills practised

- Spreadsheet organization and working with a clean analysis table.
- Reading source metadata and identifying an indicator code.
- Interpreting percentage-of-population data.
- Distinguishing people, subscriptions and connections.
- Formulating a research question and a testable hypothesis.
- Identifying dependent, independent and control variables.
- Writing limitations and avoiding unsupported causal claims.
- Checking a published arithmetic total.
- Creating and troubleshooting a data visualization.

## 6. Workbook structure reviewed

The uploaded workbook contains these worksheets:

1. `Original WDI Data` — source observations and metadata fields; preserve as the raw-data record.
2. `Source Metadata` — publisher, database, indicator, unit, source organization and API metadata.
3. `Clean_Analysis` — cleaned Bangladesh observations, structured table and chart.
4. `Research_Notes` — indicator interpretation, answers, research question, hypotheses, variables and limitations.
5. `Industry_Data` — AMTOB subscription arithmetic check.
6. `Research_Design` — preliminary research topic, question, hypothesis and variable design.
7. `Read Me` — workbook usage notes.

The reviewed workbook has a named Excel table `BangladeshInternetUse` over `A7:B36`. Its chart is an XY scatter chart with one series, X values `A8:A36` (years) and Y values `B8:B36` (internet-use values). Check the rendered chart in Excel for the web and add clear chart and axis titles before treating the visualization as presentation-ready.

## 7. Limitations and interpretation

The WDI internet-use indicator does not measure streaming-video use, cable TV subscriptions, customer switching, prices or service quality. It cannot establish whether increased internet use causes cable TV subscriptions to decline.

The AMTOB subscription categories are not unique-user counts. The two sources describe different concepts and should not be combined on a common axis as though they measured the same thing.

Provider-level cable TV subscription data and a defensible measure of streaming-video competition are still needed to investigate the research question.

## 8. Next steps

1. Verify chart appearance and add chart/axis titles in Excel for the web.
2. Search for reliable provider-level cable TV subscription data by year.
3. Identify a measurable and credible proxy for streaming-video competition.
4. Define the study period, geographic scope and sampling strategy.
5. Keep a source log and record actual learning hours going forward.

## 9. Evidence and claims policy

This log records learning exercises and a preliminary research design. It does **not** claim that a research paper has been completed, that results have been statistically tested, or that the work has been published.

Daily study hours were not recorded in the available notes and are therefore left unspecified.
