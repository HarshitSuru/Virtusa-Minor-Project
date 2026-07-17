# Digital Library SQL

## Overview

This SQL project models a digital library system with books, students, and issued books. It includes schema creation, sample data loading, and reporting queries.


## Queries given
1. Find all books that have been issued but not returned within the allowed period (here, 14 days).
2. Measure how popular each book category is, based on borrow counts.
3. Remove inactive students who haven’t borrowed any books in the last 3 years.



## Database Schemas

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/0aed7a3d-99f8-42c4-a176-505f799ec2a3" />


## SQL Concepts Used

- Primary keys
- Foreign keys
- `JOIN`
- `WHERE`
- `COUNT`
- `ORDER BY`
- `DATEDIFF`
- `DATE_SUB`
- Subqueries

## Join Logic Used

- `IssuedBooks` joins with `Students` using `student_id`
- `IssuedBooks` joins with `Books` using `book_id`
- These joins help show overdue book details with both student and book information in a single result

## Screenshot

![Digital Library SQL Queries](./digital-library-sql.png)


## Author

Suru Harshit
