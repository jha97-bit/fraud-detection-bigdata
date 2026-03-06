# Fraud Detection using Spark + MLflow

## Project Overview
This project implements a scalable fraud detection pipeline using Apache Spark and MLflow on Databricks. The goal is to detect fraudulent financial transactions from the IEEE-CIS Fraud Detection dataset.

## Environment Setup
The project environment was configured in Databricks using a managed Spark workspace.  
Raw datasets were uploaded to Unity Catalog Volume storage.

Data location:
/Volumes/workspace/default/fraud_data

## Data Sources
Dataset: IEEE-CIS Fraud Detection (Kaggle)
Link: https://www.kaggle.com/competitions/ieee-fraud-detection/data

Files used:
- train_transaction.csv
- train_identity.csv


## Project Structure

```
fraud-detection-bigdata
│
├── notebooks       # Databricks notebooks for ingestion, EDA, modeling, MLflow
├── data-samples    # Small dataset samples
├── reports         # Final project report
├── slides          # Presentation slides
└── README.md
```

## Tools & Technologies
- Databricks
- Apache Spark (PySpark)
- MLflow
- Python
- GitHub
