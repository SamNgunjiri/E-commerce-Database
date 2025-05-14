🛒 E-Commerce Database System

📌 Project Overview

This project presents a well-structured relational **E-Commerce Database Management System** designed and implemented using **MySQL**. It supports key business operations such as product listings, order processing, cart functionality, and payment recording — all crucial to the operation of a basic online store.

🎯 Objectives

- Design a normalized, relational database schema.
- Use only MySQL to define entities and enforce data integrity.
- Support user registration, product management, cart, orders, and payments.

 🗂️ Database Structure

The system consists of the following core tables:

| Table Name     | Description                                               |
|----------------|-----------------------------------------------------------|
| `users`        | Stores customer information                               |
| `categories`   | Organizes products into logical groups                    |
| `products`     | Stores detailed product listings                          |
| `orders`       | Records order transactions from users                     |
| `order_items`  | Stores product-specific details for each order            |
| `cart_items`   | Captures items added to cart by users                     |
| `payments`     | Records payments made for orders                          |

Referential integrity is enforced through appropriate `PRIMARY KEY` and `FOREIGN KEY` constraints.

 🛠️ Technologies Used

- **Database Engine:** MySQL
- **Scripting Language:** SQL (DDL only)
- **Platform:** Localhost or any MySQL-compatible DBMS

 🚀 How to Run the Project

1. Clone this repository or download the `.sql` file directly.
2. Open your MySQL client (such as MySQL Workbench, phpMyAdmin, or CLI).
3. Run the script:

```sql
SOURCE path_to/ecommerce_db.sql;


Link to ERD: https://drawsql.app/teams/vesto/diagrams/e-commerce
