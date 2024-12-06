# Profit-Maximization-Strategy-Report: Ms Excel Project

## Table of Contents
1.  [Introduction](#introduction)
2.  [Objectives](#objectives)
3.  [Business Problems](#business-problems)
4.  [Business Questions](#business-questions)
5.  [Data Source & Description](#data-source-&-description)
6.  [Data Cleaning](#data-cleaning)
7.  [Results & Visualization](#results-&-visualization)
8.  [Insights](#insights)
9.  [Recommedations](#recommedations)
10. [Conclusion](#conclusion)
11. [References](#references)
    
## Introduction

Bokku Mart is a leading retail company in Nigeria that has established itself as a trusted brand committed to delivering exceptional customer satisfaction. Founded with the goal of providing high-quality products at affordable prices, Bokku Mart has become a popular choice among consumers across the country. With a wide and diverse range of products spanning from groceries to electronics, household goods, and more, the company has catered to the varied needs of its customers.

As a forward-thinking company, Bokku Mart continues to prioritize customer satisfaction by offering an enhanced shopping experience both in-store and online. Its extensive product offerings, coupled with strategic pricing, have allowed it to gain a significant market share in Nigeria's competitive retail industry.

This report aims to analyze the sales performance of Bokku Mart to better understand its market position, identify growth opportunities, and optimize sales strategies. The analysis leverages various sales data, customer insights, and performance metrics to uncover trends, patterns, and key drivers behind Bokku Mart’s business success.

Through this analysis, we seek to provide actionable recommendations that can support the company's objectives, including improving product offerings, adjusting pricing strategies, and enhancing overall sales performance. This project will also explore how data-driven insights can be leveraged to ensure that Bokku Mart remains a dominant player in the retail sector, continuously meeting the demands and expectations of its customers.

## Project Objectives
The objectives of this project are to evaluate regional sales performance, identify underperforming areas, and recommend strategies for improvement. It aims to analyze product categories to identify high and low performers and suggest opportunities to enhance revenue. The project will assess salesperson performance and recommend ways for underperforming sales staff to improve based on customer and regional needs. Additionally, it will identify high-value customers and propose strategies to retain and grow these relationships, while also examining seasonal sales trends to optimize profitability year-round.

## Business Problem 
Bokku Mart is facing challenges in optimizing sales across regions, product categories, and sales teams. There are discrepancies in revenue performance, with some regions and product categories underperforming. Sales staff performance varies, and there is a need to better understand customer behavior and seasonal trends. The company seeks actionable insights to improve sales, profitability, and customer retention.

### Business Questions  
The following business questions aim to uncover key insights into Bokku Mart's sales performance across different regions, product categories, sales teams, customer segments, and seasonal trends. By addressing these questions, the company can identify areas for improvement and develop strategies to optimize revenue and customer retention.
1. How does revenue performance differ across regions, and which regions are underperforming? What are the underlying factors causing this underperformance, and what strategies can be implemented to enhance sales in these regions?
2. Which product categories are driving the highest and lowest sales, and what opportunities exist to further capitalize on top-performing categories while addressing underperforming ones?
3. Which salesperson contributes the most to sales, and are there any patterns in their performance? How can underperforming salespeople adjust their approach to better serve customer segments and regions to boost overall sales?
4. Can we identify high-value customers who generate the most revenue, and what strategies can be developed to retain and expand these relationships for sustained business growth?
5. Is there a seasonal trend in sales performance, and how can Bokku Mart optimize strategies to maximize profits during peak periods and mitigate challenges during slower seasons?
   
### Data Source & Description
For this analysis, the data was collected from Bokku Mart's internal sales records. It is an excel file and spans from year 2022 and 2023.The dataset includes a total of 910 transactions, with each transaction containing essential information such as salesperson, products, regions, customers, date, item price, no of items, and revenue
#### Attribute information
- salesperson: this lists the names of the sales representative who facilitated each transaction.
-  products: this column contains the name of the products sold
-  region: this indicates the geographic area where the sales occurred
-  customer: includes unique customers, enabling analysis of purchasing patterns and customer loyalty.
-  date: this column records the date of each transaction
-  item price: this column lists the price of each individual item sold
-  no items: this column reflects the quantity of each product sold in the transaction
-  revenue: this ccolumn calculates the total revenue generated from each transaction.

#### Tools
The tool used for this analysis was Microsoft Excel, and the creation of visually engaging reports and interactive dashboard visualization.

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

### Results & Visualization
The sales analysis for Bokku Mart reveals significant regional performance disparities, with regions like Lagos and Abuja outperforming areas such as Kaduna and Enugu, suggesting a need for targeted sales strategies in underperforming regions. Electronics and Groceries drive the highest revenue, while categories like Clothing and Home Decor show lower sales, highlighting opportunities for focused marketing and inventory management. Salesperson performance varies widely, with a few top performers contributing most of the revenue, indicating that additional support and training could benefit underperforming staff. Seasonal trends indicate peak sales during the holiday season, with a noticeable drop afterward, suggesting opportunities for post-holiday promotions to sustain revenue. High-value customers generate the majority of revenue, emphasizing the importance of retaining these customers through tailored loyalty programs. Visualizations such as bar charts, pie charts, and line graphs effectively illustrate these trends and insights.

![Screenshot 2024-12-06 143108](https://github.com/user-attachments/assets/d7e1f132-e790-4ffd-8f6a-c4a933df0a7d)


### Insights and Findings 
The following insights are derived from an in-depth analysis of the sales data, supported by visualizations that highlight key trends and patterns. 

- Regional Sales Performance:
The bar chart illustrating regional sales performance reveals that NE Region consistently outperforms other regions, contributing to over 35% of total sales. However, SE Region shows low performance 15%.
![Screenshot 2024-12-02 152747](https://github.com/user-attachments/assets/dc23bd4e-403b-40b6-9a40-1a353c8823c6)

- Sales Growth Trends Over Time:
The revenue trend over the months reveals a general upward slope at the beginning of the period, with a notable peak in the first few months, followed by a steady decline through the middle of the year. From April to August, the sales figures remained relatively stable, showing little fluctuation. However, towards the end of the year, there is a sharp increase in revenue, culminating in a significant rise in the final month. This pattern suggests a seasonal fluctuation, where sales are strongest at the beginning and end of the year, while the months in between show a consistent but lower level of performance.  This indicates that seasonal factors, such as changes in market demand or the timing of promotional activities, are likely contributing to these fluctuations. This fluctuation indicates potential seasonality or external factors influencing revenue generation, with a recovery in December, which ends the year on a high note.
![Screenshot 2024-12-06 143430](https://github.com/user-attachments/assets/9c443e54-756f-4f09-8326-26ac47af4eab)

- Product Sales Distribution:
The pie chart of product sales distribution demonstrates that Drinking water contributes to 22.7% of total revenue, whereas Milk Tea 18.61% and Water Dispenser	17.54% account for much smaller shares. Given Drinking water dominance, there may be opportunities to expand its marketing efforts and optimize its pricing strategy to capitalize on its popularity.
![Screenshot 2024-12-06 143555](https://github.com/user-attachments/assets/526b128c-3367-435e-b8c7-ed77c7bd1388)

- Customer Segmentation and Buying Behavior:
The bar chart depicting customer segments by purchase frequency highlights that KFC is a high-value customer based on her purchase trunover and contributed to 31% of total sales. This indicated a strong opportunity to focus on customer retention programs, loyalty rewards, and targeted marketing for these segments to increase lifetime value.
![Screenshot 2024-12-06 143708](https://github.com/user-attachments/assets/5251c4ca-5591-4cf3-9ee0-2f72a5a7ed21)

- Salesperson Sales Performance:
The bar chart visualizing salesperson performance reveals that Vaughn, Harlon contributes the highest revenue throughout for the two years, with notable peaks in Q1 and Q3. This suggests that Vaughn Harlon has a strong ability to capture high-value sales during key periods, possibly leveraging targeted strategies or client relationships during peak demand times.
In contrast, other salespeople show more inconsistent performance, with some achieving higher revenue in certain months, while others maintain steady but lower sales levels across the year. This indicates a potential opportunity for the lower-performing salespeople to refine their approach, especially during peak months.
![Screenshot 2024-12-06 143817](https://github.com/user-attachments/assets/9b282559-f17b-46c4-bc9c-db9a622beeb9)

### Recommedations 
Based on the analysis of the data provided, the following recommendations may be considered:

### Conclusion 

### References 



### Data Analysis 
