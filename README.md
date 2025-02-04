# Movies-Analysis

# Movie Dataset Cleaning

## Overview
This repository contains the cleaned version of a movie dataset. The original dataset (`movies.csv`) had various inconsistencies, missing values, and formatting issues. Using **pandas** and **numpy** in **Jupyter Notebook**, the dataset was cleaned and stored as `Final_cleaned_dataset.xls`.

## Technologies Used
- **Python**
- **pandas**
- **numpy**
- **Jupyter Notebook**

## Cleaning Process
The following transformations were applied to clean the dataset:

1. **Handling Missing Values**  
   - Removed rows/columns with excessive missing values.  
   - Replaced Null values with 0 and not available as per data type of column.

2. **Data Formatting & Standardization**  
   - Converted column names to a consistent format (lowercase, underscore-separated). 
   - Converted date column's datatype as date.

3. **Duplicates Removal**  
   - Checked for duplicate rows and removed duplicate rows.

4. **Data Type Corrections**  
   - Converted columns to appropriate data types (e.g., numerical, datetime, categorical).  
   - Removed unnecessary whitespace in text columns.

5. **Feature Engineering (if any)**  
   - Derived new meaningful features from existing columns.  

## Final Output
- The cleaned dataset is saved as `Final_cleaned_dataset.xls` in Excel format.
