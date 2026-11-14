# Retail Intelligence Lakehouse

## Project Overview

Retail Intelligence Lakehouse is an end-to-end data engineering, business intelligence, and machine learning project developed using Databricks, PySpark, Delta Lake, SQL, Python, and Power BI.

The project transforms raw retail transaction data into structured, business-ready information using the Medallion Architecture.

## Objectives

- Build a scalable data processing pipeline.
- Implement Bronze, Silver, and Gold layers.
- Perform data cleaning and transformation using PySpark.
- Store processed data in Delta Lake.
- Perform business analysis using SQL.
- Develop customer segmentation using K-Means clustering.
- Build interactive Power BI dashboards.
- Generate actionable retail business insights.

## Technology Stack

- Databricks
- Apache Spark / PySpark
- Delta Lake
- Python
- SQL
- Pandas and NumPy
- Scikit-learn
- K-Means Clustering
- Power BI
- Git and GitHub

## Architecture

Raw CSV → Bronze → Silver → Gold → Machine Learning → Power BI

## Machine Learning

Customer segmentation is performed using RFM features:

- Recency
- Frequency
- Monetary

K-Means clustering identifies four customer groups based on purchasing behaviour and spending patterns.

## Business Intelligence

The Power BI dashboard includes:

1. Executive Sales Overview
2. Product and Regional Analysis
3. Customer Intelligence

## Business Outcomes

The system provides insights into sales trends, profitability, product performance, geographical performance, and customer purchasing patterns.

## Limitations and Future Enhancements

- Integrate live retail APIs.
- Implement incremental data ingestion.
- Automate pipelines using Lakeflow Jobs.
- Connect Power BI directly to Databricks SQL.
- Introduce demand forecasting.
- Implement customer churn prediction.
- Deploy the machine learning model as an API.

## Dataset

Sample Superstore retail transaction dataset.

## Disclaimer

This is an educational portfolio project using a sample retail dataset. The customer segments are analytical groupings and should not be interpreted as verified real-world customer behaviour.
