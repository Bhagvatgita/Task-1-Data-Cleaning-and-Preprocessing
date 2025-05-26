# Task-1-Data-Cleaning-and-Preprocessing
Cleaning a raw sales dataset in Excel

# Objective
To clean a raw sales dataset that contains:
- Missing values
- Duplicate rows
- Inconsistent text formats
- Improper column names
- Incorrect data types
- Unformatted dates
# Tools Used
- Microsoft Excel
# Cleaning Steps Performed

## 1. Removed Duplicate Rows
- Used Data → Remove Duplicates on the full table.
- All exact duplicates were removed to ensure unique records.

## 2. Handled Missing Values
- Used Go To Special → Blanks to highlight null cells.
- Replaced missing values with "N/A" or appropriate default values manually.
- ## 3. Fixed Inconsistent Text Formats
- Standardized text entries like country and gender using:
  - =UPPER(cell) for uppercase standardization 
  - =PROPER(cell) for proper case 
- Replaced original cells using **Paste Special → Values**

## 4. Formatted Date Columns
- Changed the **Shipping Date** column format to `dd-mm-yy` using-
  - Right-click → **Format Cells → Custom → dd-mm-yy**

## 5. Renamed Column Headers
- All headers were converted to
  - Lowercase
  - No spaces (underscores used instead)
- Example: "Order ID" → `order_id`, "Shipping Date" → `shipping_date`

## 6. Checked and Corrected Data Types
- Ensured that:
  - `order_id` and `amount` are numbers
  - `shipping_date` and `order_date` are formatted as dates
- Used **Format Cells** option to apply the correct data types.

**Summary of Changes**

Issue                 Solution Applied                       
Duplicate Rows       Removed using "Remove Duplicates"         
Missing Values       Handled using "Go To Special → Blanks"    
Inconsistent Text    Standardized using UPPER/PROPER functions 
Date Format          Shipping date set to `dd-mm-yy`           
Column Names         Renamed to lowercase with underscores     
Data Types           Set using "Format Cells" in Excel         

**Task Completed Successfully**
