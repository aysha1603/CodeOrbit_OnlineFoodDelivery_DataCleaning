# CodeOrbit_OnlineFoodDelivery_DataCleaning

## 1.Project Overview

This project was completed as part of the CodeOrbit Data Analyst Internship – Task 1.

The objective of this task is to clean and prepare an Online Food Delivery Dataset for further data analysis and visualization.

The data cleaning process was performed using WPS Spreadsheet.

## 2.Dataset

The dataset contains customer-related information such as:

- Age
- Gender
- Marital Status
- Occupation
- Monthly Income
- Educational Qualifications
- Family Size
- Customer Type
- Latitude
- Longitude
- Pin Code
- Output
- Feedback

## 3.Data Cleaning Steps

### Missing Value Check

All columns were checked for missing or blank values.

**Result:** No missing values were found.

### Duplicate Removal

Duplicate records were identified and removed.

- Original records: 388
- Duplicate records removed: 103
- Final records: 285

### Unnecessary Column Removal

The unnecessary `Unnamed: 13` column was removed from the dataset.

### Column Name Standardization

Column names were standardized for better readability and consistency.

Examples:

- `Marital Status` → `Marital_Status`
- `Family size` → `Family_Size`
- `Monthly Income` → `Monthly_Income`
- `Customer Type` → `Customer_Type`
- `Pin code` → `Pin_Code`

### Data Type Verification

Numeric and categorical fields were checked to ensure that the values were stored consistently.

### Formatting Consistency

Categorical fields such as Gender, Output, Customer Type, and Feedback were checked for formatting consistency.

## 4.Dataset Summary

| Metric | Value |
|---|---:|
| Original Records | 388 |
| Duplicate Records Removed | 103 |
| Final Records | 285 |
| Missing Values | 0 |
| Unnecessary Columns Removed | 1 |
| Final Columns | 13 |

## 5.Project Files

- `Online_Food_Delivery_Cleaned_Dataset_with_Log_and_Summary.xlsx` – cleaned dataset
- `Cleaning_Log` – documentation of cleaning activities
- `Summary` – summary of the cleaning process
- `README.md` – project documentation

## 6.Tools Used

- WPS Spreadsheet
- Excel-compatible `.xlsx` format
- GitHub

## 7.Objective

The main objective of this task is to transform the raw online food delivery dataset into a clean, consistent, and analysis-ready dataset.

The cleaned dataset can be used for:

- Data Analysis
- SQL Analysis
- KPI Analysis
- Dashboard Creation
- Data Visualization

## 8.Task Status

**CodeOrbit Data Analyst Internship – Task 1: Data Cleaning**

**Status: Completed ✅**
