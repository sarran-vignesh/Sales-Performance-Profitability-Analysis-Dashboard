# Sales Performance & Profitability Analysis Dashboard

A comprehensive Sales Analysis Power BI Dashboard designed to provide actionable insights into sales performance, product profitability,customer trends, and geographic patterns.
This project demonstrates strong analytical capability, data modeling expertise, and dashboard-building proficiency.

## Project Overview
                  1.Overall revenue and profit performance

                  2.Best-selling products and categories

                  3.Customer purchasing behavior

                  4.Regional sales distribution

                  5.Sales trends over time

                  6.KPIs to support data-driven decision-making

## Calculated Columns
                  Sales = 'orders'[List Price] * 'orders'[Quantity]

                  Discount Amount = ('orders'[Discount Percent] / 100) * [Sales]

                  Net Sales = [Sales] - [Discount Amount]

                  Cost Amount = 'orders'[cost price] * 'orders'[Quantity]

                  Profit = [Sales] - [Cost Amount]

                  Year = YEAR('orders'[Order Date])

                  Month = FORMAT('orders'[Order Date], "MMM")

                  Year Month = FORMAT('orders'[Order Date], "YYYY-MM")

                  
## DAX Used
                  Total Sales = SUM('orders'[Sales])

                  Total Net Sales = SUM('orders'[Net Sales])

                  Total Profit = SUM('orders'[Profit])

                  Profit Margin % = DIVIDE([Total Profit], [Total Sales])

                  Total Orders = DISTINCTCOUNT('orders'[Order Id])
## Conclusion

           1. Strong Sales in Key States like California, New York, Texas, and Florida contribute the highest portion of total revenue.

           2. Monthly sales show a steady upward trend.ear-over-year sales have improved moderately. Technology and Office Supplies are the top-performing categories.

           3. Furniture contributes good revenue but shows lower profit margins. Major cities such as Los Angeles, New York City, and Seattle drive the majority of urban sales.

           4. Smaller cities show stable but lower performance.

Western and Eastern regions show stronger performance compared to Central regions.
The overall sales performance shows consistent growth across most regions and product categories. 
The dashboard highlights strong revenue-generating states and categories, identifies underperforming areas, and provides clear insights into customer purchasing patterns.
By analyzing trends, regional demand, and profitability, the business can make informed decisions to improve sales strategy, optimize inventory, and target high-performing markets.

                  

                  

                  

