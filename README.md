# KPMG Data Analysis Using Microsoft Excel

A portfolio project analyzing customer demographics, transactions, new-customer prospects, and customer lifetime value (CLV) using Microsoft Excel.

## Project overview

The project brief describes six tasks:
1. Data cleaning
2. Customer segmentation
3. Transaction analysis
4. New customer insights
5. Customer lifetime value (CLV) analysis
6. Executive summary and recommendations

The project files supplied with this repository include the original multi-sheet dataset workbook, five task workbooks, the course brief, and the executive summary/recommendations PDF.

## Repository structure

```text
kpmg-excel-analysis-github/
├── data/
│   └── raw/
│       └── KPMG_Final_Project_Dataset.xlsx
├── workbooks/
│   ├── 01_Data_Cleaning.xlsx
│   ├── 02_Customer_Segmentation.xlsx
│   ├── 03_Transaction_Analysis.xlsx
│   ├── 04_New_Customer_Insights.xlsx
│   └── 05_Customer_Lifetime_Value_CLV.xlsx
├── docs/
│   ├── KPMG_Excel_Project_Brief.pdf
│   └── 06_Executive_Summary_and_Recommendations.pdf
├── screenshots/
├── notes/
├── .gitignore
└── README.md
```

## Dataset

`data/raw/KPMG_Final_Project_Dataset.xlsx` contains four sheets:
- `Customer_Address`
- `Customer_Demographic`
- `Transactions`
- `New_Customer_List`

The source brief describes fields for customer addresses and property valuation, customer demographics and job information, product transactions, and prospective customers.

## Analysis tasks

### 1. Data cleaning
Clean duplicate or incomplete records, standardize state and address formats, and correct inconsistent demographic and category values.

Workbook: `workbooks/01_Data_Cleaning.xlsx`

### 2. Customer segmentation
Summarize customers by wealth segment, gender, and job industry. Compare customer counts, tenure, purchase behavior, and wealth-segment distribution.

Workbook: `workbooks/02_Customer_Segmentation.xlsx`

### 3. Transaction analysis
Review monthly sales trends, product/brand performance, and customer purchase behavior, including high-value customers.

Workbook: `workbooks/03_Transaction_Analysis.xlsx`

### 4. New customer insights
Explore prospective customer demographics, state-level distribution, property valuation, and potential revenue indicators.

Workbook: `workbooks/04_New_Customer_Insights.xlsx`

### 5. Customer lifetime value (CLV)
Calculate customer lifetime value and compare average CLV across customer segments and demographics.

Workbook: `workbooks/05_Customer_Lifetime_Value_CLV.xlsx`

### 6. Executive summary and recommendations
The supplied PDF summarizes reported findings and recommends targeted marketing for high-CLV customers, expansion in locations with higher new-customer demand, and product improvements based on transaction performance.

Document: `docs/06_Executive_Summary_and_Recommendations.pdf`

## Selected findings in the supplied executive summary

The provided summary reports:
- Mass Customer is the largest wealth segment.
- Male customers make more bike-related purchases than female customers.
- October, May, July, August, and January are listed as months with the highest sales.
- Giant Bicycle is identified as the top-selling brand, and Standard as the top product line.
- New South Wales is reported as the state with the highest number of new customers.
- Manufacturing and Financial Services are reported as the highest-CLV industries.

These are transcribed from the supplied summary document and have not been independently recalculated in this README.

## How to use

1. Download and extract the ZIP archive.
2. Open the `.xlsx` files with Microsoft Excel or a compatible spreadsheet application.
3. Review the course brief in `docs/` for the original task requirements.
4. Add screenshots of completed charts or workbook views to `screenshots/`.
5. Update this README if you verify or improve any findings.

## Upload to GitHub

### Browser upload
1. Create a new GitHub repository, for example `kpmg-excel-data-analysis`.
2. Extract this ZIP on your computer.
3. Open the extracted folder and upload its contents to GitHub using **Add file → Upload files**.
4. Commit the changes.

If GitHub does not preserve empty folders, the `.gitkeep` placeholders in this repository keep the folders visible.

### GitHub Desktop
Alternatively, add the extracted folder as a local repository in GitHub Desktop and publish it to GitHub.

## Privacy and data handling

The workbook may contain customer-level information. Before making this repository public, confirm that you have permission to publish the data and remove or anonymize any personal or confidential information if needed. If unsure, keep the repository private and publish only the README, screenshots with sensitive information hidden, and non-sensitive analysis outputs.

## Notes

- The source file name `Taks 3 Transaction Analysis` has been standardized to `03_Transaction_Analysis.xlsx` for clarity.
- The executive summary PDF is included as a supplied project artifact; its findings are presented as reported rather than independently verified.
