SWYNEX — Data Cleaning \& Preparation

Project Overview

This project is completed as part of Task1 of the SWYNEX internship. The objective is to inspect a raw retail sales dataset, evaluate its data quality, and prepare it for reliable analysis using Microsoft Excel.

Objectives

Identify missing values.
Detect duplicate records.
Verify data types.
Check consistency in text fields.
Validate numerical values and transaction totals.
Document the inspection and cleaning process.

Dataset Information

Dataset: Retail Sales Dataset
Format: CSV / Excel
Original records: 15,600
Original columns: 9
Tool used: Microsoft Excel

Columns

1. Transaction ID
2. Date
3. Customer ID
4. Gender
5. Age
6. Product Category
7. Quantity
8. Price per Unit
9. Total Amount

Data Quality Checks

Missing Values
Checked all nine columns for missing values. The initial inspection found 9134 missing values.

Duplicate Records
Checked for completely duplicated rows. The initial inspection found 600 duplicate rows.

Data Types
Reviewed date, identifier, text, and numerical columns to ensure they used appropriate formats.

Text Consistency
Inspected Gender, Product Category, and Customer ID for inconsistent values.

Numerical Validation
Reviewed Age, Quantity, and Price per Unit for invalid values.

Transaction Amount Validation
Compared Total Amount with Quantity multiplied by Price per Unit. The initial dataset validation found  mismatches.

Files and Folders

data/raw/ — Original dataset preserved unchanged.
data/cleaned/ — Final cleaned dataset.
documentation/ — Cleaning report and supporting documentation.
screenshots/ — Evidence of the cleaning and validation process.
Data\_Cleaning\_Log.xlsx — Log of issues checked and actions taken.

Tools Used

Microsoft Excel
GitHub for project versioning and sharing

Key Learning

This project provided practical experience in inspecting data quality, validating transaction amounts, documenting data preparation, and preparing a dataset for further analysis.

Conclusion

The dataset was systematically checked for common data quality issues. Findings and any corrections were documented to maintain transparency and support reliable downstream analysis.

