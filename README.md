# 📚 Online Bookstore Sales Analysis (SQL Project)

This project explores a fictional online bookstore's sales data using SQL. With over 450 book records, the analysis helps uncover business insights such as top-performing genres, best-selling books, and revenue trends across years.

---

## 📌 Objective

- Analyze book sales data to generate actionable insights  
- Identify top-selling genres and authors  
- Understand pricing impact and publication trends  
- Practice advanced SQL skills with real-like data

---

## 🛠️ Tools & Technologies

- **Database:** PostgreSQL  
- **Language:** SQL  
- **Platform:** pgAdmin / SQL Editor  
- **Data Size:** 450+ rows

---

## 📂 Dataset Fields

| Field           | Description                          |
|----------------|--------------------------------------|
| `book_id`       | Unique book identifier               |
| `title`         | Book title                           |
| `author`        | Author's full name                   |
| `genre`         | Book genre (Fiction, Mystery, etc.)  |
| `year_published`| Year of publication                  |
| `price`         | Price of the book                    |
| `copies_sold`   | Number of copies sold                |

---

## 🧠 Key SQL Concepts Used

- `GROUP BY` and `ORDER BY`  
- `JOINs` and subqueries  
- Aggregate functions: `SUM()`, `AVG()`, `COUNT()`  
- Window functions: `RANK()`, `ROW_NUMBER()`  
- Conditional filtering using `WHERE`, `HAVING`

---

## 📊 Sample Insights

- **Most profitable genre:** Mystery  
- **Top-selling book:** Based on `copies_sold * price`  
- **Trend:** Older books tend to sell less despite higher prices  
- **Revenue by genre:** Revealed which genres consistently drive profit

---

## 📂 Datasets Included 🔗

- [`Books SQL.csv`](./Books%20Sql.csv.xlsx): Contains book details like title, author, genre, price, and copies sold  
- [`Orders SQL.csv`](./Orders%20Sql.csv.xlsx): Order data with purchase records  
- [`Customers SQL.csv`](./Customers%20Sql.csv.xlsx): Customer-level information for deeper insights  

----

📌 **Conclusion**

This project demonstrates my ability to perform detailed data analysis using SQL and communicate insights in a business
relevant context. It showcases both technical and analytical thinking, making it suitable for real-world applications.

---

## 📈 Sample Query

```sql
SELECT genre, SUM(price * copies_sold) AS total_revenue
FROM books
GROUP BY genre
ORDER BY total_revenue DESC;
---

## 👩‍💻 Author
**Ayushi Singh**  
[LinkedIn](www.linkedin.com/in/ayushi-singh-9259b5244)
