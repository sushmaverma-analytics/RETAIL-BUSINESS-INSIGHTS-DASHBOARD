# RETAIL-BUSINESS-INSIGHTS-DASHBOARD
# This Power BI dashboard built to analyze retail store performance across different years and stores. The objective of this project is to help business managers understand operational performance by analyzing key business metrics such as CPI, Fuel Price, Temperature, Unemployment, and Store-wise trends.
# Dataset Description

### The dataset contains retail operational data from 45 stores across multiple years.

#### Main Columns
- Store
- Date
- Year
- Quarter
- Month
- CPI
- Fuel Price
- Temperature
- Unemployment
# Data Cleaning (SQL+ POWER QUERY)
- "I used SQL for the initial data cleaning because SQL is optimized for handling large datasets efficiently. Tasks like removing duplicates, handling null values, standardizing text, and validating data are faster and more scalable in SQL. After ensuring the data quality, I imported the cleaned dataset into Power BI, where I focused on data modeling, DAX calculations, and dashboard development.Created a Calendar hierarchy for easier time-based analysis.
# Data Modeling
- I followed a Star Schema approach.

Fact Table

Retail Data

Dimension Tables
Date
Store

Relationships were created using:

Store ID
Date

This improved query performance and simplified DAX calculations.

# Tools Used
Power BI Desktop
Power Query
DAX
Data Modeling
Star Schema
Interactive Slicers
Smart Narrative
Key Influencers
Matrix Visual
KPI Cards
Bookmarks and selections
Web search
conditional Formatting
# Business Insights
- Total of fuel price by store,
- Min fuel  price by year how store is getting affected and how it works
- How Total temperature affects year by year
- how stores, avg fuel price, unemployment, avg temp getting affected by avg CPI  year by year
- Top retail data analytics stores by avg CPI
# Final Validation
- Finally, I checked the total number of records and verified that no duplicates or missing values remained.
# Dashboard Preview
<img width="1142" height="652" alt="Screenshot 2026-06-14 040118" src="https://github.com/user-attachments/assets/e1e73907-f794-4f80-bd8e-4efcf9ca5aa7" />

