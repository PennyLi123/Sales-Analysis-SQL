# Sales-Analysis
# Project Overview
Utilise SQL to assist a e-commerce toy product company in enhancing its business growth by performing toy sales analysis.

# SQL skills used in this project
* Subqueriers
* Left Join
* Case when
* Group by
* Order by
* Distinct
* Temporary table
* Window function

# Built with
* MySql workbench 

# Dataset Schema
Work with six related tables, which contain eCommerce data about:
• Website Activity
• Products
• Orders and Refunds

# Dataset Schema
<img src="https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Schema.png" width="430">



# Query Result - Sales growth analysis
### 1. Show company's volume growth for the life of the business.

<img src="https://github.com/PennyLi123/Sales-Analysis-SQL/raw/master/Sales%20Growth%20Results/Sales%20Growth%20Q1.jpg" width="150">

At the end of a three year run of this business, the company has large growth in both orders volume and session's volume. 

Compare the 60 orders from the first quarter, the company have about 100 times more orders now. 
And similar large growth in session volume.

### 2. Showcase all of the efficiency improvements since the company launched, for session-to-order conversion rate, revenue per session, and revenue per order.

<img src="https://github.com/PennyLi123/Sales-Analysis-SQL/raw/master/Sales%20Growth%20Results/Sales%20Growth%20Q2.jpg" width="450">

The session to order conversion rate has gone from 3% to 8%. 
The revenue per order has gone from $49 to above $60 by doing cross-sell.
The revenue per session has gone from around $1.59 to over $5.

### 3. Show orders growth for specific channels.
Channels:
•Gsearch nonbrand, 
•Bsearch nonbrand, 
•brand search overall, 
•organic search, 
•direct type-in

<img src="https://github.com/PennyLi123/Sales-Analysis-SQL/raw/master/Sales%20Growth%20Results/Sales%20Growth%20Q3.jpg" width="600">

### 4. Show overall session-to-order conversion rate trends for channels, by quarter.

<img src="https://github.com/PennyLi123/Sales-Analysis-SQL/raw/master/Sales%20Growth%20Results/Sales%20Growth%20Q4.jpg" width="660">

Nice steady growth are showed for brand search, organic search and direct type in channels. Investor would be impressed to see this result.

### 5. Recognize seasonality by analysing revenue and margin of the product, and total sales and revenue.

<img src="https://github.com/PennyLi123/Sales-Analysis-SQL/raw/master/Sales%20Growth%20Results/Sales%20Growth%20Q5.jpg" width="700">

There's a rush leading up to the Chritsmas and New Year's holiday season at the end of the year, same as Feburary due to Valentine's day.

### 6. What is the impact of introducing new products.

<img src="https://github.com/PennyLi123/Sales-Analysis-SQL/raw/master/Sales%20Growth%20Results/Sales%20Growth%20Q6.jpg" width="550">

Adding additional products making the product page is the click through rate going up from around 71% at the beginning of the business to 85% in the most recent month.
And similarly, the rate of people seeing the product page and then converting to a full paying order has gone up from 8%, 6%, 7% to all the way up to around 14% in the most recent months.

### 7. How well each product cross-sells from one another?

<img src="https://github.com/PennyLi123/Sales-Analysis-SQL/raw/master/Sales%20Growth%20Results/Sales%20Growth%20Q7.jpg" width="460">

Product 3 cross sells pretty well for Product 1, Product 4 cross sells really well for all of the products above 20% of the orders for primary product one, two and three end up purchasing product for as well.







