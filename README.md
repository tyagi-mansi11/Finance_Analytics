# Finance_Analytics <br>

## Project Overview <br>

This SQL project is part of the Bootcamp at CodeBasics. The project involves performing financial analytics on Atliq hardware's data. The primary objective is to create required reports and extract valuable insights.
<br>

## Teach Stacks <br>

• MYSQL Workbench - For SQL queries <br>
• Excel - For visualization <br>

## Company Background and Problem Statement<br>
AtliQ Hardware is a company which has grown vastly in recent years and is all over the globe. The company specializes in selling computer hardware and related products through three channels i.e. Retailers, Direct and Distributors. <br>
<br>
Excel is a common and accessible way for individuals and businesses to analyze and visualize data. Despite having a wide range of tools and functions for performing basic to advanced data analysis tasks, working with large Excel files can be slow and unresponsive, often crashing or freezing during use. The struggle with handling extensive datasets leads to performance issues and data corruption risks.  <br>
<br>
In this project, I utilized SQL to address the limitations of Excel in handling and analyzing vast datasets. This enables the generation of required reports and extracts valuable insights, leading to enhanced company operational efficiency.

## Project Structure <br>

The project is organized as follows: 

• _[SQL Queries](https://github.com/tyagi-mansi11/Finance_Analytics/blob/306688d1877235162696adc7ef841ef9370e73c4/SQL%20Queries.pdf)_: Contains the SQL queries   <br>
• _[Finance Analytics](https://github.com/tyagi-mansi11/Finance_Analytics/blob/306688d1877235162696adc7ef841ef9370e73c4/Finance_Analytics.pdf)_: Contains ppt of the project

The following reports are generated:

[1] Croma India product-wise sales report for fiscal year 2021 <br>
[2] Gross monthly total sales report <br>
[3] Yearly gross sales report <br>
[4] Top markets, products and customers for a given fiscal year <br>
[5] Net sales % share by Customers <br>
[6] Net sales % share by different Regions <br>
[7] Top 2 markets in every region by their gross sales for a given fiscal year <br>
[8] Top 2 products per Division by their sold quantity for a given fiscal year <br>



## Understanding Datasets  
<pre>
[1] dim_customer
     • 27 distinct markets (ex India, USA)
     • 75 distinct customers throughout the market
     • Two types of platforms:
          • Brick & Motors - Physical/offline store
          • E-commerce - Online Store 
     • Three channels: Retailer, Direct, Distributors <br>
     
[2] dim_market
     • 27 distinct markets (ex India, USA, Spain)
     • 7 sub-zones
     • 4 regions i.e APAC, EU, NA, LATAM  <br>
          APAC- Asia Pacific
            EU- European Union
            NA- North American
         LATAM- Latin America
     
[3] dim_product
    • Divisions
           • P & A - Peripherals, Accessories
           • PC - Notebook, Desktop
           • N & S - Networking, Storage
  
[4] fact_forecast_monthly
Contains the value of forecast quantity values for each customer.

[5] fact_sales_monthly
Contains the value of sold quantity.

[6] fact_freight_cost
The details of travel costs and other costs for each market with the fiscal year.
  
[7] fact_gross_price
The details of gross prices with product code.
  
[8] fact_manufacturing_cost
The details of manufacturing cost with product code with year.
  
[9] fact_Pre_invoice_dedutions
The details of pre-invoice deductions percentage for each customer with year.
  
[10] Post_invoice_deductions
The details of post-invoice deductions and other deductions.
  
</pre>

As per the requirements in the project following function, views and stored procedures are created <br>
<br>
<img src="https://github.com/tyagi-mansi11/img/blob/2d2acf75e3d302df308efabbb4fef1e72f017772/Screenshot%202024-09-02%20230251.png"  width="350" height="300">

## Learnings

Following are the various SQL concepts applied in the project:

• Basic SQL commands  <br>
• Filtering and Sorting Data  <br>
• Aggregating Data  <br>
• Joining Tables  <br>
• User-defined Function  <br>
• Window Functions  <br>
• CTE   <br>
• Stored Procedures  <br>
• Views  <br>




