# banking-system-backend

A robust backend application simulating the core operations of a commercial bank. The project focuses on data persistence, transaction consistency, and secure relational database interactions using an architecture that separates concerns cleanly.

## 🚀 Key Features
- **Full CRUD System:** Complete implementation of Create, Read, Update, and Delete actions for bank accounts and clients.
- **Financial Transaction Logic:** Handles complex operations such as algorithmic IBAN generation, safe deposits, balance verification, and cross-account transfers.
- **Database Security (Anti-SQL Injection):** Fully secured against cyber attacks via **Parameterized Queries** for every single database transaction.
- **Data Integrity & Consistency:** Ensures financial records and balances match precisely after complex multi-step transaction executions.
- **Modular Design (Clean Code):** Implements a clear separation between the business logic layer and the Data Access Layer (DAL).

## 🛠️ Tech Stack & Concepts
- **Language:** Python 3
- **Database:** SQL (SQLite / Interrogări parametrizate)
- **Concepts:** Relational Database Design, Parameterized Statements, Data Persistence.

## 📦 Project Structure
```text
core-banking-system/
│
├── database/              # SQL setup, connection pooling, and tables schema
├── services/              # Business logic (Transfers, Validation, IBAN engine)
└── main.py                # Console App Interface / System controller
