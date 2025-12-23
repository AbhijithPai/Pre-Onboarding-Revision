# Database Basics – Learning Log

📅 **Topic Covered:** Database Fundamentals  
🎯 **Goal:** Understand how data is stored, organized, and accessed in real-world systems

---

## 📌 What is a Database?
A **database** is an organized collection of data that allows efficient storage, retrieval, and management of information.

Examples:
- Employee records
- Sales transactions
- User accounts

---

## 📌 What is an RDBMS?
**RDBMS (Relational Database Management System)** stores data in **tables** with predefined schemas and relationships.

Examples:
- MySQL
- PostgreSQL
- Oracle
- SQL Server

Key features:
- Structured schema
- Relationships between tables
- Uses SQL for querying

---

## 📌 SQL vs NoSQL Databases

### SQL Databases
- Structured (tables, rows, columns)
- Fixed schema
- Strong consistency
- Uses SQL

Examples: MySQL, PostgreSQL

### NoSQL Databases
- Flexible schema
- Stores data as documents, key-value, graphs, etc.
- Scales easily

Examples: MongoDB, Cassandra

---

## 📌 Rows vs Columns

- **Row:** A single record (tuple)
- **Column:** A field/attribute of data

Example:
| EmployeeID | Name | Salary |
|-----------|------|--------|
| 101       | Alex | 50000  |

---

## 📌 Primary Key
- Uniquely identifies each row in a table
- Cannot be NULL
- No duplicate values

Example:
```sql
EmployeeID PRIMARY KEY
