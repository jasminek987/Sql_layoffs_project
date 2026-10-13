# Layoffs Data Analysis (SQL)

Cleaning and exploratory analysis of global tech layoffs
using MySQL.

## Business Problem
Which companies and industries cut the most staff, how
layoffs changed over time, and which companies shut down
completely.

## Dataset
Global tech layoffs, 1999 rows, covering 2020-03-11 to 2023-03-06.

## Tools
MySQL, MySQL Workbench

## Data Cleaning
- Removed duplicate records using ROW_NUMBER and a CTE
- Standardised inconsistent company and industry names
- Converted date column from text to DATE type
- Handled null and blank values
- Dropped columns not needed for analysis

## Analysis
- Total layoffs by company
- Layoffs by year
- Companies that laid off 100% of staff
- Top 3 companies by layoffs per year (DENSE_RANK + CTEs)
- Rolling monthly total of layoffs (window function)

## Key Findings
1. 18150 had the highest total layoffs at Amazon employees.
2. 2022 was the worst year, with 161711 layoffs.
3. 116 companies shut down entirely.

## Files
- `Data_cleaning.sql`
- `Eda.sql`
