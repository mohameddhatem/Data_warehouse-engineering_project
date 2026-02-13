# Data_warehouse-engineering_project
Building data warehouse project with three medallion , extracting data from  CSV Files , ETLs , Stored procedure , data analysis , visualisations



Project Overview
This project implements a Data Warehouse for a business domain to consolidate data from multiple sources and provide insights through analytics and reporting.
Key features:
Centralized data storage for multiple sources
Cleaned and transformed data for reporting
Support for ad-hoc analytics and dashboards
Objectives
Integrate heterogeneous data into a single repository
Design a scalable star schema or snowflake schema
Enable ETL automation for data ingestion
Generate meaningful insights and visualizations
Architecture
Data Sources → ETL → Staging → Data Warehouse → Analytics & Dashboards
Data Sources: CSV, Excel, APIs, relational databases
ETL Layer: Extract, Transform, Load using Python / SQL / Airflow
Staging Area: Raw data storage before cleaning
Data Warehouse: Fact and dimension tables
Analytics: Reports and dashboards using Power BI / Tableau / Python
Data Sources
Source	Type	Description
Sales CSV	Flat file	Daily sales transactions
Customer DB	SQL Server	Customer info and demographics
Web API	JSON	Product ratings and reviews
ETL Process
Extract: Pull data from sources using Python scripts / SQL queries
Transform: Clean data, normalize, handle missing values, derive metrics
Load: Insert transformed data into staging and finally into the data warehouse
Optional: Automated with a scheduler (Airflow / Cron jobs)

