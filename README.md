# Data Warehouse and Analytics Project

Welcome to the *Data Warehouse and Analytics Project* repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---
## 🏗 Data Architecture

The data architecture for this project follows Medallion Architecture *Bronze, **Silver, and **Gold* layers:
![Data Architecture](docs/High%20Level%20Architecture.png)
1. *Bronze Layer*: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. *Silver Layer*: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. *Gold Layer*: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project involves:

1. *Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze, **Silver, and **Gold* layers.
2. *ETL Pipelines*: Extracting, transforming, and loading data from source systems into the warehouse.
3. *Data Modeling*: Developing fact and dimension tables optimized for analytical queries.
4. *Analytics & Reporting*: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:
- SQL Development
- Data Architect
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics  

---

## 🛠 Important Links & Tools:

Everything is for Free!
- *[Datasets](datasets/):* Access to the project dataset (csv files).
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)
- **[DrawIO](https://www.drawio.com/):** Design data architecture, models, flows, and diagrams.


---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- *Data Sources*: Import data from two source systems (ERP and CRM) provided as CSV files.
- *Data Quality*: Cleanse and resolve data quality issues prior to analysis.
- *Integration*: Combine both sources into a single, user-friendly data model designed for analytical queries.
- *Scope*: Focus on the latest dataset only; historization of data is not required.
- *Documentation*: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- *Customer Behavior*
- *Product Performance*
- *Sales Trends*

## 📂 Repository Structure


data-warehouse-project/
│
├── datasets/               
│   └── # المجلد ده بيحتوي على البيانات الخام المستخدمة في المشروع، زي بيانات ERP و CRM
│
├── docs/                   
│   ├── High level Architecture.png
│   │   └── # صورة توضح البنية المعمارية للمشروع (تم رسمها على Draw.io)
│   └── dataflow.png
│       └── # صورة توضح تدفق البيانات في المشروع
│
├── scripts/                
│   ├── bronze/
│   │   └── # سكريبتات لاستخراج وتحميل البيانات الخام (Raw Data)
│   ├── silver/
│   │   └── # سكريبتات تنظيف وتحويل البيانات (Data Cleaning & Transformation)
│   └── gold/
│       └── # سكريبتات لإنشاء النماذج التحليلية (Analytical Models)
│
├── tests/                  
│   └── # سكريبتات لاختبارات جودة البيانات والتحقق من صحتها
│
├── README.md               
│   └── # ملف يشرح نظرة عامة على المشروع والتعليمات الخاصة باستخدامه
│
└── LICENSE                 
    └── # معلومات الترخيص الخاصة بالمشروع

├── tests/                              # Test scripts and data quality checks
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository


