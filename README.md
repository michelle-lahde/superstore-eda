# superstore Sales - Exploratory Data Analysis

![Dashboard](excel/Superstore_Sales_Summary_Page.png)

## Overview
Exploratory data analysis of 9,800 US retail orders from a sample superstore dataset covering 2015–2018.
Analysed using Excel to uncover regional sales patterns, customer behaviour, and seasonal trends.

## Key Findings
1. **Technology outperforms the other categories.** It has 3× fewer orders than Office Supplies but generates nearly equal revenue → Individual technology purchases have higher values.
2. **California drives 20% of all revenue** from just one state. The business has a heavy geographic concentration risk in the West. 
3. **Sales are right-skewed** because the mean ($231) is 4x the median ($54) due to large tech orders.
4. **Clear seasonality every year.** Sales peak regularly in November through December, pointing to holiday and end-of-year spend cycles. 
5. **Corporate buyers use faster shipping** → Higher first class usage that Consumer segment despite lower order volume.
6. **Despite having the largest segment by volume,** Consumer customers use Standard Class at a higher rate than Corporate. Suggesting Corporate  buyers are more time-sensitive or have larger shipping budgets. 

## Tool Used
- Microsoft Excel for data cleaning, PivotTables, charts, and dashboard.

## Files
- [Superstore Analysis Workbook](excel/Superstore_Analysis.xlsx) — Excel workbook with cleaned data, PivotTables, and summary dashboard
- [Raw Dataset](data/train.csv) — raw dataset (Sample Superstore, via Kaggle)

## Data Cleaning
- 11 missing postal codes (Burlington, VT) →  Filled with 05401 
- Duplicate Order IDs →  Kept because one order contains multiple line items 
- Repeat customer IDs →  Kept because repeat customers are valid data 
- Sales outliers over $10K →  Kept because legitimate high-value tech products 

## How to Run
1. Download `data/train.csv`
2. Open `excel/Superstore_Analysis.xlsx` workbook to explore PivotTables and dashboard
