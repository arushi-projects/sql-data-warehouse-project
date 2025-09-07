# Modern Data Warehouse for Sales Analytics

This project implements a modern data warehouse using **SQL Server** to consolidate and analyse sales data from ERP and CRM systems. The warehouse enables informed decision-making by providing clean, integrated, and analytics-ready datasets for customer behavior, product performance, and sales trends.

## 📌 **Objective**
Develop a scalable data warehouse that transforms raw sales data into actionable insights using structured ETL pipelines, star schema modelling, and SQL-based analytics.

## ✅ **Features**
- **Medallion Architecture:** Bronze (raw), Silver (cleaned), and Gold (analytics-ready) layers for structured data processing.
- **ETL Pipelines:** Optimised extraction, transformation, and loading using CTEs and stored procedures in Azure Data Studio.
- **Data Modelling:** Star schema design with fact and dimension tables for efficient querying.
- **Analytics:** SQL reports to explore customer segments, product performance, and sales trends.
- **Documentation:** Detailed diagrams and data catalogue for easy understanding and maintenance.

## 📂 **Repository Structure**

data-warehouse-project/
│
├── datasets/ # Raw ERP and CRM datasets
├── docs/ # Documentation and diagrams
│ ├── data_architecture.drawio
│ ├── data_catalog.md
│ ├── data_flow.drawio
│ └── data_models.drawio
├── scripts/ # ETL and transformation scripts
│ ├── bronze/
│ ├── silver/
│ └── gold/
└── readme.md # Project overview and setup instructions


## 🚀 **Getting Started**
1. Load the CSV files from `datasets/` into your SQL Server environment.
2. Follow the ETL scripts in the `scripts/` directory to transform the data through bronze, silver, and gold layers.
3. Explore the analytics-ready tables using the provided SQL queries.

## 📂 **Resources**
The repository includes:
- Raw datasets
- ETL scripts
- Architecture diagrams
- Data catalogue with metadata

---

This setup allows teams to build scalable data solutions and derive business intelligence from structured, high-quality datasets.
