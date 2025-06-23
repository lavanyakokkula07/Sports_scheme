# 🏆 Sports Database Project

This repository contains the MySQL Workbench database design and SQL scripts for a **Sports Management System**. It includes the full ER model, SQL scripts to create tables and relationships, and example queries to manipulate and view data.

---

## 📂 Project Files

| File Name | Description |
|-----------|-------------|
| `SportsData.sql` | SQL script to create the entire schema (tables, keys, constraints) |
| `SportsER.mwb` | MySQL Workbench model file (editable ER diagram) |
| `database_queries.sql` | Sample SQL queries (e.g. SELECT, JOIN, INSERT) for testing |

---

## 🧱 Database Schema Overview

### Key Tables:
- **`player`** – Holds player information
- **`team`** – Team data including team ID and name
- **`match`** – Match schedule, scores, and related teams
- **`tournament`** – Tournament-level details

### Relationships:
- A **team** has many **players**
- A **match** is played between two **teams**
- A **player** can participate in multiple **matches**
- Matches are part of a **tournament**

---

## 🚀 How to Use

1. **Create the schema:**
   - Open `SportsData.sql` in MySQL Workbench
   - Run the script to create all tables and relationships

2. **Explore or test:**
   - Use `database_queries.sql` to run sample queries (e.g., SELECT, JOIN, etc.)

3. **View or edit diagram:**
   - Open `SportsER.mwb` in MySQL Workbench to visually modify the ER diagram



---

##Author
Kokkula Lavanya
---
