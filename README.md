# Customer Insights Model 
In this repository provides a comprehensive analysis of a SQL retail dataset, offering valuable insights into sales, order processing, customer information, product details, and branch information. The dataset comprises five essential tables: sales_fact, order_product_mapping, customer_info, product_info, and branch_details. 

## Objective
To design a normalized relational database schema for a retail business, enabling effective storage and management of key transactional and customer data. The schema allows tracking of sales, customers, products, and their relationships, with a focus on integrity and efficiency.

## Key Features

1. Database Creation:

Creates a database named retail_database.
Ensures proper usage of the database with the USE statement.

2. Table Definitions:

SALES_FACT: A fact table capturing details of sales transactions, with primary key ORDER_ID and additional attributes like CUSTOMER_ID, ORDER_DATE, and STORE_ID.
ORDER_PRODUCT_MAPPING: Maps products to orders with a composite primary key of ORDER_ID and PRODUCT_ID.
CUSTOMER_INFO: Stores customer details like customer_id, first_name, last_name, gender, and email.

3.Primary and Foreign Keys:

Implements constraints to enforce data integrity, e.g., linking ORDER_ID in SALES_FACT to ORDER_PRODUCT_MAPPING.
Ensures referential integrity between orders and their associated products.

4. Normalization:

Separates data into logical tables to reduce redundancy and ensure data consistency.

