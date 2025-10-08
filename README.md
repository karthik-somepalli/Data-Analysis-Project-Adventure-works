📊 Adventure Works Data Analysis: Sales & Finance Performance
Welcome to my first comprehensive portfolio project. This analysis takes the raw AdventureWorksDW dataset through an end-to-end pipeline, focusing on data cleaning, transformation with SQL, and visualization with a multi-page Power BI dashboard.

<p align="center">
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server Badge"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=white" alt="Power BI Badge"/>
<img src="https://img.shields.io/badge/Data%20Modeling-404040?style=for-the-badge&logoColor=white" alt="Data Modeling Badge"/>
<img src="https://img.shields.io/badge/Python%20(Future%20Automation)-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Automation Badge"/>
</p>

🚀 Project Pipeline & Skills Demonstrated
The project demonstrates proficiency across the entire business intelligence workflow:

Data Acquisition: Restored the original .bak file in Microsoft SQL Server Management Studio (SSMS).

Data Cleaning/ETL: Used SQL to query, clean, and transform the raw tables.

Modeling: Established relationships and a Star Schema in Power BI.

Visualization: Built a dynamic, three-page interactive dashboard for executive consumption.

⚙️ SQL Cleaning and Transformation
The primary cleaning objective was to filter and format the data to create normalized tables suitable for Power BI modeling.

The raw dataset link is available for download on Microsoft's GitHub: AdventureWorksDW2019.bak

The project files include portfolio_1-project-analysis.sql, which contains the queries used to generate the final cleaned CSV tables.

📈 Final Dashboard Visualization
The Power BI dashboard provides three distinct views to analyze Internet Sales, Customer Demographics, and Product Performance.

Page 1: AdventureWorks Sales Overview
This page presents high-level KPIs, budget vs. actual sales, and year-over-year growth, serving as an executive summary.

<p align="center">
<img src="https://user-images.githubusercontent.com/122973220/213424939-2e4614c7-28f2-4f25-9691-e53f7aa9f368.jpg" width="800"/>
</p>

Page 2: Sales by Customer
A deep dive into customer segments, sales geography, and demographic influence on purchasing behavior.

<p align="center">
<img src="https://user-images.githubusercontent.com/122973220/213426418-36348415-aa68-42e7-90a2-81b0306cd30f.jpg" alt="Sales by Customer Dashboard Page 2" width="800"/>
</p>

Page 3: Sales by Product
Focuses on product profitability, comparing sales across different product categories and analyzing budget adherence.

<p align="center">
<img src="https://user-images.githubusercontent.com/122973220/213426517-39db89b9-88e1-4241-9844-bd65cfadb686.jpg" alt="Sales by Product Dashboard Page 3" width="800"/>
</p>

📁 Repository Contents
File Name	Description	Role in Project
portfolio_1-project-visualization_powerbi.pbix	The Primary Deliverable. The interactive, 3-page Power BI dashboard file.	Visualization & Modeling
portfolio_1-project-analysis.sql	Contains all original SQL queries used for data cleaning and extraction.	Data Cleaning & ETL
portfolio_1-data_table-*.csv	Cleaned and filtered data tables used as the input source for the Power BI model.	Data Source
portfolio_1-project-visualization_pdf.pdf	Static PDF export of the final 3-page dashboard.	Final Deliverable
portfolio_1-data_table-SalesBudget.xlsx	Supporting Excel data used for Budget vs. Actual comparisons.	Data Source
🎯 Future Automation Aim (2023 Resolution)
My next goal is to move beyond manual reporting and establish a fully autonomous data delivery system.

The future aim is to build a Python-based automation system capable of:

Connecting directly to the database.

Executing the SQL cleaning script.

Refreshing the Power BI dashboard data.

Exporting the static PDF.

Automatically Emailing the PDF report to concerned stakeholders.

This autonomy will ensure the entire process requires near-zero human intervention, maximizing efficiency and demonstrating proficiency in programming, automation, and DevOps principles.
