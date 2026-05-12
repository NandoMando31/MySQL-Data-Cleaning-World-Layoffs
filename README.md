# World Layoffs: Data Cleaning in MySQL 📉🧹

## 📌 Project Overview
This project focuses on a complete data cleaning process of a "World Layoffs" dataset using **MySQL**. The goal was to transform raw, messy data into a clean, structured format suitable for Exploratory Data Analysis (EDA).

## 🛠️ Skills & SQL Concepts Applied
- **Data Staging:** Creating auxiliary tables to preserve raw data integrity.
- **Duplicate Removal:** Identifying and deleting redundant records using `ROW_NUMBER()` and **CTEs**.
- **Standardization:** Using `TRIM`, `TRAILING`, and `LIKE` to fix inconsistent strings and categories.
- **Date Conversion:** Transforming text columns into proper `DATE` formats using `STR_TO_DATE`.
- **Null Value Imputation:** Handling missing data through **Self-Joins** and logical updates.
- **Schema Optimization:** Modifying column types and dropping unnecessary columns for performance.

## 🚀 Key Technical Solutions
* **The Duplicate Challenge:** Since MySQL doesn't allow direct deletions from a CTE, I used a secondary staging table with an auxiliary `row_num` column to physically remove duplicates.
* **Smart Imputation:** Developed a join logic that populates missing `industry` fields by referencing other records from the same company.

## 📂 Files in this Repository
* `layoffs_data_cleaning.sql`: The full SQL script containing the cleaning workflow.

---
**Author:** Italo Fernando Martin Yupan Artica  
*Data Analytics Portfolio* | [LinkedIn Profile](https://www.linkedin.com/in/f-yupan-analyst)
