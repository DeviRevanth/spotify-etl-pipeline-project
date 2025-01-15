# 🎧 Spotify ETL Pipeline with AWS Services 🚀

*Welcome to the **Spotify ETL Pipeline** project! This repository demonstrates how to build a scalable and efficient ETL (Extract, Transform, Load) pipeline for Spotify data using AWS services. The pipeline processes data sourced from a Kaggle dataset.*

---

### Key AWS Services:
- **IAM**: Securely manage access and permissions across AWS services.
- **AWS Glue Job**: Handle the transformation of raw Spotify data into structured formats.
- **AWS Glue Catalog**: Centralized metadata store to enable seamless querying.
- **Amazon S3**: Store raw, processed, and transformed data reliably and efficiently.
- **Amazon Athena**: Perform SQL queries directly on the data stored in S3 without the need for additional infrastructure.
- **Amazon QuickSight**: Create interactive dashboards and visualizations for deep insights.

---

## 🔑 Features

- **Kaggle Dataset Integration**: The pipeline uses Spotify data downloaded from Kaggle, providing comprehensive insights into tracks, artists, and albums.
- **ETL Pipeline**: Efficiently processes data using AWS Glue for extraction, transformation, and loading.
- **Metadata Management**: Registers schemas in Glue Catalog for easy querying with Athena.
- **Serverless Querying**: Run SQL queries on the data using Amazon Athena, reducing infrastructure management.
- **Data Visualization**: Build powerful dashboards with Amazon QuickSight to explore trends, insights, and metrics.

---

## 📊 Architecture Overview

The pipeline follows these stages:
1. **Data Source**: Download the Spotify dataset from Kaggle and upload it to Amazon S3.
2. **Extract**: Load the raw dataset from S3 for processing.
3. **Transform**: AWS Glue processes the data, applying necessary transformations and schema definitions.
4. **Load**: Transformed data is saved back to S3 and registered in the Glue Catalog.
5. **Query & Visualize**: Use Athena for analysis and QuickSight for visualization.

---

## 🗂 Dataset Information

- **Source**: [Kaggle Spotify Dataset](https://www.kaggle.com)
- **Contents**: Data on tracks, artists and albums suitable for music analysis.

---
