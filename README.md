# 📊 project overview
This repository contains a comprehensive collection of SQL scripts for data exploration, analytics, and reporting based on the Gold layer of a self-built data warehouse.

The scripts cover different types of analysis such as database exploration, measures and metrics, time-based trends, cumulative analytics, segmentation, ranking, and reporting. Each script focuses on a specific analytical task and reflects real-world business analysis scenarios.
This repository is designed to help data analysts and BI professionals quickly explore, segment, and analyze business-ready data within a relational database. All queries follow SQL best practices for clarity, accuracy, and performance.

The analyses are performed on the curated Gold layer star schema, ensuring consistent business logic and a realistic enterprise analytics workflow.

---
## 🔹 Data Source
The analyses in this project are based on the Gold layer of a self-designed data warehouse.
🔗 **Data Warehouse Repository** 
[View the Data Warehouse Project](https://github.com/MoQasem2/SQL-Data-Warehouse-Project.git)  

The warehouse follows a medallion architecture (Bronze → Silver → Gold). The Gold layer contains a star schema with fact and dimension views designed specifically for analytics and reporting.

---
## 🔹 Analytical Focus

This project demonstrates end-to-end analytical querying across multiple business themes using the Gold layer star schema.

- Exploratory data analysis  
- KPI and metrics calculation  
- Time-based trend analysis  
- Cumulative and running totals  
- Product and customer performance analysis  
- Data segmentation  
- Ranking and Top/Bottom analysis  
- Reporting-ready SQL queries  

The goal of this project is to show how business-ready warehouse data can be transformed into actionable insights using professional SQL techniques and clean analytical logic.

---
##  🔹 Gold Layer Model Used

The analytics are built on a star schema consisting of:

- `gold.dim_customers` → Customer master data  
- `gold.dim_products` → Product and category attributes  
- `gold.fact_sales` → Transactional sales measures  

The fact table connects to conformed dimensions via surrogate keys, enabling scalable and reliable analytical queries.

##  🔹 SQL Techniques Demonstrated

- Complex JOIN operations  
- Window functions 
- Common Table Expressions (CTEs)  
- Aggregations and GROUP BY  
- Date-based analysis  
- Business rule implementation  
- Clean, production-style SQL formatting
  
----
## 🔹 Business Value

Through this project, the dataset is transformed into insights that support:

- Revenue and sales monitoring  
- Customer behavior analysis  
- Product performance evaluation  
- Trend and growth analysis  
- Segmentation-driven decision making  

The structure and queries reflect real-world data analyst responsibilities in modern BI environments.

---
## 👤 About Me
Hi their I'm Mohammed Qasem.I'm a Data Analyst & BI Developer 




