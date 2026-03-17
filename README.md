## Sales Analysis System (AdventureWorks SQL)

## Project Scenario

- The management team at AdventureWorks wants a Sales Analysis System to analyze sales trends and manage product prices.
  
- They have outlined the following requirements:
  
- Create a view to display all sales orders along with customer names, product names, and order totals.
- Create a stored procedure to update product prices, ensuring that the new price is not lower than 50% of the product's current price.
- Write a query to retrieve data from the view for analysis.
- Execute the procedure to update the price of a specific product.

## Tools Used

- SQL Server

## Database Structure

- SalesLT.SalesOrderHeader: Contains information about each sales order.
- SalesLT.SalesOrderDetail: Contains details of the products in each order.
- SalesLT.Customer: Contains customer details.
- SalesLT.Product: Contains product details.

## Key Concepts Used

Joins (INNER JOIN, LEFT JOIN)

GROUP BY and ORDER BY

Filtering using WHERE

Views, Stored Procedures


## Summary

- The Sales Analysis System successfully integrates customer, product, and order data to simplify sales reporting and analysis.
- It also ensures secure price updates through a controlled stored procedure that maintains data integrity.

## Author

Aishika Nandy
