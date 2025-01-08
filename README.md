# Complaint-Analytics

## 1. Overview
In this project, I designed and implemented an end-to-end data pipeline for analyzing consumer complaints data stored in an Amazon S3 bucket.

- Skills Demonstrated: Data engineering with Databricks, Delta Live Tables, PySpark, SparkSQL, Amazon S3, Power BI for visualization and reporting.

## 2. Business Questions
- Do consumer complaints show any seasonal patterns?
- Which products present the most complaints? What are its most common issues?
- How are complaints typically resolved?
- Can you learn anything from the complaints with untimely responses?

## 3. Solution Architecture
![complaint-analytics](https://github.com/user-attachments/assets/16268856-6345-40eb-b501-0eef57a77c4d)

## 4. Data Engineering
I developed a pipeline in Databricks using Delta Live Tables for efficient data processing. In the pipeline, I created a staging table for data validation and cleansing, followed by materialized views for fact and dimension tables using PySpark and SparkSQL.

- #### Data Pipeline
<img width="949" alt="image" src="https://github.com/user-attachments/assets/986d3671-6ace-4b0b-9376-df4092106ed7" />

[Spark notebook for ingesting data from Amazon S3 into Databricks volume (file storage)](https://github.com/johnuzoma/Complaint-Analytics/blob/main/cc-data_setup.ipynb)

[Spark notebook attached to the DLT pipeline.](https://github.com/johnuzoma/Complaint-Analytics/blob/main/cc-pipeline.ipynb)

## 5. Data Analysis & Reporting
I connected Databricks to Power BI (using a personal access key generated in Databricks) to create a report addressing key questions, including seasonal trends, product-based complaint distribution, resolution methods, and insights from untimely responses.

- #### Power BI Report
<img width="712" alt="image" src="https://github.com/user-attachments/assets/2a8a4044-662b-45bf-82ae-ef0740a55f00" />

