# DBMS Lab — Viva Q&A 🎓


## 🔗 Quick Access

* 🌐 **[Launch the Live Web Application](https://noel-1602.github.io/DBMS_LAB/)**
* 📖 **[Detailed Exam Notes (Notes.txt)](Notes.txt)**

---

## ✨ Features

* 🔍 **Instant Search** — Real-time search through both questions and detailed answers instantly as you type.
* 🏷️ **Topic Filtering** — Interactive chips to narrow down questions by specific topics (e.g., Joins, NoSQL, Schema Design).
* 🗂️ **Interactive Q&A Cards** — Sleek collapsible cards with rotating chevrons and high-contrast styling for clear readability.

---

## 📂 Lab Program Reference Index

Below is the directory of structured lab programs and exercises included in this repository:

| Program / Exercise | Topic & SQL Implementation | Direct Link |
| :--- | :--- | :---: |
| **Schema Design & DDL** | Create database/tables, set primary & foreign keys, constraints, modify schema. | [Q2.md](Q2.md) |
| **DML Operations** | Insert, update, select with conditions, and delete data. | [Q4.md](Q4.md) |
| **Aggregation & Grouping** | Practice with `SUM`, `AVG`, `COUNT`, `MIN`, `MAX`, `GROUP BY`, and `HAVING`. | [Q5.md](Q5.md) |
| **Joins & Subqueries** | Inner Joins, Outer Joins (Left, Right), nested/correlated subqueries, and Set Operators. | [Q6.md](Q6.md) |
| **TCL & DCL Commands** | Manage transaction logic (`COMMIT`, `ROLLBACK`, `SAVEPOINT`) and privileges (`GRANT`, `REVOKE`). | [Q7.md](Q7.md) |
| **Views & Assertions** | Create virtual tables (Views) and enforce complex constraints via Assertions. | [Q8.md](Q8.md) |
| **PL/SQL Blocks** | Implementation of Stored Procedures, Functions, and Database Triggers. | [Q9.md](Q9.md) |

---

## 📖 Theory Syllabus Reference

For a deeper dive into theoretical concepts, refer to the comprehensive [Notes.txt](Notes.txt) file:

### 🔹 Module 1: Introduction & ER Model
* **Core Concepts**: Introduction to DBMS, Data Abstraction & Mapping, Three-Schema Architecture, Data Independence (Physical & Logical).
* **Database Design**: Entity-Relationship (ER) diagrams, Entity Sets, Attributes (Derived, Composite, Multi-valued), Key Constraints (Candidate, Super, Surrogate), and Participation (Total vs Partial).

### 🔹 Module 2: Relational Model & SQL
* **Relational Concepts**: Relational Algebra operations (Selection, Projection, Joins, Set operations).
* **SQL Language**: Data Definition (DDL), Data Manipulation (DML), Data Control (DCL), and Transaction Control (TCL).
* **DB Objects**: Indexes, Views, Assertions, Triggers, and Stored Procedures vs Functions.

### 🔹 Module 3: Normalization & Transaction Processing
* **Database Design Theory**: Anomalies (Insert, Update, Delete), Functional Dependencies, and Normalization Forms (1NF, 2NF, 3NF, BCNF).
* **Transactions**: ACID properties, Transaction States, Concurrency issues (Dirty read, Lost update, Phantom read), Serializability (Conflict & View).
* **Concurrency & Recovery**: Two-Phase Locking Protocol (2PL), Deferred vs Immediate Updates, and Shadow Paging.

### 🔹 Module 4: NoSQL Databases
* **Modern Systems**: NoSQL features (horizontal scaling, schema-less), Key-Value/Document/Column-Family/Graph DB models.
* **Distributed Systems**: CAP Theorem (Consistency, Availability, Partition Tolerance) and BASE properties.
* **Technologies**: Apache Cassandra (Keyspaces, Partition Keys, Eventual Consistency, CQL) and MongoDB (BSON document structures, CRUD operations in Python/pymongo).


---

## 🚀 Running Locally

Since this is a lightweight serverless single-page application, no installation or build step is required!

1. Clone the repository:
   ```bash
   git clone https://github.com/noel-1602/DBMS_LAB.git
   ```
2. Simply open `index.html` in your web browser, or run a lightweight local server:
   ```bash
   npx serve .
   ```
