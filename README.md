# SQL-practice
It's my mini SQL project! It includes a custom dataset built in MySQL and a set of query challenges designed to test and improve your SQL skills.

## Files Included

- `create_dataset.zip` contains `create_dataset.sql` – Sets up the database schema and populates it with sample data.
- `queries_and_solutions.sql` – Contains SQL questions (as comments) and their corresponding solutions.

## Getting Started

1. Make sure you have MySQL installed (version 8.0+ recommended).
2. Open your SQL client (e.g., MySQL Workbench, DBeaver, or command line).
3. Run `create_dataset.sql` to create and populate the database.
4. Open `queries_and_solutions.sql` to explore the questions and run the queries.

## Sample Challenge

```sql
-- Q1: What is the total revenue generated in 2023?
SELECT SUM(amount) FROM sales WHERE YEAR(date) = 2023;

