Azure Data Engineering Pipeline
📌 Project Overview

This project demonstrates an end-to-end data engineering pipeline built on Azure Data Lake Storage Gen2 (ADLS) using Azure Data Factory (ADF), PySpark, and Power BI.

The pipeline ingests raw data from CSV files and the GitHub API, applies transformations using the Medallion Architecture (Bronze → Silver → Gold layers), and visualizes key insights in Power BI.

The solution is designed with performance in mind, featuring incremental loading and watermarking techniques to reduce data latency and optimize pipeline efficiency.

🏗 Architecture

Data Ingestion (Bronze Layer)

Extracted data from CSV files and GitHub API.

Loaded data into Azure Data Lake Gen2 using Azure Data Factory.

Data Transformation (Silver Layer)

Applied data cleaning, filtering, and schema normalization with PySpark.

Implemented incremental loading with watermarking for efficiency.

Data Enrichment & Aggregation (Gold Layer)

Curated analytical datasets for reporting.

Designed star-schema-like structures for ease of visualization.

Visualization

Built interactive dashboards in Power BI to deliver actionable insights.

🚀 Key Features

✅ Automated ingestion from multiple sources (CSV, API)

✅ Incremental data loading with watermarking

✅ Data processing with Medallion Architecture (Bronze, Silver, Gold)

✅ Data transformation & enrichment using PySpark

✅ Insightful Power BI dashboards

✅ Reduced data latency by 25%

🛠️ Technologies Used

Azure Data Factory – Orchestration & Ingestion

Azure Data Lake Storage Gen2 – Data Storage

PySpark – Data Processing & Transformations

Power BI – Visualization & Analytics

📊 Outcomes

Reduced data latency by 25%.

Optimized pipeline performance through incremental loads.

Delivered a scalable data analytics solution using Azure services.
