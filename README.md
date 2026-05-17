# SQL Data Warehouse Project

Modern SQL Data Warehouse project built using Medallion Architecture (Bronze, Silver, Gold) with ETL pipelines, data modeling, and analytics reporting.

---

## 📌 Project Overview

This project demonstrates the end-to-end process of building a modern data warehouse using SQL Server.

### Key Features
- Importing ERP and CRM datasets from CSV files
- Building ETL pipelines
- Data cleaning and transformation
- Creating fact and dimension tables
- Star schema data modeling
- SQL analytics and reporting

---

## 🏗️ Data Architecture

The project follows the Medallion Architecture approach:

### 🥉 Bronze Layer
Stores raw data directly from source systems.

### 🥈 Silver Layer
Cleans and transforms data for analysis.

### 🥇 Gold Layer
Provides business-ready analytical data models.

![Data Architecture](docs/data_architecture.png)

---

## ⚙️ Technologies Used

- SQL
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- Draw.io
- Git & GitHub

---

## 🚀 Project Requirements

### Data Engineering
- Load ERP and CRM datasets
- Build ETL pipelines
- Transform and clean raw data
- Create analytical data models

### Analytics & Reporting
Generate insights for:
- Customer behavior
- Product performance
- Sales trends

---

## 📂 Repository Structure

```text
sql-data-warehouse-project/
│
├── datasets/          # Raw datasets
├── docs/              # Documentation and diagrams
├── scripts/
│   ├── bronze/        # Raw data scripts
│   ├── silver/        # Transformation scripts
│   └── gold/          # Analytics scripts
├── tests/             # Testing and quality checks
├── README.md
└── requirements.txt



📖 Documentation

The project includes:

Data Architecture
ETL Workflow
Data Flow Diagrams
Star Schema Models
Naming Conventions
Data Catalog
🛠️ Tools
SQL Server Express
SQL Server Management Studio (SSMS)
Draw.io
GitHub
🛡️ License

This project is licensed under the MIT License.
