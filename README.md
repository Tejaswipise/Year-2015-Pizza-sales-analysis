# Year-2015 Pizza Sales Analysis
## Table of Contents
- [Recommendation](#Recommedation)
### 1. Project Objective
Analyze Pizza Sales Data of year 2015 to find trends and patterns to provide insights for content strategy decisions.

### 2. Dataset Source
- File Used: pizza_sales.csv 
- Source: [Pizza Sales Dataset of year 2015-kaggle](https://www.kaggle.com/datasets/nextmillionaire/pizza-sales-dataset)  
- Dataset contains of pizza sizes, categories, names, ingredients, id, order dates, days, times, id, and prices.

### 3. Problem Statements
- Sales Performance Analysis  
- Revenue Trends and Seasonality  
- Customer Prefernces and Order Patterns  
- Profitability Analysis

### 4. Tools USed
- MySQL Workbench – Data querying and cleaning  
- Power BI – Data visualization  
- Excel – Initial data exploration

### 5. Data Cleaning Steps
-  Changed the format of date from mm-dd-yyyy to yyyy-mm-dd
-  Created new column by extracted `Hour` from `order_time` for analysis
-  Created new columns by extracting 'Month' from `order_date`, `Month_Num` from `Month`, `Day_Num` from `order_day` for analysis.

### 6. SQL Insights
- Sales Performance Analysis(top 10 least and best selling Pizzas)
- Peak Sales hour
- Order Frequency by Day of Week
- Sales trends over seasonality by Analyzing the Total orders every month
- Customer spending behavior
- Average Orders
- Customer spending behavior based on pizza category and pizza sales
- Percentage of sales by pizza size and pizza category
- frequent order combinations
- Average revenue per order
- Gross profit and Profit margin per pizza
- Revenue generated by pizza size and pizza category

### 7. Visualizations (Power BI)
- **Bar chart**- Top 10 Best sellings and Least selling pizzas.
- **Pie Chart**- Percentage sales by Pizza Size.
- **Dount Chart**- Percentage sales by Pizza Category.
- **Funnel Chart**- Total Pizzas sold by PIzza Category.
- **Stacked Column Chart**- Order frequency by day of week.
- **Line and Cllustered Column Chart**- Peak sales by Hours.
- **Area Chart**- Peak sales by Month.
- **Line Chart**- Gross profit and Profit Margin per pizza.
- **Bar Chart**- Gross profit By Pizza Size.
- **Bar Chart**- Gross profit by Pizza category.

### 8. Key Insights
- The Thai Chicken Pizza is Sold the highest and The Brie Carre Pizza has the lowest sellings.
- The Large Size pizza contributes most to sales, gross profit and orders and XXL pizza is the least to contribute.
- The Classic category is the most loved as it contributes the more to orders and chicken category has lowest contribution to order.
- The Chicken category got large gross profit and veggie the lowest.
- The California Chicken Pizza made the highest gross profit as well as profit margin
- Friday is the day among the week days which has the peak orders.
- Between 12PM to 1PM the pizza orders are at the peak.
- July is the month where the orders are at the peak and october is the month having lowest pizza orders.
- The Hawaiian Pizza and The Thai chicken Pizza are the most frequently together ordered pizzas.
  
### 9. Conclusion
This analysis reveals strong trends and patterns showing which pizzas or what combination of pizzas are the most loved by customers, which makes good profit to the pizza company based on their sizes, categories. Also shows in which month, day of week, and what hour in a day customers would often buy pizzas.

### 10. Recommendations
- Promote slow moving items by launching targeted deals or combo offers.
- Launch offers on the most frequently brought combos on fridays/weekends to maximize the revenue.
- Discontinuing of XXL-size pizza would benefit the company by saving it's cost of production as XXL-sized pizza is making avery small amount of profit.
- Plan marketing campaigns around holidays or weekends to maximize revenue.
- To not let the sales of pizza drastically fall after a specific amount of time, launch a deal or an offer 
- Promote veggie category with chicken category by launching a combo deal of veggie annd chicken category to increase the gross profit.
- Pairing of any pizza which has maximum orders/revenue (California Chicken Pizza) with other slow selling pizza by offering a deal will increase the profit as well as promotes slow selling pizzas.
- More availability of Larger size pizzas in all categoreis can help in increasing the sales of all categories as well as increases the profir of larger size pizza

---

> *Note*: This project is part of my data analytics learning journey and showcases SQL analysis and Power BI visualization skills.
