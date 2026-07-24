# Data Warehouse and Analytics Project

## Overview

This project demonstrates a comprehensive data warehousing and analytics solution, covering the full lifecycle from building a data warehouse to generating actionable business insights.

---

## 📋 Project Overview

This project involves:

- **Data Architecture**  
  Designing a modern data warehouse using the **Medallion Architecture** (Bronze, Silver, and Gold layers).

- **ETL Pipelines**  
  Extracting, transforming, and loading data from source systems into the data warehouse.

- **Data Modeling**  
  Developing optimized **fact and dimension tables** for efficient analytical querying.

- **Analytics & Reporting**  
  Creating SQL-based reports and dashboards to generate actionable business insights.

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---
#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

## 🏗️ data architecture
The data architecture of this project follows Medallion architecture bronze, silver, and gold layers.
<img width="3714" height="1854" alt="Data_architecture " src="https://github.com/user-attachments/assets/2e580afc-f2ca-4cb5-885b-637782fdf2b4" />
1. **Bronze Layer:** Loads raw data from CSV files into SQL Server while preserving the original structure.
2. **Silver Layer:** Cleans, standardizes, and transforms data to improve data quality and prepare it for analysis.
3. **Gold Layer:** Builds a business-ready Star Schema optimized for reporting and analytics.





