# B42_DA_009_Number_Crunchers
# Overview
This project analyzes stock market data for the top 10 fast food giants, offering insights into their financial performance, trading activities, and market trends. The dashboard is designed using Power BI, with data preprocessed and stored in MySQL for efficient handling and visualization.

# Key Features
- Daily Returns and Volume Analysis: Visualizes company-wise performance and trading activity.
- Stock Price Patterns: Tracks trends with 30-day moving averages.
- Relative Strength Index (RSI): Identifies overbought and oversold conditions.
- Dynamic Filters: Customize analysis by company, year, month, and quarter.
  
# Project Steps
## 1. Data Preprocessing
Cleaned and handled missing values, anomalies, and outliers.
Engineered features such as daily returns, moving averages, RSI, and log returns.
Combined individual company datasets into a single master table for seamless analysis.
## 2. SQL Database Setup
Stored the processed data in a MySQL database.
Included a schema with relevant fields such as Date, Company_Name, Close_Price, Volume, and calculated features.
Ensured the database was optimized for large-scale queries.
## 3. Power BI Integration
Imported data from the SQL database into Power BI.
Designed a user-friendly dashboard with intuitive visuals and interactivity.
Incorporated slicers and filters to allow users to explore data dynamically.

# Setup Instructions
## 1. Setting Up MySQL
Install MySQL on your system.
Import the provided SQL dump file (fast_food_stocks.sql) into your MySQL database.
Verify the database schema:
Table: Each cleaned tables
Columns: Date, Company_Name, Close_Price, Volume, Daily_Return, RSI, etc.
## 2. Connecting Power BI
Open Power BI Desktop.
Navigate to Home > Get Data > MySQL Database.
Enter the server details and credentials for your MySQL instance.
Select the fast_food_stocks table and load it into Power BI.
Apply data transformations or modeling as needed.

# Power BI Dashboard
https://drive.google.com/file/d/1pTuJ8mouDl8U8kYYuRoENop7VVo81SPu/view?usp=sharing

# Insights
McDonald’s Corporation leads in cumulative daily returns, followed by Berkshire Hathaway.
Starbucks Corporation dominates trading volume with 49.6% of the total.
Market trends indicate sharp growth in 30-day moving averages post-2000, reflecting industry expansion.

# Methodology
- Data Cleaning: Addressed missing values, anomalies, and outliers in Python.
- Feature Engineering: Added columns such as RSI, log returns, and Bollinger Bands.
- Database Design: Structured SQL tables for easy integration with Power BI.
- Visualization: Used Power BI to create interactive dashboards with dynamic filters.

# Notes
Ensure your MySQL instance is accessible to Power BI before starting.
Adjust filters in Power BI for customized analysis.
This project can be extended by incorporating additional datasets or integrating machine learning predictions.
