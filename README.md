# Store Sales and Forecast Dashboard

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Process](#process)
- [Features](#features)
- [Insights](#insights)
- [Learning](#learning)

## Overview

The XYZ Store Dashboard provides a comprehensive snapshot of sales performance, profits, orders, and key business metrics across regions, customer segments, payment modes, and product categories. Its intuitive layout combines summary metrics, year-over-year performance trends, geographic analysis, and categorical breakdowns, enabling quick identification of strengths, growth patterns, and operational highlights.

![O1](https://github.com/user-attachments/assets/3bfd9df4-be8d-49ba-8884-9ef184b849fa)  

![O2](https://github.com/user-attachments/assets/936c4393-292a-436f-95df-8b777a760323)  


<img width="1443" height="811" alt="O3" src="https://github.com/user-attachments/assets/21566406-3422-4e98-9a5c-6ed237aaed3a" />  


![O4](https://github.com/user-attachments/assets/9f6bf2c7-267f-4238-8c54-3d43db87c4a1)  


## Dataset

The Dataset table header represents a sales transaction dataset with the following columns:

- **Category**: The main grouping or type of goods sold (e.g., Electronics, Furniture).
- **Sub-Category**: A more specific classification within each main category (e.g., Laptops under Electronics).
- **Product Name**: The specific item sold.
- **Sales**: The monetary value of the transaction.
- **Quantity**: The number of units sold in each transaction.
- **Profit**: The profit earned from the sale.
- **Returns**: Indicates if the item was returned.
- **Payment Mode**: The method used for payment (e.g., Credit Card, Cash).

This structure is typically used for retail sales analysis, helping track performance, inventory, and customer behavior.


## Process

Tools Used :- Microsoft Excel,  Microsoft Power BI.  

Process:-   
-Familiarizing with the dataset.   
-Connecting the data to a Power BI file.    
-Performing Data Cleaning Operations.  
-Generating required Column for analysis.  
-Checking Data Module.     
-Generating Calculations where required.  
-Designing a Power BI dashboard.  
-Creating data visuals for the Power BI dashboard as per the design.  
-Formatting the Visuals.  
-Adding Slicers and other visuals. 

## Features


### Dashboard Features

- **KPI Highlights** (Top Center)
  - **Total Sales, Profit, Orders, and Average Shipping Days:** Displayed as large figures at a glance for immediate assessment of business scale and efficiency.

- **Segmented Sales Breakdowns** (Left Side)
  - **Sales by Segment:** Shows share by Consumer, Corporate, and Home Office segments using a donut chart.
  - **Sales by Payment Mode:** Pie chart breakdown of payment preferences, including COD, Online, and Cards.
  - **Sales by Region:** Regional performance with proportional shares represented in a donut chart.

- **Performance Trends** (Center)
  - **Monthly Sales by Year-over-Year (YoY):** Line chart compares monthly sales for two years, highlighting growth or decline patterns.
  - **Monthly Profit by YoY:** Similar line chart for profits aims to visualize trends over time.

- **Categorical and Shipping Insights** (Right Side)
  - **Sales by Ship Mode:** Horizontal bar chart illustrates preference for shipping options (Standard, Second Class, First Class, Same Day).
  - **Sales by Category:** Highlights top-performing product categories (Office Supplies, Technology, Furniture).
  - **Sales by Sub Category:** Drills down further with sales per sub-category (Phones, Chairs, etc.), using a horizontal bar chart.
  - **Profit and Sales by State (Map):** Geographical distribution of sales and profits visualized by bubble sizes on a U.S. map.

### Summary

- The dashboard is designed for quick, visual analysis of sales performance, customer segments, regional strengths, shipping preferences, most profitable categories, and monthly trends.
- It features an easy-to-read layout with a blend of pie charts, bar charts, line graphs, and a map for geographic insights.
- KPIs and comparative year-to-year trends help decision-makers track progress, spot opportunities, and focus on high-performing segments or regions.


## Insights

### Super Store Dashboard Insights

### Key Performance Metrics
- **Total Sales:** 1.57M
- **Total Profit:** 175.26K
- **Total Orders:** 22K
- **Average Shipping Days:** 3.93

### Sales Breakdown

#### By Segment
- **Consumer**: 48% of sales (largest segment)
- **Corporate**: 33%
- **Home Office**: 19%

#### By Region
- **West**: 33% of sales (top region)
- **East**: 29%
- **Central**: 22%
- **South**: 16%

#### By Payment Mode
- **Cash on Delivery (COD):** 43% (most common)
- **Online:** 35%
- **Cards:** 22%

### Sales & Profit Trends

- **Monthly Sales Year-over-Year (YoY):**
  - 2020 shows higher sales compared to 2019, with sales peaking towards the end of the year (November and December).
- **Monthly Profit YoY:**
  - Profits in 2020 consistently surpass those in 2019, especially in the final months.

### Sales by Category & Sub-Category

#### Top Categories
- **Office Supplies:** 0.64M (highest)
- **Technology:** 0.47M
- **Furniture:** 0.45M

#### Top Sub-Categories
- **Phones:** 0.20M
- **Chairs:** 0.18M
- **Binders:** 0.15M
- **Storage:** 0.15M
- **Accessories:** 0.12M

### Sales by Shipping Mode
- **Standard Class:** 0.91M (most utilized)
- **Second Class:** 0.31M
- **First Class:** 0.24M
- **Same Day:** 0.10M

### Geographic Insights
- The map visualization highlights a concentration of sales and profit in states along the east and west coasts of the United States, with larger bubbles indicating higher performance in those states.

**Summary of Insights:**
- The business is strongest among the Consumer segment, in the West and East regions, and for Office Supplies and Technology.
- Performance in 2020 improved over 2019 in both sales and profit, especially late in the year.
- Standard shipping is overwhelmingly preferred, and COD is the most used payment mode.
- Phones and Chairs are standout sub-categories driving sales.

These insights can guide targeted marketing, operational improvements, and strategic resource allocation to maximize future growth.


## Learning

Data connectivity and Updating in Power BI.  
Data modeling in Power BI.  
Designing a Power BI dashboard.  
Using DAX to change numerical data to categorical data.  
Working with Transactional Data in Power BI.  
Working on Sales Forecasting using inbuilt Power BI functionality.  
