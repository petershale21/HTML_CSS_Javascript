## Sales Management Script

## Overview

This JavaScript script performs basic sales and inventory management functions. It calculates total sales, generates receipts for orders, and checks stock levels of products.

## Features

### 1. Total Sales Calculation
The script calculates the total sales amount based on an array of sales transactions. Each transaction includes:
item: Name of the item sold.
quantity: Number of items sold.
price: Price per item.

### 2. Receipt Generation
The script generates a detailed receipt for customer orders, displaying:
item: Name of the ordered product.
quantity: Amount of each item ordered.
price: Price per unit.
total: The total cost per item and the grand total.

### 3. Stock Level Checking
The script checks and logs the stock status of different products:
If the product has stock available, it is marked as "In Stock."
If the stock level is 0, it is marked as "Out of Stock."

## Code Explanation
calculateTotalSales(sales): Iterates through the sales array and computes the total revenue.
generateReceipt(orders): Prints a formatted receipt with item details and the grand total.
checkStockLevels(products): Checks inventory levels and logs stock availability.

## Usage
1. Open your web browser.
2. Go to the inspect section by right clicking on a blank area and clicking inspect. 
3. Open the browser's developer console and execute the script.

The output will include:
The total sales amount.
A formatted receipt with a breakdown of purchases.
The stock availability of different products.

## Example Output
```

Total Sales Amount: 1825
Receipt:
----------------------
Espresso - Quantity: 2, Price: $3.5, Total: $7
Latte - Quantity: 3, Price: $4.0, Total: $12
Cappuccino - Quantity: 1, Price: $4.5, Total: $4.5
----------------------
Grand Total: $23.5
Laptop is In Stock.
Headphones is Out of Stock.
Smartphone is In Stock.

## Notes

The script can be expanded to include tax calculations and discounts.

The stock check function can be enhanced to handle dynamic updates.

## Author

This script is intended for educational purposes to demonstrate basic sales and inventory management in JavaScript.

