## Zomato Business Analytics Dashboard (Power BI)

## Overview
This project is an end-to-end Business Analytics Dashboard built using Power BI on a Zomato-style food delivery dataset.
It focuses on transforming raw, unstructured data into actionable business insights through data cleaning, modeling, and interactive visualizations. The dashboard enables analysis of revenue trends, customer behavior, restaurant performance, and delivery operations to support data-driven decision-making.
This project was built to simulate a real-world business analytics scenario and strengthen my understanding of end-to-end data workflows in Power BI.

## Objectives
- Analyze overall business performance (Revenue, Orders, AOV)
- Understand customer behavior (New vs Returning users)
- Evaluate restaurant performance and cuisine trends
- Identify operational insights like delivery time efficiency

## Tech Stack
- Power BI
- Power Query (ETL)
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)


## Project Workflow
### 1. Data Cleaning (ETL)
- Handled missing values and incorrect formats
- Standardized date and numerical columns

### 2. Data Modeling
- Designed a Star Schema to improve query performance and scalability
- Established relationships between fact and dimension tables (Orders, Customers, Restaurants)

### 3. DAX Calculations
- Developed dynamic measures using DAX:
  - Total Revenue
  - Total Orders
  - Average Order Value (AOV)
- Ensured measures respond to filters and slicers for interactive analysis


### 4. Dashboard Development
- Executive Overview dashboard
- Customer Analytics dashboard
- Restaurant Performance dashboard

### 5. Advanced Features
- Implemented drill-through functionality for detailed restaurant-level analysis
- Built a dynamic KPI selector for flexible metric comparison (Revenue, Orders, AOV)
- Enabled interactive filtering for deeper data exploration

## Key Insights

- A small segment of restaurants contributes disproportionately to total revenue, indicating a skewed performance distribution
- Returning customers show higher average order value, highlighting the importance of retention strategies
- Certain cuisines consistently outperform others, suggesting targeted marketing opportunities
- Increased delivery time negatively impacts customer experience and potential retention


## Files Included
- Power BI (.pbix) file
- Dataset 


##  Future Improvements

- I aim to add advanced KPIs such as customer retention rate, churn analysis, and delivery delay percentage to deepen business insights.
- I plan to implement more advanced DAX calculations and optimize existing measures for better performance on large datasets.
- I aim to include predictive analytics (forecasting revenue/orders) to move from descriptive to predictive analysis.
- I will expand the project by adding more granular drill-downs (city-level, time-based trends) for deeper exploration.
- I also plan to deploy this dashboard using Power BI Service for real-time sharing and accessibility.

## About Me
I am an Electrical Engineering student at DTU with an interest in Data Analytics and Business Intelligence. I enjoy building dashboards that convert data into actionable insights.

