# Azure PySpark & SQL Coding Challenges

[![License: MIT](https://shields.io)](https://opensource.org)

A centralized repository featuring solutions to LeetCode and advanced SQL problems implemented using **PySpark (DataFrame API)** and **Spark SQL** within **Azure Databricks**. 

This repository serves as a technical portfolio demonstrating senior-level data engineering competencies in distributed computing, query optimization, and programmatic data transformations.

## 🛠️ Tech Stack & Environment
* **Platform:** Azure Databricks (Single-Node / Multi-Node Clusters)
* **Language:** Python (PySpark API)
* **Engine:** Apache Spark 3.x
* **Storage:** Delta Lake formats (where applicable for optimization)

## 📁 Repository Structure
The problems are organized by platform, topic, and difficulty to ensure clean code maintenance:

```text
├── LICENSE
├── README.md
└── solutions/
    ├── easy/
    │   └── 175_combine_two_tables/
    │       ├── solution.ipynb
    │       └── README.md
    ├── medium/
    │   └── 180_consecutive_numbers/
    │       ├── solution.ipynb
    │       └── README.md
    └── hard/
```

## 🚀 Key Learning Objectives & Optimization Focus
While solving these standard SQL problems, the implementation focuses heavily on Spark-specific execution patterns:
* **API Parity:** Implementing solutions using both fluent PySpark DataFrame transformations and raw Spark SQL queries.
* **Performance Tuning:** Avoiding costly operations like `collect()`, minimizing data shuffling, and utilizing appropriate partitioning strategies.
* **Window Functions:** Leveraging `pyspark.sql.Window` for complex analytical aggregations (ranking, lead/lag, cumulative metrics).

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
