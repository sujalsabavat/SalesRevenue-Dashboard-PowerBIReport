# SalesRevenue-Dashboard-PowerBIReport
## Overview
This GitHub repository contains code and documentation for an ETL (Extract, Transform, Load) process designed to create a data model for further analysis. The primary goal is to facilitate business analysis using a star schema composed of fact and dimension tables. The data transformation process involves using Power Query Editor to clean and structure the data, ensuring its suitability for analysis.

# ETL Process
The ETL process involves several key steps:<br>
Data Extraction:<br>
Source data is obtained for analysis.<br>
Data Transformation:<br>
Foreign zones are removed from markets.<br>
Negative and zero sales amounts are filtered out.<br>
Data Loading:<br>
The cleaned and transformed data is loaded into the star schema consisting of fact and dimension tables.<br>
# Data Modeling
The core of this project is the creation of a star schema. This schema includes a fact table that contains business metrics and dimension tables that provide context to these metrics. This model is designed to support efficient querying and reporting for business analysis.<br>
Star Schema Components
Fact Table:<br>
Contains business metrics such as sales quantity, revenue, etc.<br>
Dimension Tables:<br>
Provide context for the business metrics, e.g., region, customer information, etc.<br>
# PowerBI Dashboard
Once the data model is established, a PowerBI Dashboard is built to provide a comprehensive view of key business indicators. The dashboard includes the following components:<br>
Revenue by Region:<br>
Visual representation of revenue distribution across different regions.<br>
Top 5 Customers:<br>
Identifies and displays the top 5 customers contributing to overall revenue.<br>
Revenue Over Time:<br>
Tracks revenue generated over a specific period, allowing for trend analysis.<br>
Sales Quantity:<br>
Presents insights into sales quantity, aiding in inventory and demand analysis.
