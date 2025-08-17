# 📚 Library Management System – SQL Project Overview
🔖 Project Title:

Library Management System

This project is based on My Sql of library management system where we are dealing with books issued and returned within a period of time.

🎯 Objectives:

The goal of this project is to design and implement a relational database system to efficiently manage operations in a library. This includes:

Managing branches, employees, members, books, and their rental/return statuses

Performing essential CRUD operations (Create, Read, Update, Delete)

Tracking book issues, returns, and rental income

Monitoring member activity, employee management, and overdue books

Creating summary and report tables for analytics

🏗️ Database Design (Schema)

The database includes the following tables:

branch – Stores branch information and manager details

employees – Stores employee details, linked to a branch

members – Stores library member details

books – Stores book information including title, author, rental price, and status

issued_status – Tracks which member issued which book, with reference to employee and book

return_status – Tracks book returns, linked to issued status

📈 Highlights and Best Practices Used:

Strong use of joins (including LEFT JOIN, INNER JOIN)

Good use of aggregations (SUM, COUNT, GROUP BY, HAVING)

Followed normalization principles by separating entities

Used foreign key constraints to enforce relationships

Modular and meaningful query structure for real-world use cases

✅ Conclusion

This Library Management System project demonstrates a robust implementation of SQL for real-world data handling. It supports core library operations, enforces data integrity, and enables valuable reporting and analysis through efficient SQL queries.

All tables use primary keys, and appropriate foreign keys ensure referential integrity.
