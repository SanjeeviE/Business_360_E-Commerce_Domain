# Business 360 Power BI Dashboard
This repository contains the Power BI dashboard for analyzing AtliQ's business performance across various views for FY 2018-2022. The dashboard provides insights into finance, marketing, supply chain, executive, sales, and global sales trends.

**Data Sources**
SQL Database: The database dump gdb041.sql and gdb056.sql contains structured data in a star schema format with dimension (dim_) and fact (fact_) tables.

dim_customer: Details about customers.
dim_market: Information on markets.
dim_product: Product details.
fact_forecast_monthly: Monthly forecast data.
fact_sales_monthly: Monthly sales data.
Excel/CSV Files (TBD based on further uploads): Contains supplementary data for the analysis.

**Dashboard Views**
Finance View: Analyzes financial metrics and KPIs.
Marketing View: Offers insights into marketing efforts and their outcomes.
Supply Chain View: Displays metrics related to the supply chain and logistics.
Executive View: Provides an executive summary of the business's performance.
Sales View: Delves into sales metrics, KPIs, and trends.
Global Sales Trends: Visualizes sales trends across the globe.
Technical Details
Data Model: The data model has been created in Power BI by integrating data from the SQL database and Excel/CSV files.
Optimization: The report has been optimized using DAX Studio for better performance.
How to Use
Data Preparation:

Load the SQL dump into a MySQL database.
Import any additional Excel/CSV files if provided.
Power BI:

Open the Power BI report file from this repository.
Connect the report to the database and refresh the data model.
Navigate through the various views/tabs for insights.
Optimization with DAX Studio:

If you experience any performance issues, use DAX Studio to optimize the data model and measures.
