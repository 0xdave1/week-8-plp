# week-8-plp
# 📦 E-commerce Store Database Management System

## 📝 Assignment Overview
This repository contains my solution for **Question 1** of the Week 8 assignment in the *Database Design & Programming with SQL* module at PLP Academy.

**Objective:**  
Design and implement a full-featured relational database using MySQL for a real-world use case.

**Chosen Use Case:**  
E-commerce Store – managing customers, products, orders, payments, and categories.

## 📂 Files Included
- `mystore.sql`: Contains all SQL statements for creating the database schema, tables, and relationship constraints.

## 🛠️ Technologies Used
- MySQL
- MySQL Workbench
- Visual Studio Code (for editing)

## 📐 Database Features
- **Well-structured tables** for Customers, Products, Orders, Payments, Categories, and junction tables.
- **Constraints**: `PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, `UNIQUE`
- **Relationships**:
  - One-to-One: Orders ↔ Payments
  - One-to-Many: Customers → Orders
  - Many-to-Many: Orders ↔ Products, Products ↔ Categories

## 🚀 How to Run
1. Clone the repository.
2. Open `mystore.sql` in MySQL Workbench.
3. Execute the script to create the database and tables.

## 📅 Submission Info
- **Deadline**: Wednesday, 25th September 2025
- **Status**: Submitted on time ✅

## 🙋‍♂️ Author
- David Joseph
- PLP Academy Student

