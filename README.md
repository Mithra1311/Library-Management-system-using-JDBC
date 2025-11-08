 Library Management System (JDBC + MySQL)
Description:
A Java-based Library Management System using JDBC and MySQL. Allows users to view available books, lend, and return them with real-time database updates for efficient library operations.
 Features
Display list of available books with quantity
Lend a book (decrease quantity)
Return a book (increase quantity)
MySQL database connectivity using JDBC
Technologies Used
Java
JDBC
MySQL
SQL Queries
 Setup Instructions
Create a MySQL database named library.
Run the following SQL commands:
CREATE TABLE books (
id INT PRIMARY KEY,
title VARCHAR(100),
quantity INT
);
INSERT INTO books VALUES
(1, 'Java Programming', 5),
(2, 'Data Structures', 3),
(3, 'Database Systems', 4);
Update your MySQL username and password in the Java code:
static final String USER = "root";
static final String PASS = "your_password";
Compile and run the Java program.
Sample Output
===== Library Menu =====
1. Show Books
2. Lend a Book
3. Return a Book
4. Exit
Concept Used
Java Database Connectivity (JDBC)
SQL operations (SELECT, UPDATE)
Object-Oriented Programming concepts
 Conclusion
This project demonstrates basic database interaction using JDBC and provides a clear understanding of CRUD operations in Java for real-world applications.

