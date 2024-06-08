# Global Mart Sales Analysis

Sales Analysis Project
This project involves analyzing sales data to gain insights into customer behavior, regional sales trends, product performance, and shipping methods. The analysis is conducted using Python and SQLite, with visualization libraries such as Matplotlib and Seaborn.

## Overview
The project consists of three main parts:

Customer Analysis: Analyze the distribution of orders and sales across different regions and segments.

Sales Analysis: Identify top-selling products, evaluate sales growth, and determine monthly sales trends.

Shipping Analysis: Assess the frequency and sales associated with different shipping methods.

## Requirements
To run the code make sure that you have the following libraries installed:
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sqlite3

You can install these libraries using pip (ex: pip install pandas matplotlib seaborn)

## Data
The data used for analysis is stored in an SQLite database named global_mart.db. It contains tables for orders, including information such as order date, region, segment, product details, sale price, and ship mode. 

Data Source: https://www.kaggle.com/datasets/ankitbansal06/retail-orders

## Findings

### Customer Analysis
The West region generates the highest sales, followed by the East, Central, and South.
Regular consumers make up the majority of sales, followed by Corporate and Home Office segments.

### Sales Analysis
Sales in 2023 showed mixed trends compared to 2022, with notable variations in different months.
Copiers emerged as the top revenue-generating product, followed by Binders and Machines.
Supplies experienced the highest growth in revenue from 2022 to 2023, while Appliances saw the most significant regression.
Shipping Method Analysis
Standard Class shipping method generated the highest number of orders and sales, followed by Second Class, First Class, and Same Day.

## Recommendations
Customer Analysis
Focus marketing efforts on regular consumers and explore strategies to increase sales in regions with growth potential, such as the South.
Sales Analysis
Utilize insights on seasonal sales patterns to optimize resource allocation and inventory management.
Promote top-selling products based on regional preferences and invest in product categories experiencing growth.
Shipping Method Analysis
Ensure efficiency and reliability of the Standard Class shipping method and explore optimizations for other shipping methods to capture additional sales opportunities.






