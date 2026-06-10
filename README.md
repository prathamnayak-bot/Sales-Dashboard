# Sales Dashboard Project

## Overview
A Google Sheets sales dashboard built from messy CSV data.

## Sheets
- **Raw_data** — original dirty CSV, never edited
- **Clean_data** — formula-only cleaned data
- **Dashboard** — executive pivot dashboard with charts

## Tools Used
- Google Sheets
- QUERY, SUMIF, XLOOKUP, COUNTIF
- Data cleaning formulas (TRIM, PROPER, IFERROR, LET)

## Data Issues Fixed
- 10 country code variants standardised
- Mixed case status (Won/won/WON) normalised
- 2 broken dates handled silently
- Revenue, Month, Quarter columns derived

## How to Use
1. Paste raw CSV into Raw_data sheet
2. Clean_data formulas update automatically
3. Dashboard charts and pivots refresh instantly
