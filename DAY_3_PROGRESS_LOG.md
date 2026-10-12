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

## 3. Dataset overview

The practice dataset contains **12 fictional household observations** with these variables:

| Variable | Description |
|---|---|
| `Household_ID` | Identifier assigned to each fictional household |
| `Monthly_Income_BDT` | Fictional monthly household income in Bangladeshi taka |
| `Internet_Hours_Weekly` | Fictional weekly internet-use hours |
| `Internet_Expense_BDT` | Fictional household internet expense in Bangladeshi taka |

The dataset was created for learning and formula practice. It is not verified survey data.

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

This formula classifies each fictional household according to whether its monthly income is at least BDT 30,000. The threshold is a practice rule, not an official income category.

## 5. Summary and interpretation

- The sum of monthly incomes in the fictional sample is **BDT 367,000**.
- The mean is approximately **BDT 30,583.33** per household.
- The median is **BDT 29,000**, meaning half of the observations are at or below this value and half are at or above it.
- The minimum and maximum are **BDT 15,000** and **BDT 52,000**, respectively.
- The range is **BDT 37,000**, showing the difference between the highest and lowest observations in this sample.

The range provides a basic indication of spread, but it does not describe the full distribution. It is not sufficient by itself to measure income inequality.

## 6. Limitations and responsible interpretation

This is a **synthetic dataset containing only 12 fictional observations**. Therefore:

- The results describe only the practice data.
- They must not be presented as estimates of actual household income, internet use, or internet expenditure in Bangladesh.
- The data cannot support population-level conclusions or causal claims.
- A real empirical study would require verified data, a suitable sampling or data-collection design, clear variable definitions, and appropriate analytical methods.

This limitation is an important part of responsible research practice: statistical calculations can be correct even when the data are not suitable for real-world inference.

## 7. Project files

The Day 3 work is intended to be documented alongside the workbook and this progress log in the `economics-data-research-portfolio` repository.

Suggested filenames:

- `Day3_Excel_Statistics.xlsx` — workbook containing the practice data and summary calculations.
- `DAY_3_PROGRESS_LOG.md` — this learning and analysis record.

Only include files that have actually been created and checked before committing them to the repository.

## 8. Reflection

Day 3 strengthened the connection between spreadsheet skills and introductory quantitative analysis. The main lesson was not only how to calculate descriptive statistics in Excel, but also how to explain what those statistics show—and what they cannot establish.

## 9. Next steps

1. Check that the workbook formulas return the results documented above.
2. Confirm that the workbook and this log use consistent variable names and cell references.
3. Review the workbook for clear labels, number formats, and readable summary results.
4. Continue to more advanced Excel analysis, such as percentage calculations, sorting and filtering by conditions, and charts.
5. When moving toward empirical economics research, use a verified public dataset and document its source, definitions, and limitations.

---

*Prepared as a learning record for an economics and data-analysis portfolio. All household figures in this exercise are synthetic and illustrative.*
