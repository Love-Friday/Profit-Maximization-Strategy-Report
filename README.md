# Profit-Maximization-Strategy-Report: Ms Excel Project

## Table of Contents
1. [Introduction](#introduction)

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Business Questions](#business-questions)
- [Results](#results) 
- [Recommedations](#recommedations)
- [Limitations](#limitations)
- [References](#references)

## Project Overview

Bokku Mart is a leading retail company in Nigeria, dedicated to customer satisfaction by providing high-quality products at affordable prices. 
The comapany offers a diverse range of products, making it a popular choice among consumers. 

This project aims to analyze the Bokku Mart dataset, which is a 'fictitious' dataset used as a case study to gain insights into customer behaviour, sales trends, and product performance.

The dataset comprises sales record collected from Bokku Mart, spanning from January 2022 to December 2023. It includes keyvariables such as. This data will enable us to analyze sales performance and customer behaviour across various regions. 

## Tools
The tool used for this analysis was Microsoft Excel, and the creation of visually engaging reports and interactive dashboard visualization.

## Problem Statement 
This analysis aims to evaluate the sales performance of products at Bokku Mart by examining key metrics such as total revenue from products sold, sales per customer, year-to-date revenue, and identifying the month and year with the highest profit. 

### Business Questions  
From the analysis, the management wants to an executive summary of the follwing based on the problem stated above. They include; 

- What is the total revenue?
- What is the total number of producrs sold?
- What are the sales per customer?
- What is the YTD revenue?
- Which month and year had the most profit?
- Where is the company seeing the most success by region?
- Which product should be the company continue to invest in and reasons?
- 

1. How does revenue vary across different regions, which regions are underperforming, why and how can we improve?
2. What product categories are driving the highest & lowest sales, and how can we capitalize on them further?
3. Which salesperson contributes the highest sales, are they any pattern in their performance? How can the less performing salespersons tailor their approcah to meet the unique needs of different customer segemts and regions to boost sales?
4. Can we identify key customers who generate the most revenue and tailor strategies to retain and grow their business?
5. Is there a seasonal trend in sales perfoemance, how can we adjust strategies to maximize profits during peak periods?

Additionally, the analysis will investigate regional sales trends and determine which products the company should continue to invest in. 

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
- used the PROPER function in the Salesperson column to convert text to proper case, correcting mixed capitalization.
- Applied VALUE(CLEAN) function in the item price column to eliminate non-printable characters and convert text values to numbers.
- The revenue column automatically updates by formatting it to calculate item price multiplied by the number of items  = H2 * I2 
- Inserted two additional columns to extract Year and Month values from the Date column
- utilized the YEAR function to extract the year from the Date column; =YEAR(K2 : K911)
- Employed the MONTH function to extract the month from the Date column;  =YEAR(L2 : L911)


Exploratory Data Analysis (EDA)




### Insights

In my profit maximization strategy report analysis, the result reveal a treasure of insights. The analysis results are summarized as follows;
The following insights are derived from an in-depth analysis of the sales data, supported by visualizations that highlight key trends and patterns. 
- Regional Sales Performance
The bar chart illustrating regional sales performance reveals that NE Region consistently outperforms other regions from the 2 year analysis, contributing to over 35% of total sales. However, SE Region shows low performance 15%.
![Screenshot 2024-12-02 152747](https://github.com/user-attachments/assets/dc23bd4e-403b-40b6-9a40-1a353c8823c6)



### Recommedations 
Based on the analysis of the data provided, the following recommendations may be considered:

Conclusion 

References 

### Limitations 

### References 



### Data Analysis 
