# Pizza-sales-analyisis
This project aims to delve into a comprehensive analysis of a pizza sales data to extract valuable insights that can drive strategic business decisions. By examining key metrics and identifying trends to help optimize sales strategies, improve customer satisfaction, and ultimately boost revenue.

# TOOLS USED
- SQL – Data cleaning and Analysis,
- Power BI – Creation of Report and Visualization

# Data Sourcing
This data was obatained from kaggle
Here's a link to the Data on Kaggle:(https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)
# Data Description
This pizza sales dataset make up 12 relevant features:
The data contains just one sheet with 12 columns and 48,620 rows
-order_id: Unique identifier for each order placed by a table

-order_details_id: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)
-pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price
-quantity: Quantity ordered for each pizza of the same type and size
-order_date: Date the order was placed (entered into the system prior to cooking & serving)
-order_time: Time the order was placed (entered into the system prior to cooking & serving)
-unit_price: Price of the pizza in USD
-total_price: unit_price * quantity
-pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)
-pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price
-pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)
-pizza_name: Name of the pizza as shown in the menu

# DATA CLEANING AND TRANSFORMATION
 The data was efficiently cleaned and made more usable using Microsoft SQL Server. Some of the transformation and cleaning as effected are as follow;
 1. Converting order date and order time columns into their appropriate data type.
 ```sql
alter table pizza_sales alter column order_date date
```
```sql
alter table pizza_sales alter column order_time time
```
2.


 
