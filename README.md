DATA WAREHOUSING AND ANALYTICS PROJECT
Welcome data warehousing and analytics project repository***** This project demonstrates comprehensive data warehousing and analytics solution, from building a warehouse to generating actionable insights. Designed as a portfolio project by implementing standard and industry best practices and data engineering and analytics Notions:
==================================================================================================================================================================================================================
  
HiGH LEVEL ARCHITECHTURAL DESIGN: https://app.diagrams.net/?src=about#G1RHzhMJCvsCVuiS_r0YTlVmResA---nJv#%7B%22pageId%22%3A%22ENrI8TddiCgyRL0yWyHr%22%7D (draw.io) 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
BRONZE LAYER DATAFLOW DIAGRAM :https://app.diagrams.net/#G1eIqc0SWZo5L8RWAH4CQF96-m7pKcmV9N#%7B%22pageId%22%3A%22Cbe5rRa6jUTYSwL8uK46%22%7D
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
INTiGRATION DIAGRAM: https://app.diagrams.net/#G1uulaYsZbpi3pyh_pReTsQ_vNiXyJ5gjV#%7B%22pageId%22%3A%224yOj6MV5-AvYVCollSsQ%22%7D
===================================================================================================================================================================================================================

📖 Project Overview
This project involves:

Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
Data Modeling: Developing fact and dimension tables optimized for analytical queries.
Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.
🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

SQL Development
Data Architect
Data Engineering
ETL Pipeline Developer
Data Modeling
Data Analytics
🛠️ Important Links & Tools:
Everything is for Free!

Datasets: Access to the project dataset (csv files).
SQL Server Express: Lightweight server for hosting your SQL database.
SQL Server Management Studio (SSMS): GUI for managing and interacting with databases.
Git Repository: Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
DrawIO: Design data architecture, models, flows, and diagrams.
Notion: All-in-one tool for project management and organization.
🚀 Project Requirements
Building the Data Warehouse (Data Engineering)
Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications
Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
Data Quality: Cleanse and resolve data quality issues prior to analysis.
Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
Scope: Focus on the latest dataset only; historization of data is not required.
Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
BI: Analytics & Reporting (Data Analysis)
Objective
Develop SQL-based analytics to deliver detailed insights into:

Customer Behavior
Product Performance
Sales Trends
These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to docs/requirements.md.

🏗️ Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers: Data Architecture

Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.
📂 Repository Structure
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
About me my name is jeshwanth BTECH 2024 graduate at VNR vignana jyothi institute of technology my skills : AZURE DATA FACTORY FUNDAMENTALS OF AZURE CLOUD AND AZURE SYNAPSES,MICROSOFT SSMS,AZURE DATABRICKS ,python SQL, tableau,DATA ANALYSIS.
