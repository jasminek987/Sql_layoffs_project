# Layoffs Data Analysis (SQL)

Cleaning and exploratory analysis of global tech layoffs
using MySQL.

## Business Problem
Which companies and industries cut the most staff, how
layoffs changed over time, and which companies shut down
completely.

## Dataset
Global tech layoffs, ____ rows, covering ____ to ____.

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

## Files
- `data_cleaning.sql`
- `eda.sql`
