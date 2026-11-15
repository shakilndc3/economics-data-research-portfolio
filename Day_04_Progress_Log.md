# Day 4 Progress Log — Excel Conditional Analysis

**Date:** 14 October 2026  
**Focus:** Conditional formulas and lookup functions in Excel  
**Dataset:** Fictional digital-connectivity practice data (synthetic; not official Bangladesh statistics)

## 1. Learning objectives

- Apply conditions to count records and summarize values.
- Combine multiple conditions in a single calculation.
- Retrieve a related value using an identifier.
- Present results clearly in a separate analysis sheet.

## 2. Functions practised

| Function | What it does | Example from this exercise |
|---|---|---|
| `COUNTIF` | Counts cells matching one condition | `=COUNTIF(B2:B11,"Dhaka")` |
| `SUMIF` | Adds values matching one condition | `=SUMIF(B2:B11,"Dhaka",D2:D11)` |
| `COUNTIFS` | Counts records matching multiple conditions | `=COUNTIFS(B2:B11,"Chattogram",E2:E11,"Yes")` |
| `SUMIFS` | Adds values matching multiple conditions | `=SUMIFS(D2:D11,B2:B11,"Chattogram",E2:E11,"Yes")` |
| `XLOOKUP` | Finds an identifier and returns a related value | `=XLOOKUP(104,A2:A11,D2:D11,"Not Found")` |

*Note: The examples above assume the data is on a worksheet where columns A–E contain ID, Region, Internet Users, Monthly Income (BDT), and Internet Access respectively. If using the `DATA` sheet from the workbook, prefix the ranges with `DATA!`.*

## 3. Results checked

| Analysis question | Result |
|---|---:|
| Number of records in Dhaka | 3 |
| Total monthly income in Dhaka | BDT 97,000 |
| Total monthly income in Chattogram | BDT 69,000 |
| Total income for records with internet access | BDT 169,000 |
| Total income above BDT 25,000 | BDT 123,000 |
| Total internet users in Dhaka | 255 |
| Chattogram records with internet access | 2 |
| Dhaka records with internet access | 3 |
| Records with income above BDT 20,000 and internet access | 6 |
| Rajshahi records without internet access | 2 |
| Chattogram income with internet access | BDT 50,000 |
| Dhaka income with internet access | BDT 97,000 |
| Khulna income without internet access | BDT 20,000 |
| Internet users in Chattogram with internet access | 135 |
| Income associated with ID 104 | BDT 35,000 |
| Income associated with ID 101 | BDT 30,000 |
| Region associated with ID 106 | Chattogram |
| Internet-access status for ID 107 | No |
| Search for nonexistent ID 999 | Not Found |

## 4. Key learning notes

- `COUNTIF` and `SUMIF` handle one condition; `COUNTIFS` and `SUMIFS` handle multiple conditions.
- In `SUMIF`, the criteria range and sum range must align row by row.
- In `SUMIFS`, the sum range comes first, followed by each criteria range and criterion.
- `XLOOKUP` can return a value from a different column using an ID, and its optional not-found argument can make missing matches explicit.
- Separating raw data from an `ANALYSIS` sheet makes calculations easier to review and present.
- Currency formatting changes how a numeric result is displayed; it does not change the underlying value.

## 5. Reflection

I practised turning questions about regions, income, internet users, and access into reproducible Excel formulas. The results provide a foundation for later descriptive analysis and for repeating similar calculations in R.

## 6. Data and interpretation caveat

The dataset is synthetic and contains only ten records. These results demonstrate Excel techniques; they must not be interpreted as evidence about actual internet use, household income, or regional conditions in Bangladesh.

## 7. Next steps

- Practise checking formulas against the source rows.
- Learn PivotTables and PivotCharts to summarize data by region and access status.
- Begin research fundamentals alongside Excel practice, then reproduce selected calculations in R when the R-learning phase begins.
