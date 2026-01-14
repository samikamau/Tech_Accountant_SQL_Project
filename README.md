SQL-Practice-Project/
│
├── 01_Create_Tables.sql
-- 2️⃣ CREATE TABLES CREATE TABLE customers ( customer_id SERIAL PRIMARY KEY, customer_name VARCHAR(255), city VARCHAR(100) ); CREATE TABLE sales_reps ( rep_id SERIAL PRIMARY KEY, rep_name VARCHAR(255) ); CREATE TABLE invoices ( invoice_id SERIAL PRIMARY KEY, customer_id INT, rep_id INT, invoice_date DATE, invoice_amount NUMERIC(12,2) ); CREATE TABLE payments ( payment_id SERIAL PRIMARY KEY, invoice_id INT, payment_date DATE, amount_paid NUMERIC(12,2) ); CREATE TABLE tax_payroll( id SERIAL PRIMARY KEY, full_name VARCHAR(255), dept VARCHAR(255), gross_pay NUMERIC(12,2), taxable_pay NUMERIC(12,2), shif NUMERIC(12,2), nssf NUMERIC(12,2), ahl NUMERIC(12,2), paye NUMERIC(12,2), net_pay NUMERIC(12,2) ); --
├── 02_Insert_Data.sql
├── 03_Views.sql
├── 04_Basic_Queries.sql
├── 05_GroupBy_Having.sql
├── 06_Joins.sql
├── 07_Subqueries.sql
├── 08_Window_Functions.sql
├── 09_Advanced_Filters.sql
├── 10_Analytics.sql
└── README.md
