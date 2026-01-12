# 📱 phone-store-inventory

I would like to help phone stores keep accurate and reliable inventory data.
I believe the first step is enforcing strong business rules at the database level.
This project records all phones available in a store inside a SQL database table.

I am asking the public at large to submit database table scripts to implement this inventory system.

## 📌 Spec

The full specification for this project is included in the repository in the file called spec.txt.

## 📦 Deliverables

The following three files are required to implement the requirements for this repository.
Details for each file are described in the spec.

1. table.sql

Creates the database and phone inventory table
Includes all required constraints

2. sampledata.sql

Inserts sample phone inventory data
Demonstrates valid data according to business rules

3. reports.sql

Contains useful queries and reports
Examples: inventory list, low-stock phones, total inventory value

### 📜 Business Rules

- Each phone must have a unique Brand and Model combination
- Quantity in stock cannot be negative
- Price must be a positive value
- Purchase date cannot be in the future

 ## 🛠️ SQL Requirements

- Primary key
- Properly named columns
- Appropriate data types
- NOT NULL constraints where applicable
- Data integrity constraints (UNIQUE, CHECK)
- Files must be re-runnable, including:
- DROP TABLE IF EXISTS
- DROP DATABASE IF EXISTS
- CREATE DATABASE
- USE database name
