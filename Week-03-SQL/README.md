# week 3 assignment

In this assignment i used the superstore dataset and worked with advanced sql concepts.

first i created customers, products and orders tables from the sample_superstore table using select distinct.

Then i used subqueries to find orders having sales greater than average sales and also found the highest sales order for each customer.
after that i used cte to calculate total sales for every customer and to find customers whose sales are above average.
i also used window functions like rank() and row_number(). rank was used to rank customers based on total sales and row_number was used to number orders within each customer.

for the final query i combined join, cte and window function to display customer name, total sales and customer rank.

In the mini project i found top 5 customers, bottom 5 customers, customers with only one order, customers having above average sales and highest order value for each customer.

from this assignment i understood how subqueries, ctes and window functions can be used together for sales analysis and customer ranking.

#brief insights

few customers generated very high sales compared to others.
some customers made only one order.
customer ranking helped identify top performing customers.
ctes and window functions made complex analysis easier.
advanced sql can be used to get useful business insights from sales data.
