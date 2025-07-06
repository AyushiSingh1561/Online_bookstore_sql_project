# 📚 Online Bookstore SQL Project

## 📌 Project Overview
This PostgreSQL-based SQL project models an online bookstore database system. It includes schema and data for books, customers, orders, and more. The SQL dump file was exported using pgAdmin and includes both structure and data.

## 🛠️ Tools & Technologies
- PostgreSQL
- pgAdmin 4

## 🗃️ Database Schema

### 📘 Books Table
- `book_id` (Primary Key)
- `title`
- `author`
- `genre`
- `published_year`
- `price`
- `stock`

### 👥 Customers Table
- `customer_id` (Primary Key)
- `name`
- `email`
- `location`

### 📦 Orders Table
- `order_id` (Primary Key)
- `customer_id` (Foreign Key)
- `order_date`

### 🧾 OrderDetails Table
- `order_id` (Foreign Key)
- `book_id` (Foreign Key)
- `quantity`
- `price`

## 📊 Potential Analyses
- Top 5 best-selling books
- Monthly revenue trends
- Customer purchase behavior
- Genre-wise performance
- Stock level alerts

## 💡 What I Learned
- Writing DDL & DML in PostgreSQL
- Using pgAdmin to export/restore databases
- Efficient data backup using `COPY FROM`
- Practiced SQL joins, subqueries, and aggregation

## 👩‍💻 Author
**Ayushi Singh**  
[LinkedIn](www.linkedin.com/in/ayushi-singh-9259b5244)
