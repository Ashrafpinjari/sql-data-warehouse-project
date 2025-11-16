🚀 **Data Warehouse & Analytics Project**

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

🏛️ Architecture Overview — Medallion Architecture

This project follows the Medallion Architecture (Bronze → Silver → Gold) to ensure clean, reliable, and analytics-ready data.

🥉 Bronze Layer — Raw Data

Stores raw data as-is from source systems.

Ingested from CSV files into SQL Server (ERP & CRM systems).

🥈 Silver Layer — Cleansed & Standardized

Data cleansing (null handling, deduplication, format alignment).

Standardization + normalization for consistent analytical use.

🥇 Gold Layer — Business-Ready

Final curated tables in Star Schema format.

Contains Fact and Dimension tables for analytics.

Supports BI dashboards and advanced SQL reporting.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

📦 Project Overview

This project demonstrates:

🔧 1. Data Architecture

Design & implementation of a modern data warehouse using SQL Server + Medallion layers.

⚙️ 2. ETL Pipelines

Build ETL processes to:

Extract from CSV files

Transform data across layers

Load into dimensional models

🧩 3. Data Modeling

Creation of:

Fact tables (Sales, Orders, Transactions)

Dimension tables (Customer, Product, Calendar, Region, SalesPerson)

📊 4. Analytics & Reporting

SQL-based insights such as:

Customer buying patterns

Product sales performance

Monthly, quarterly, yearly sales trends

Top-performing categories, regions, and sales reps

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

🎯 Skills Demonstrated

This project is suitable for showcasing expertise in:

🛠️ SQL Development

🚀 Data Engineering

🔄 ETL Pipeline Design

🧱 Data Modeling (Star Schema)

🧹 Data Cleansing & Quality

📈 Data Analytics & BI

🛢️ Data Architecture

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Project Requirements

🔨 Part 1: Data Engineering — Data Warehouse
🎯 Objective

Build a SQL Server–based modern data warehouse consolidating sales data for analytics.

📌 Specifications

Data Sources: ERP + CRM (CSV files)

Data Quality: Clean & validate data before loading

Integration: Merge both systems into a unified analytical model

Scope: Latest dataset only (no SCD/historical tracking)

Deliverable: Fully documented data model + ERD

📊 Part 2: Data Analytics — Reporting
🎯 Objective

Deliver insight-generating SQL queries & dashboards related to:

👥 Customer behavior

📦 Product performance

💰 Sales trends

🌎 Regional sales

📈 Key business metrics

These enable data-driven decision-making for business teams.

🗂️ Repository Structure 
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_layers.pdf                 # Detailed explanation of each layer
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
|    ├── quality_check_silver.sql        # Test script for silver layer
|    ├── quality_check_silver.sql        # Test script for gold layer
|
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository


-------------------------------------------------------------------------------------------------------------------------------------------------------------------

📘 Documentation

In this repository you will find:

🔹 ERD (Entity Relationship Diagram)

🔹 Star schema explanation

🔹 Data flow diagrams

🔹 Business rules & transformation logic

🔹 SQL scripts for each layer
