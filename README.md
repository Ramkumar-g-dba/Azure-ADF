# Azure Data Factory (ADF) Learning Repository

> **Tech Stack:** Azure Data Factory | Azure SQL Database | Azure Blob Storage | Azure Data Lake Storage Gen2 | GitHub

![Azure Data Factory](https://img.shields.io/badge/Azure-Data%20Factory-0078D4?style=flat&logo=microsoftazure)
![Azure](https://img.shields.io/badge/Azure-Cloud-0078D4?style=flat&logo=microsoftazure)
![Azure SQL](https://img.shields.io/badge/Azure-SQL-CC2927?style=flat)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-181717?style=flat&logo=github)

---

# Project Overview

This repository documents my **Azure Data Factory (ADF) learning journey** through hands-on exercises and mini projects. It includes practical implementations of ETL/ELT pipelines, Mapping Data Flows, pipeline orchestration, parameterization, control flow activities, and Azure data integration concepts.

The goal of this repository is to strengthen Azure Data Engineering skills by building real-world data movement and transformation workflows.

---

# Learning Objectives

- Understand Azure Data Factory architecture
- Build end-to-end ETL/ELT pipelines
- Create reusable and parameterized pipelines
- Learn Mapping Data Flows
- Implement control flow activities
- Integrate Azure SQL Database and Azure Storage
- Practice workflow orchestration
- Version control ADF using GitHub

---

# Repository Contents

## Pipelines

| No | Pipeline | Description |
|----|----------|-------------|
| 01 | Copy Data | Copy data between source and destination |
| 02 | Stored Procedure | Execute stored procedures |
| 03 | Stored Procedure with Parameter | Execute parameterized procedures |
| 04 | From CSV | Load CSV files into destination |
| 05 | Validation | Validate source data before processing |
| 06 | Send Email | Email notification pipeline |
| 07 | Execute Pipeline | Invoke child pipelines |
| 08 | Branching | Conditional execution |
| 09 | ForEach | Loop through multiple items |
| 10 | Script | Execute SQL scripts |
| 11 | Filter Data Flow | Filtering using Mapping Data Flow |
| 12 | Join Data Flow | Join datasets using Mapping Data Flow |
| Common | Common Data Flow | Shared reusable data flow |

---

## Mapping Data Flows

| Data Flow | Description |
|-----------|-------------|
| Filter | Filter rows |
| Join | Join multiple datasets |
| Select | Select required columns |
| Derived Column | Create calculated columns |
| Conditional Split | Split data based on conditions |
| Branching | Implement branching logic |
| Alter Row | Insert, Update, Delete, Upsert operations |

---

# Concepts Covered

## Pipeline Activities

- Copy Activity
- Stored Procedure Activity
- Script Activity
- Execute Pipeline Activity
- Validation Activity
- Email Notification
- Lookup Activity
- ForEach Activity
- If Condition
- Switch Activity
- Variables
- Parameters

---

## Mapping Data Flow Transformations

- Source
- Sink
- Filter
- Join
- Select
- Derived Column
- Conditional Split
- Alter Row
- Branching

---

## Azure Services Used

- Azure Data Factory
- Azure SQL Database
- Azure Blob Storage
- Azure Data Lake Storage Gen2
- GitHub Integration

---

# Folder Structure

```
Azure-ADF/
│
├── pipeline/
│   ├── Copy Data
│   ├── Stored Procedure
│   ├── Execute Pipeline
│   ├── ForEach
│   ├── Validation
│   └── Script
│
├── dataflow/
│   ├── Filter
│   ├── Join
│   ├── Select
│   ├── Derived Column
│   ├── Conditional Split
│   └── Alter Row
│
├── dataset/
├── linkedService/
├── integrationRuntime/
├── trigger/
└── README.md
```

---

# Skills Demonstrated

- Azure Data Factory
- ETL / ELT Pipelines
- Mapping Data Flows
- Azure SQL Database
- Azure Storage Integration
- Pipeline Orchestration
- Parameterization
- Control Flow Activities
- Git Version Control
- Azure Data Engineering Fundamentals

---

# Future Enhancements

- Dynamic Pipelines
- Metadata Driven ETL
- Incremental Loading
- Change Data Capture (CDC)
- REST API Integration
- Snowflake Integration
- Azure Synapse Analytics
- CI/CD using Azure DevOps
- Monitoring & Alerts

---

# Author

## Ramkumar G

**Aspiring Azure Data Engineer | Snowflake Developer**

- GitHub: https://github.com/Ramkumar-g-dba
- LinkedIn: https://linkedin.com/in/ramdba
- Portfolio: https://ramkumar-g-dba.github.io/ramkumar-portfolio

---

⭐ If you found this repository useful, feel free to star it!
