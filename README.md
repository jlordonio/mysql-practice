# MySQL Practice Database Schema

This repository contains SQL scripts for foundational data structuring, table creation, and schema design developed during my MySQL learning roadmap.

## 📌 Repository Contents

- `mydb_practice_schema.sql`: Full DDL script defining table structures, data types, primary keys, auto-increments, and relational constraints.

## 🗄️ Database Overview (`mydb`)

The schema includes the following practice tables:

- **`customers`**: Customer profile management (`customer_id`, names, referral links).
- **`employees`**: Workforce tracking (`employee_id`, hourly pay rates, job roles, hire dates).
- **`transactions`**: Sales log with `FOREIGN KEY` references connecting back to `customers`.
- **`products`**: Inventory catalog enforcing `UNIQUE` constraints on product naming.
- **`expenses` & `income`**: Basic financial logging tables.
- **`test`**: Temporal data types demonstration (`DATE`, `TIME`, `DATETIME`).

## 🛠️ Tools Used
- **Database Engine**: MySQL 8.0 Community Server
- **GUI Tool**: MySQL Workbench
- **Version Control**: Git & GitHub
