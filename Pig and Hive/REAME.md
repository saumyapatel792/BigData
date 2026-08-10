
# Hadoop & Hive Sales Data Analysis

## 📌 Project Overview

This project demonstrates how to use **Apache Hadoop and Apache Hive** to store, query, aggregate, join, partition, and analyze sales transaction data.

The project covers:

- Hadoop HDFS setup
- Apache Hive 4.0.1
- Hive database and table creation
- Loading CSV data into Hive
- Basic SQL queries
- Aggregation queries
- `GROUP BY` and `HAVING`
- Join operations
- External tables
- Partitioning
- `EXPLAIN` query plans
- Hive table metadata
- Basic Hive optimization concepts

---

## 🛠️ Technologies Used

| Technology | Version |
|---|---|
| Ubuntu / WSL2 | Ubuntu 26.04 LTS |
| Hadoop | 3.3.6 |
| Apache Hive | 4.0.1 |
| Java | OpenJDK |
| HDFS | Hadoop Distributed File System |
| Beeline | Hive JDBC Client |
| Database | Apache Derby Metastore |

---

# 📂 Project Structure

```text
hive-sales-analysis/
│
├── README.md
├── sales_data.csv
├── customers.csv
├── sales_queries.sql
│
└── screenshots/
    ├── hadoop-running.png
    ├── hive-version.png
    ├── data-loaded.png
    ├── aggregation-query.png
    ├── join-query.png
    └── partition-query.png
