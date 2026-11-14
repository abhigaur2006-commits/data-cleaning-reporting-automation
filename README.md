# Data Cleaning & Reporting Automation

An automated pipeline that cleans messy sales data and generates reports.

## Features
- Removes duplicates, including ones hidden by inconsistent formatting
- Standardizes text and mixed date formats
- Handles missing values (median by sub-category, most common value, or "Unknown")
- Generates an Excel report and an interactive visual summary
- One function, run_pipeline(), runs everything

## How to run
1. Open the notebook in Google Colab
2. Upload train.csv
3. Run all cells

## Tools
Python, Pandas, NumPy, Plotly, openpyxl
