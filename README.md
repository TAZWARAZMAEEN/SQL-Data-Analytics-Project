# 📊 SQL Data Analytics Project (SQL Server)

This repository contains a SQL Server analytics project focused on:
- Creating an **analytics schema (Gold layer)**
- Loading curated CSV datasets into **dimension and fact tables**
- Running a set of **analysis/report SQL scripts** (ranking, trends, segmentation, KPIs, etc.)

> Note: This project does **not** implement a full ingestion pipeline (Bronze/Silver ETL).  
> Data is provided as curated CSVs and loaded directly into the `gold` schema using `BULK INSERT`.

---

## 🧱 What’s Inside

### ✅ Gold Schema Tables
- `gold.dim_customers`
- `gold.dim_products`
- `gold.fact_sales`

### ✅ Analytics Scripts
SQL scripts in `/scripts` perform different analytics patterns such as:
- Exploration & profiling
- Measures / KPIs
- Magnitude analysis
- Rankings
- Change over time trends
- Cumulative metrics
- Performance analysis
- Segmentation
- Part-to-whole analysis
- Customer and product reports

---

## 📁 Project Structure

```
SQL-Data-Analytics-Project/
│
├── datasets/
│ └── csv/
│ ├── bronze_.csv
│ ├── silver_.csv
│ ├── gold_dim_customers.csv
│ ├── gold_dim_products.csv
│ ├── gold_fact_sales.csv
│ ├── gold_report_customers.csv
│ └── gold_report_products.csv
│
├── scripts/
│ ├── 00_init_database.sql
│ ├── 01_database_exploration.sql
│ ├── 02_dimensions_exploration.sql
│ ├── 03_date_range_exploration.sql
│ ├── 04_measures_exploration.sql
│ ├── 05_magnitude_analysis.sql
│ ├── 06_ranking_analysis.sql
│ ├── 07_change_over_time_analysis.sql
│ ├── 08_cumulative_analysis.sql
│ ├── 09_performance_analysis.sql
│ ├── 10_data_segmentation.sql
│ ├── 11_part_to_whole_analysis.sql
│ ├── 12_report_customers.sql
│ └── 13_report_products.sql
│
├── DataWarehouseAnalytics.bak
└── README.md
```
#  🛡️ License
This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.
