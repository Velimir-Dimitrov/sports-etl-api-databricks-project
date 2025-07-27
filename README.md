# ⚙️ Data Engineering Project: From Raw Sport Data to Azure Synapse Analytics

## Overview

This project is an end-to-end data engineering pipeline using Python, Databricks, and Azure to ingest, process, and store sports event data retrieved via a public API (TheSportsDB). It demonstrates how to:
- Extract season-based sports event data (e.g., UFC events) using REST APIs
- Transform the raw JSON using PySpark in a Databricks notebook
- Load curated data into Azure Data Lake Storage (ADLS) and optionally into Synapse Analytics for downstream use

## Business Case

This pipeline reflects real-world scenarios in data engineering, including raw data ingestion, cleaning, structuring, and storage optimization. The final data can be used for reporting, analytics, or visualization in tools like Power BI. Potential use cases include:
- Sports trend analysis
- Athlete or league performance monitoring
- Fan engagement analytics for media or fitness platforms

## Architecture

<img width="750" height="381" alt="diagram" src="https://github.com/user-attachments/assets/ffb87b90-49a3-4b0f-808d-952bedf9589e" />


## Tools Used
- Python
- Azure Blob Storage
- Azure Databricks
- PySpark
- Azure Synapse Analytics

## Data Source
- [TheSportsDB API](https://www.thesportsdb.com/api.php)

## Process
1. **Extract** data from sports API using Python
2. **Load** raw data to Azure Blob Storage
3. **Transform** using PySpark in Databricks
4. **Load** to Synapse Analytics for querying

## Future Enhancements
- Add Power BI dashboard
