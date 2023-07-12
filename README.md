# Walmart_sales_Data_Analysis

#About

This project aims to explore Walmart Sales data to understand top-performing branches and products, sales trends of of different products, customer behavior. The aim is to study how sales strategies can be improved and optimized. 

#Purposes Of The Project

The major aim of the project is to gain insight into the sales data of Walmart to understand the different factors that affect sales of the different branches.

#Analysis List

Product Analysis
Conduct analysis of the data to understand the different product lines, the product lines performing best, and the product lines that need to be improved.

Sales Analysis
This analysis aims to answer the question of the sales trends of products. The result of this can help us measure the effectiveness of each sales strategy the business applies and what modifications are needed to gain more sales.

Customer Analysis
This analysis aims to uncover the different customer segments, purchase trends, and profitability of each customer segment.

#Approach Used


Data Wrangling: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.

Build a database
Create a table and insert the data.
Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are filtered out.


Feature Engineering: This will help us generate some new columns from existing ones.
Add a new column named time_of_day to give an insight into sales in the Morning, Afternoon, and Evening. This will help answer the question of which part of the day most sales are made.


Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question of which week of the day each branch is busiest.

Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.


Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.

Conclusion:

