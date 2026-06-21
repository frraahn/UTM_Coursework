# 🗄️ Database Programming 

Welcome to the repository for my **Database Programming** course at Universiti Teknologi Malaysia (UTM)! This repository compiles a comprehensive set of relational (SQL) and non-relational (NoSQL) database artifacts, detailing schema implementation, advanced queries, indexing optimization, and document-oriented application models.

---

## 📂 Project & Assignment Breakdown

### 🔹 SQL & Relational Databases (MySQL)
* **Project I: Attendance Management System Backend** (`/DayangFarahFarzana_Group2_ProjectI.pdf`)
  * Engineered a complete relational database to track student and staff attendance histories. 
  * Applied DDL/DML scripts, integrated strict referential integrity constraints, and evaluated query optimization paths utilizing complex joins and correlated subqueries.
* **Assignment 1: Hostel Management Database Implementation** (`/Assignment1_DP.pdf` & `/Assignment1DP_A23CS0079_A23CS0176.sql`)
  * Formulated a backend configuration for room allocations, payments, and maintenance lifecycle management (`hostel_mgmt_sf`).
  * Structured table schemas with cascading rules (`ON DELETE RESTRICT`, `ON UPDATE CASCADE`) and engineered filtered aggregations using conditional `CASE` statements and `HAVING` filters.
* **Lab 1: Performance Tuning & B-Tree Indexes** (`/Lab Assignment 1 template.pdf`)
  * Conducted query profiling using `SET profiling = 1` and analytical scanning with `EXPLAIN`.
  * Quantified execution performance improvements by creating balanced B-Tree indexes to accelerate range searches and table sorts.

### 🔹 NoSQL & Document-Oriented Databases (MongoDB)
* **Project II: Delivery Records Tracking System** (`/SECP3623-02_ProjectII_Group2.pdf`)
  * Transitioned paradigm structures from relational schemas to a highly flexible, non-relational model mapping Customers, Orders, Drivers, and Deliveries collections.
  * Formulated data modeling methodologies comparing embedding vs. referencing and implemented complex data aggregation pipelines.
* **Lab 2: Clinic Appointment Operations** (`/Lab2_Clinic_A23CS0079 (1).pdf`)
  * Conducted document manipulation exercises focusing on `insertMany()` array payloads.
  * Executed conditional projections and sorting strategies filtering by appointment statuses and fee threshold bounds (`$gte`, `$lte`).

---

## 💡 Course Reflection & Key Takeaways

Advancing through this database programming framework drastically enhanced my technical maturity regarding data persistence layers. This course bridged the gap between basic data storage and true performance engineering:

1. **The Power of Optimization:** Learning to dissect execution footprints via `EXPLAIN` and profiling tools demonstrated that writing code that works is only half the battle. Implementing strategic B-Tree indexing highlighted how structural planning keeps systems scalable.
2. **Architectural Versatility:** Shifting from strict SQL ACID constraints to the loose, horizontal scalability of MongoDB documents reshaped how I evaluate application requirements. Mapping out when to embed documents for high-speed read lookups versus referencing them to preserve consistency was a key highlight.
3. **Real-World Problem Solving:** Constructing functional engines for the *Attendance System* and the *Delivery Tracker* mirrored genuine industrial data patterns, equipping me with the backend confidence required to design reliable, enterprise-grade storage architectures.
