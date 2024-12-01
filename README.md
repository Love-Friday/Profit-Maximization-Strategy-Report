# Profit-Maximization-Strategy-Report: Ms Excel Project

## Table of Contents
1. [Introduction](#introduction)
   -[Project Overview](#project-overview)
   -[Objectives](#objectives)
2.[Business Problems](#business-problems)
   - [Problem Statement](#problem-statement)
3.[Data Source](#data-source)
- [Key Metrics and Variables](#key-metrics-and-variables)
- [Data Quality](#data-quality)
4.[Data Exploration & Preprocessing](#data-exploration-analysis)
 - [Data Cleaning](#data-cleaning)
 - [Data Transformation](#data-transformation)
5. [Results & Analysis](#results-&-analysis)
  - [Data Visualizations](#data-visualizations)
  - [Insights](#insights)
  - [Recommedations](#recommedations)
6. [Conclusion](#conclusion)
- [Limitations](#limitations)
- [References](#references)

## Introduction

Bokku Mart is a leading retail company in Nigeria, dedicated to customer satisfaction by providing high-quality products at affordable prices. The comapany offers a diverse range of products, making it a popular choice among consumers. 

This project focuses on sales analytics for Bokku Mart, aiming to analyze and visualize sales data to uncover sales trends, customer behavior, product and salesperson performance. The objective is to identify top-performing salespeople, highlight seasonal and regional sales fluctuations, and provide actionable insights to optimize sales strategies. By utilizing data analysis tools and visualizations, this project helps guide decision-making to improve sales performance and maximize revenue at Bokku Mart.

## Project Overview
This project is designed to perform sales analytics for Bokku Mart, leveraging historical sales data to derive insights into sales performance across different regions, customer segments, and time periods. The analysis aims to:
- Identify top-performing salespeople and their contribution to overall revenue.
- Examine seasonal trends, highlighting peak and low sales months to better understand market demand cycles.
- Assess regional sales performance, pinpointing areas of strength and opportunities for growth in different regions.
- Provide recommendations to optimize sales strategies based on the patterns and trends uncovered in the data.

  ## Objectives


The objectives of this project are to analyze Bokku Mart's sales data across regions, product categories, salespeople, customer segments, and seasonal trends to uncover insights that can drive revenue growth and improve sales strategies.



  - Revenue Distribution and Regional Performance
  - Product Category Analysis
  - Salesperson Performance Insights
  - Seasonal Sales Trends and Strategy Optimization







## Tools
The tool used for this analysis was Microsoft Excel, and the creation of visually engaging reports and interactive dashboard visualization.

## Problem Statement 
This analysis aims to evaluate the sales performance of products at Bokku Mart by examining key metrics such as total revenue from products sold, sales per customer, year-to-date revenue, and identifying the month and year with the highest profit. 

### Business Questions  
From the analysis, the management wants to an executive summary of the follwing based on the problem stated above. They include; 
1. How does revenue vary across different regions, which regions are underperforming, why and how can we improve?
2. What product categories are driving the highest & lowest sales, and how can we capitalize on them further?
3. Which salesperson contributes the highest sales, are they any pattern in their performance? How can the less performing salespersons tailor their approcah to meet the unique needs of different customer segemts and regions to boost sales?
4. Can we identify key customers who generate the most revenue and tailor strategies to retain and grow their business?
5. Is there a seasonal trend in sales perfoemance, how can we adjust strategies to maximize profits during peak periods?

## Data Description

The dataset used for this report contains sales information from 4 different regions between 2022 and 2023. The dataset includes a total of 910 transactions, with each transaction containing essential information such as salesperson, products, regions, customers, date, item price, no of items, and revenue. 

Attribute information. 
- salesperson: this lists the names of the sales representative who facilitated each transaction.
-  products: this column contains the name of the products sold
-  region: this indicates the geographic area where the sales occurred
-  customer: includes unique customers, enabling analysis of purchasing patterns and customer loyalty.
-  date: this column records the date of each transaction
-  item price: this column lists the price of each individual item sold
-  no items: this column reflects the quantity of each product sold in the transaction
-  revenue: this ccolumn calculates the total revenue generated from each transaction. 
  
### Data Source

The primary dataset used for this project is the 'sales _data.excel' file. These data points serve as the foundation for analyzing sales performance and formulating strategies to enhance profitability. 

### Data Cleaning
In this report, I will outline the data cleaning process undertaken to prepare the dataset for analysis. The dataset, which contains sales information from various regions, required several steps to ensure accuracy and consistency. Below are the key actions taken to clean and organize the data effectively. 

- Loaded the dataset into ms excel
- Removed duplicates (none found): select data > click data tab > click  remove duplicates icon.
- used the PROPER function in the Salesperson column to convert text to proper case, correcting mixed capitalization, =PROPER(C2:C911)
- Applied VALUE(CLEAN) function in the item price column to eliminate non-printable characters and convert text values to numbers, =VALUE(CLEAN(H2:H911)
- The revenue column automatically updates by formatting it to calculate item price multiplied by the number of items  = H2 * I2 
- Inserted two additional columns to extract Year and Month name values from the Date column
- utilized the YEAR function to extract the year from the Date column; =YEAR(K2 : K911)
- Employed the TEXT function to extract the month name from the Date column;  =Text(G2,"MMM")


Exploratory Data Analysis (EDA)




### Insights

In my profit maximization strategy report analysis, the result reveal a treasure of insights. The analysis results are summarized as follows;
The following insights are derived from an in-depth analysis of the sales data, supported by visualizations that highlight key trends and patterns. 
- Regional Sales Performance:
The bar chart illustrating regional sales performance reveals that NE Region consistently outperforms other regions, contributing to over 35% of total sales. However, SE Region shows low performance 15%.
![Screenshot 2024-12-02 152747](https://github.com/user-attachments/assets/dc23bd4e-403b-40b6-9a40-1a353c8823c6)

-Sales Growth Trends Over Time
The revenue trend over the months reveals a general upward slope at the beginning of the period, with a notable peak in the first few months, followed by a steady decline through the middle of the year. From April to August, the sales figures remained relatively stable, showing little fluctuation. However, towards the end of the year, there is a sharp increase in revenue, culminating in a significant rise in the final month. This pattern suggests a seasonal fluctuation, where sales are strongest at the beginning and end of the year, while the months in between show a consistent but lower level of performance.  This indicates that seasonal factors, such as changes in market demand or the timing of promotional activities, are likely contributing to these fluctuations. This fluctuation indicates potential seasonality or external factors influencing revenue generation, with a recovery in December, which ends the year on a high note.

likely due to post-holiday demand or promotions, while the months from March to October experience lower and more consistent sales, with a significant drop in October. This fluctuation indicates potential seasonality or external factors influencing revenue generation, with a recovery in December, which ends the year on a high note.

- Product Sales Distribution
The pie chart of product sales distribution demonstrates that Drinking water contributes to 22.7% of total revenue, whereas Milk Tea 18.61% and Water Dispenser	17.54% account for much smaller shares. Given Drinking water dominance, there may be opportunities to expand its marketing efforts and optimize its pricing strategy to capitalize on its popularity.

- Customer Segmentation and Buying Behavior
The bar chart depicting customer segments by purchase frequency highlights that KFC is a high-value customer based on her purchase trunover and contributed to 31% of total sales. This indicated a strong opportunity to focus on customer retention programs, loyalty rewards, and targeted marketing for these segments to increase lifetime value.

- Salesperson Sales Performance
The bar chart visualizing salesperson performance reveals that Vaughn, Harlon contributes the highest revenue throughout for the two years, with notable peaks in Q1 and Q3. This suggests that Vaughn Harlon has a strong ability to capture high-value sales during key periods, possibly leveraging targeted strategies or client relationships during peak demand times.

In contrast, other salespeople show more inconsistent performance, with some achieving higher revenue in certain months, while others maintain steady but lower sales levels across the year. This indicates a potential opportunity for the lower-performing salespeople to refine their approach, especially during peak months.

### Recommedations 
Based on the analysis of the data provided, the following recommendations may be considered:

Conclusion 

References 

### Limitations 

### References 



### Data Analysis 
