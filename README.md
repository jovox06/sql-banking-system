# SQL Banking System

From database modeling to strategic business analytics.

A complete SQL Server project that moves a bank from fragmented data and slow reporting to a centralized, reliable database with automated analysis.

📄 **Presentation:** [BankingSystem.pdf](presentation/BankingSystem.pdf)

---

## Problem

- Data was scattered and disconnected
- Reports took days to prepare
- No transparency in decision-making

## Goal

Build one centralized database on **SQL Server** that is accurate, adapts to business needs, and solves data management problems at the root.

---

## Database Architecture

A centralized architecture with **30+ tables** covering all operations:

| Domain | Description |
|---|---|
| Customers | Profiles of all customers |
| Accounts | Active and frozen accounts |
| Transactions | Incoming and outgoing transfer history |
| Loans | Dynamic loan portfolio |
| Branches | Geographic branch network |

**Relational design:** Primary Keys uniquely identify each record, and Foreign Keys enforce logical and physical links between tables. This guarantees data integrity and blocks orphan records.

---

## Data Quality

Cleaning of **10,000+ records**:

| Before | Process | After |
|---|---|---|
| NULL values, wrong dates and formats, duplicates, broken IDs | Validation, duplicate removal, format standardization, ID consistency checks | Clean, reliable database ready for analytics |

---

## Analytics

- **JOIN**: combines scattered tables into one view of each customer (360° view)
- **CTE (Common Table Expressions)**: simplifies complex multi-step calculations with virtual tables
- **Aggregate functions**: `SUM`, `COUNT`, `AVG`, `MAX`, `MIN` with grouping to turn millions of rows into clear insights
- **Fraud analysis**: detects transactions of **$10,000+** in a short time window for risk monitoring
- **VIP segmentation**: Top-3 customers by balance using sorting and ranking functions

---

## Results

| Before | After |
|---|---|
| No transparency | Data integrity and accuracy reached 100% |
| Reports delayed by days | Fast, automated decisions |
| Fragmented architecture | Timely risk detection and real-time monitoring |

---

## Project Structure

```
sql-banking-system/
├── README.md
├── sql/
│   ├── [01_create_tables.sql]
│   ├── [02_insert_data.sql]
│   ├── [03_data_cleaning.sql]
│   └── [04_analysis_queries.sql]
└── presentation/
    └── BankingSystem_EN.pdf
```

## How to Run

1. Install SQL Server and SQL Server Management Studio (SSMS)
2. Run the scripts in the `sql/` folder in numeric order
3. Execute the analysis queries

## Next Steps

1. **Power BI integration**: real-time dashboards for business owners
2. **Artificial Intelligence**: credit scoring and risk prediction
3. **Big Data scaling**: indexing to process millions of transactions in seconds

## Tech Stack

SQL Server · T-SQL · SSMS

## Author

**Javohir Yunusov**
[LinkedIn]([your link]) · [Telegram]([your link])
