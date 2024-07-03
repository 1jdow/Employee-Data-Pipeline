This repository contains code and configuration files for an Extract, Transform, Load (ETL) project using Google Cloud Data Fusion for data extraction, Apache Airflow/Composer for orchestration, and Google BigQuery for data loading.


# Overview
The project aims to perform the following tasks:

1. Data Extraction: Extract data using python.
2. Data Masking: Apply data masking & encoding techniques to sensitive information in Cloud Data Fusion before loading it into BigQuery.
3. Data Loading: Load transformed data into Google BigQuery tables.
4. Orchestration: Automate complete Data pipeline using Airflow ( Cloud Composer )

# To run this project
Create a Composer environment a data fusin instance and a bucket in storage

# Architecture:
![image](https://github.com/1jdow/Employee-Data-Pipeline/assets/82601410/acc02bb1-e24b-4af7-84a8-fabc896ffb62)
