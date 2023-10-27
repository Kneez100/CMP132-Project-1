# CMP132-Project-1
# Inventory Management System

## Implemented Functionalities

### Product Class

- `display_product_info`: Display product information including ID, name, category, price, and quantity in stock.
- `sell`: Update the quantity in stock when a sale is made and check for sufficient stock.
- `restock`: Increase the quantity in stock.

### Inventory Class

- `add_product`: Add a product to the inventory.
- `update_stock`: Update the stock quantity for a product.
- `get_product_info`: Retrieve and display product information by product ID.
- `record_sale`: Record a transaction and update the sales history.
- `generate_stock_report`: Generate a report of current stock levels.
- `generate_sales_history_report`: Generate a report of sales history including transaction details.
- `calculate_total_revenue`: Calculate the total revenue.
- `generate_revenue_report`: Generate a report of the total revenue.

### Transaction Class

- `calculate_total_amount`: Calculate the total amount for a transaction.
- `make_sale`: Make a sale, update product quantities, and check for stock availability.

## Test Results

### Product Class Test Result

- `display_product_info`: Displayed product information for product1 and product2.
- `sell`: Successfully sold products with details. Checked and returned an error message for insufficient stock.
- `restock`: Successfully restocked products with the new stock level displayed.

### Inventory Class Test Result

- `add_product`: Added product1 and product2 to inventory, and verified that product2 already exists.
- `update_stock`: Updated the stock for product1, and checked for a product that doesn't exist in the inventory.
- `get_product_info`: Retrieved and displayed product information for product1.
- `record_sale`: Recorded a sale transaction.
- `generate_stock_report`: Generated and displayed a report of current stock levels.
- `generate_sales_history_report`: Generated and displayed a report of the sales history.
- `calculate_total_revenue`: Calculated and displayed the total revenue.
- `generate_revenue_report`: Generated and displayed a report of the total revenue.
