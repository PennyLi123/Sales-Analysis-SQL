# <p align="center">E-commerce Toy Sales Analysis</p> 
# Project Overview
Utilise SQL to assist a e-commerce toy product company in enhancing its business growth by performing user analysis and toy sales analysis.

# SQL skills used in this project
* Subqueriers
* Left Join
* Case when
* Group by
* Order by
* Distinct
* Temporary table

# Built with
* MySql workbench 

# Dataset Schema
Work with six related tables, which contain eCommerce data about:
• Website Activity
• Products
• Orders and Refunds

# Dataset Schema
![Schema.png](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Schema.png){:width="430"}


# Query Result - User Analysis
### 1. How many of e-commerce website visitors come back to the website for another session?

![User Analysis Results/User Analysis Q1.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/User%20Analysis%20Results/User%20Analysis%20Q1.jpg){:width="430"}

### 2. What is the minimum, maximum, and average time between the first and second session for customers who do come back?

![User Analysis Results/User Analysis Q2.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/User%20Analysis%20Results/User%20Analysis%20Q2.jpg){:width="430"}

Repeat visitors are coming back about a month later, on average.

### 3. Which channels are repeat visitors come back through? If its all direct type-in, or if company paying for these customers with paid search ads multiple times.

![User Analysis Results/User Analysis Q3.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/User%20Analysis%20Results/User%20Analysis%20Q3.jpg){:width="430"}

When customers come back for repeat visits, they come mainly through organic search, direct type-in, and paid brand.
Only about 1/3 come through a paid channel, and brand clicks are cheaper than non-brand. 
So all in all, company is not paying very much for these subsequent visits.

### 4. Comparison of conversion rates and revenue per session for repeat sessions vs new sessions.

![User Analysis Results/User Analysis Q4.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/User%20Analysis%20Results/User%20Analysis%20Q4.jpg){:width="430"}

Repeat sessions are more likely to convert, and produce more revenue per session.


# Query Result - Sales growth analysis
### 1. Show company's volume growth for the life of the business.
![Sales Growth Results/Sales Growth Q1.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Sales%20Growth%20Results/Sales%20Growth%20Q1.jpg){:width="430"}

At the end of a three year run of this business, the company has large growth in both orders volume and session's volume. 

Compare the 60 orders from the first quarter, the company have about 100 times more orders now. 
And similar large growth in session volume.

### 2. Showcase all of the efficiency improvements since the company launched, for session-to-order conversion rate, revenue per session, and revenue per order.
![Sales Growth Results/Sales Growth Q2.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Sales%20Growth%20Results/Sales%20Growth%20Q2.jpg){:width="430"}

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
![Sales Growth Results/Sales Growth Q3.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Sales%20Growth%20Results/Sales%20Growth%20Q3.jpg){:width="430"}

### 4. Show overall session-to-order conversion rate trends for channels, by quarter.
![Sales Growth Results/Sales Growth Q4.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Sales%20Growth%20Results/Sales%20Growth%20Q4.jpg){:width="430"}
Nice steady growth are showed for brand search, organic search and direct type in channels. Investor would be impressed to see this result.

### 5. Recognize seasonality by analysing revenue and margin of the product, and total sales and revenue.
![Sales Growth Results/Sales Growth Q5.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Sales%20Growth%20Results/Sales%20Growth%20Q5.jpg){:width="430"}
There's a rush leading up to the Chritsmas and New Year's holiday season at the end of the year, same as Feburary due to Valentine's day.

### 6. What is the impact of introducing new products.
![Sales Growth Results/Sales Growth Q6.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Sales%20Growth%20Results/Sales%20Growth%20Q6.jpg){:width="430"}
Adding additional products making the product page is the click through rate going up from around 71% at the beginning of the business to 85% in the most recent month.
And similarly, the rate of people seeing the product page and then converting to a full paying order has gone up from 8%, 6%, 7% to all the way up to around 14% in the most recent months.

### 7. How well each product cross-sells from one another?
![Sales Growth Results/Sales Growth Q7.jpg](https://github.com/PennyLi123/Sales-Analysis-SQL/blob/master/Sales%20Growth%20Results/Sales%20Growth%20Q7.jpg){:width="430"}
Product 3 cross sells pretty well for Product 1, Product 4 cross sells really well for all of the products above 20% of the orders for primary product one, two and three end up purchasing product for as well.







