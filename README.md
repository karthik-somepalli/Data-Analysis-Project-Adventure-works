🚀 AdventureWorks Sales Performance Dashboard
This project demonstrates a complete end-to-end data pipeline, from raw SQL data cleaning and preparation to interactive visualization using Power BI.

<p align="center">
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server Badge"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=white" alt="Power BI Badge"/>
<img src="https://img.shields.io/badge/Data%20Cleaning-007ACC?style=for-the-badge&logo=power-automate&logoColor=white" alt="Data Cleaning Badge"/>
<img src="https://img.shields.io/badge/Data%20Modeling-404040?style=for-the-badge&logoColor=white" alt="Data Modeling Badge"/>
</p>

💡 Project Goal & Value
The objective was to transform the complex AdventureWorks Data Warehouse into a centralized, interactive resource, providing key stakeholders with self-service analytics across Sales, Customer Demographics, and Product Performance.

Key Skills Demonstrated:
Database Management (SQL): Data restoration, querying, transformation, and export preparation.

Data Modeling: Building functional Star Schemas in Power BI.

Data Visualization: Designing multi-page, actionable dashboards for executive review.

🛠️ Data Pipeline & Technical Execution
1. SQL Data Preparation (Extract & Transform)
The process began by restoring the large (99MB) AdventureWorksDW2019.bak file in Microsoft SQL Server Management Studio (SSMS).

Data Cleaning: SQL scripts were used to select, sort, and clean only the necessary columns from the original dataset.

Output: The final cleaned data was exported into 4 separate CSV data tables ready for direct ingestion into Power BI, ensuring efficient data model size.

2. Power BI Data Modeling
The relational structure of the data was defined within Power BI to ensure calculation accuracy.

Model: The cleaned CSVs (for dimensions: DimCustomer, DimDate, DimProduct, etc.) were imported along with the sales fact data (FactInternetSales).

Schema: The tables were linked in the "Model" view to create a clean and efficient schema, optimizing cross-table filtering and measure performance.

Transformation: Further refinement was performed in Power Query (M-Language) to rename columns and ensure correct data types before visualization.

3. Interactive Dashboard (3 Pages)
The final deliverable is an interactive, multi-page Power BI dashboard designed for focused analysis:

Page 1: AdventureWorks Sales Overview

Focus: Executive summary of Total Sales, Gross Margin, and global geographic contribution.

Page 2: Sales by Customer

Focus: Detailed analysis of customer demographics, identifying high-value customer groups and regional sales performance.

Page 3: Sales by Product

Focus: Breakdown of product category and subcategory performance to inform inventory and product strategy.

🚀 Future Aim: Full Automation (Data Engineering)
This project serves as the blueprint for my next goal: setting up a fully automated, Zero-Touch Data System.

Target Proficiency: Achieving sufficient proficiency in Python and data engineering tools.

Automation Goal: To create a system that autonomously:

Pulls fresh data from the database.

Cleans and organizes the data (ETL/ELT process).

Visualizes the data in a dashboard.

Exports the dashboard as a PDF.

Emails the PDF report to all concerned stakeholders.

Resolution: I intend to achieve this full automation and system setup, allowing for unforeseen constraints, ideally by the end of 2023.

📂 Repository Contents
File Type	File Names	Description
Power BI File	portfolio_1-project-visualization_powerbi.pbix	The interactive, 3-page dashboard visualization file.
SQL Script	portfolio_1-project-analysis.sql	The SQL queries used for initial data cleaning, transformation, and export to CSVs.
Static Report	portfolio_1-project-visualization_pdf.pdf	A static, exported version of the final dashboard.
Data Tables (CSVs)	portfolio_1-data_table-DimCustomer.csv, etc.	The 4 cleaned CSV files and 1 Excel worksheet used as the import source for Power BI.
Original Dataset	External Link	Link to the original, large AdventureWorksDW2019.bak file on Microsoft's GitHub.
