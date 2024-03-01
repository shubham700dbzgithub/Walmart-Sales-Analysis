# Walmart-Sales-Analysis

About
This project aims to explore the Walmart Sales data to understand top performing branches and products, sales trend of of different products, customer behaviour. The aims is to study how sales strategies can be improved and optimized. 

Purposes Of The Project: 
The major aim of thie project is to gain insight into the sales data of Walmart to understand the different factors that affect sales of the different branches.

Details about fields:

invoice_id	: Invoice of the sales made	VARCHAR(30)
branch: Branch at which sales were made	VARCHAR(5)
city: The location of the branch  VARCHAR(30)
customer_type:  The type of the customer	VARCHAR(30)
gender:	Gender of the customer making purchase	VARCHAR(10)
product_line:	Product line of the product solf	VARCHAR(100)
unit_price: 	The price of each product	DECIMAL(10, 2)
quantity: 	The amount of the product sold	INT
VAT:  The amount of tax on the purchase	FLOAT(6, 4)
total: The total cost of the purchase	DECIMAL(10, 2)
date:The date on which the purchase was made	DATE
time: The time at which the purchase was made	TIMESTAMP
payment_method:	The total amount paid	DECIMAL(10, 2)
cogs	: Cost Of Goods sold	DECIMAL(10, 2)
gross_margin_percentage:	Gross margin percentage	FLOAT(11, 9)
gross_income: 	Gross Income	DECIMAL(10, 2)
rating: 	Rating	FLOAT(2, 1)

Analysis List: 
1. Product Analysis: 
Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.

2. Sales Analysis:
This analysis aims to answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the business applies and what modificatoins are needed to gain more sales.

3. Customer Analysis:
This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.

Approch Used:
1. Data Wrangling:- This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.
a. Build a database
b. Create table and insert the data.
c. Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are 
   filtered out.
