# DSA2040A_ET_Exam_Kath_041
Ingabire Catherine-671041

## Project Overview
This project demonstrates the Extract and Transform phases of an ETL process using the Online Retail dataset from Kaggle. The objective was to profile, clean, and transform raw sales data to prepare it for analysis.

---

## 1. Extract Phase
**File:** etl_extract.ipynb  
- Loaded the dataset from Kaggle.
- Performed data profiling using pandas (`info()`, `describe()`).
- Identified data quality issues such as missing CustomerID values, duplicates, and negative quantities.
- Created incremental and validated datasets.

**Outputs:**
- data/incremental_data.csv  
- data/validated_full.csv  
- data/validated_incremental.csv

---

## 2. Transform Phase
**File:** etl_transform.ipynb  
- Removed duplicate rows.
- Filled missing values for CustomerID and Description.
- Fixed negative Quantity values.
- Converted InvoiceDate to datetime format and extracted Year and Month.
- Created a new column: TotalCost = Quantity × UnitPrice.
- Standardized column names to lowercase and underscore format.

**Outputs:**
- transformed/transformed_full.csv  
- transformed/transformed_incremental.csv

---

## Tools Used
- Python 3.x  
- Pandas library  
- Visual Studio Code (VS Code)  
- Git & GitHub

---

## Author
**Name:** Ingabire Catherine  
**ID:** 041  
**Course:** DSA 2040A – Statistical Computing
