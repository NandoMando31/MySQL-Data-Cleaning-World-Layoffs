# World Layoffs: Data Cleaning & Exploratory Data Analysis (EDA) 📉🔍

## 📌 Project Overview
This repository contains a two-part SQL project focused on the "World Layoffs" dataset. 
1. **Data Cleaning:** Transforming raw data into a usable format.
2. **Exploratory Data Analysis (EDA):** Uncovering trends and patterns in global layoffs from 2020 to 2023.

## 🛠️ Skills & SQL Concepts Applied
- **Advanced EDA:** Identifying top companies, industries, and countries impacted by layoffs.
- **Window Functions:** Using `DENSE_RANK()` to create yearly rankings and `SUM() OVER()` for rolling totals.
- **Time Series Analysis:** Extracting and grouping data by years and months to visualize trends over time.
- **Complex CTEs:** Structuring multi-level Common Table Expressions to perform advanced filtering and calculations.
- **Data Aggregation:** Extensive use of `GROUP BY` and aggregate functions to summarize financial impacts and funding levels.

## 💡 Key Business Insights Discovered
* **Rolling Totals:** Calculated the cumulative progression of layoffs month-over-month to visualize the pandemic's impact.
* **Top Rankings:** Identified the top 5 companies with the most layoffs for each year using ranking partitions.
* **Funding Impact:** Analyzed the relationship between funds raised and layoff percentages, identifying high-risk company stages (e.g., Post-IPO vs. Series B).

## 📂 Repository Structure
* `layoffs_data_cleaning.sql`: Full script for the data cleaning workflow.
* `layoffs_eda.sql`: Script containing all exploratory queries and business questions.

---
**Author:** Italo Fernando Martin Yupan Artica  
*Data Analytics Portfolio* | [LinkedIn Profile](https://www.linkedin.com/in/f-yupan-analyst)
