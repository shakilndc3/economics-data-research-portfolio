# Economics, Data Analysis & Research Portfolio

## About this portfolio

This repository documents my ongoing development of practical skills in data management, quantitative analysis, and economics research.

## Current learning

### Day 2 — Excel Data Handling

**Skills practised:**
- Opening and saving CSV and Excel files
- Formatting spreadsheet data
- Sorting and filtering records
- Checking for missing values and duplicate records
- Documenting a data workflow

**Dataset:** Synthetic digital connectivity data created for practice.

**Important limitation:** The dataset is illustrative and does not represent verified statistics about Bangladesh.

## Future projects

- Excel data cleaning and exploratory analysis
- Statistical analysis using R
- Applied economics research using verified public datasets
- Research documentation and reproducible workflows

## Status

This portfolio is a work in progress. Projects will be added as I complete and verify them.

# Day 3 Progress Log — Excel Statistical Analysis

**Portfolio:** Economics, Data Analysis & Research  
**Learning stage:** Day 3  
**Project:** Descriptive statistics using Excel  
**Dataset:** Synthetic household digital-connectivity practice data  
**Status:** Completed

---

## 1. Learning objectives

The objective of Day 3 was to move from basic spreadsheet data handling to introductory statistical analysis in Microsoft Excel. The work focused on calculating summary statistics, applying a conditional formula, and interpreting results cautiously.

## 2. Skills practised

- Calculating totals with `SUM`.
- Calculating arithmetic means with `AVERAGE`.
- Counting numeric observations with `COUNT`.
- Identifying minimum and maximum values with `MIN` and `MAX`.
- Calculating the median with `MEDIAN`.
- Applying a simple logical condition with `IF`.
- Organising summary results in a separate worksheet.
- Interpreting descriptive statistics and documenting dataset limitations.

## 4. Excel formulas used

The following examples assume the monthly income values are in cells `B2:B13`. Adjust the cell references if the workbook layout differs.

| Measure | Excel formula | Result |
|---|---|---:|
| Total monthly income | `=SUM(B2:B13)` | BDT 367,000 |
| Mean monthly income | `=AVERAGE(B2:B13)` | BDT 30,583.33 |
| Number of numeric observations | `=COUNT(B2:B13)` | 12 |
| Minimum monthly income | `=MIN(B2:B13)` | BDT 15,000 |
| Maximum monthly income | `=MAX(B2:B13)` | BDT 52,000 |
| Median monthly income | `=MEDIAN(B2:B13)` | BDT 29,000 |
| Income range | `=MAX(B2:B13)-MIN(B2:B13)` | BDT 37,000 |

Example of a conditional classification formula:

```excel
=IF(B2>=30000,"At/above 30,000","Below 30,000")
```
## 8. Reflection

Day 3 strengthened the connection between spreadsheet skills and introductory quantitative analysis. The main lesson was not only how to calculate descriptive statistics in Excel, but also how to explain what those statistics show—and what they cannot establish.

### Day 4 — Excel Conditional Analysis

Practised Excel's `COUNTIF`, `SUMIF`, `COUNTIFS`, `SUMIFS`, and `XLOOKUP` functions using a synthetic digital-connectivity dataset. Analysed regional income, internet users, and internet-access records; applied multiple criteria; retrieved values using IDs; and organised results in a separate analysis worksheet.

## 2. Functions practised

| Function | What it does | Example from this exercise |
|---|---|---|
| `COUNTIF` | Counts cells matching one condition | `=COUNTIF(B2:B11,"Dhaka")` |
| `SUMIF` | Adds values matching one condition | `=SUMIF(B2:B11,"Dhaka",D2:D11)` |
| `COUNTIFS` | Counts records matching multiple conditions | `=COUNTIFS(B2:B11,"Chattogram",E2:E11,"Yes")` |
| `SUMIFS` | Adds values matching multiple conditions | `=SUMIFS(D2:D11,B2:B11,"Chattogram",E2:E11,"Yes")` |
| `XLOOKUP` | Finds an identifier and returns a related value | `=XLOOKUP(104,A2:A11,D2:D11,"Not Found")` |

**Key learning:** Using conditional formulas to answer structured data questions, validate results, and prepare for descriptive statistics and research-oriented data analysis.

**Key learning notes
- `COUNTIF` and `SUMIF` handle one condition; `COUNTIFS` and `SUMIFS` handle multiple conditions.
- In `SUMIF`, the criteria range and sum range must align row by row.
- In `SUMIFS`, the sum range comes first, followed by each criteria range and criterion.
- `XLOOKUP` can return a value from a different column using an ID, and its optional not-found argument can make missing matches explicit.
- Separating raw data from an `ANALYSIS` sheet makes calculations easier to review and present.
- Currency formatting changes how a numeric result is displayed; it does not change the underlying value.

**Tools:** Microsoft Excel 

##Reflection
I practised turning questions about regions, income, internet users, and access into reproducible Excel formulas. The results provide a foundation for later descriptive analysis and for repeating similar calculations in R.

## Data and interpretation caveat
The dataset is synthetic and contains only ten records. These results demonstrate Excel techniques; they must not be interpreted as evidence about actual internet use, household income, or regional conditions in Bangladesh.
