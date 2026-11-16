# Reza's Data Portfolio

A collection of my data projects: SQL, Python, Data Engineering, and Dashboards.

## Featured project

**[Online Bookstore ELT Pipeline and Dashboard](https://github.com/zareee12/toko-buku-pipeline)**: a daily automated pipeline from a WooCommerce store to PostgreSQL, dbt, and Looker Studio, scheduled with GitHub Actions. Built from real company data and published with anonymized data. [Live dashboard](https://datastudio.google.com/reporting/e6e2ebf3-f9ec-44c9-854e-194defd2f27d)

## Data Engineering

| Project | Associated | Tools | Description |
|---|---|---|---|
| [Online Bookstore ELT Pipeline and Dashboard](https://github.com/zareee12/toko-buku-pipeline) | Personal project | Python, PostgreSQL (Supabase), dbt, GitHub Actions, Looker Studio | End-to-end pipeline that pulls products, variations, and orders from the WooCommerce REST API (read-only), loads them into PostgreSQL, models them with dbt (staging, marts, data tests), and serves a 5-page Looker Studio dashboard. Runs daily on GitHub Actions with retry on API timeouts. Handles real data-quality issues such as display stock vs. real stock, pre-order detection, and deleted products in order history. The public version uses anonymized data in a separate schema with a read-only role. [Live dashboard](https://datastudio.google.com/reporting/e6e2ebf3-f9ec-44c9-854e-194defd2f27d) |
| [ETL Pipeline to Data Warehouse with Apache Airflow](https://github.com/zareee12/ETL-Pipeline-to-Data-Warehouse-with-Apache-Airflow) | DNA Studio | Python, PostgreSQL, Airflow | Modular ETL pipeline using Apache Airflow and PostgreSQL that automates loading raw CSV files into a structured data warehouse. It simulates a real-world scenario where transactional data is ingested, staged, transformed, and modeled for analytical querying using a star schema. |
| [⚠️ DBT Sales Reporting](https://github.com/zareee12/dbt-sales-reporting) | Project | SQL, dbt, Apache Superset (Preset.io) | Complete end-to-end sales data reporting pipeline, with dbt (Data Build Tool) for data modeling and Apache Superset for business intelligence and dashboarding. |
| [⚠️ Fraud Detection Analyst](https://github.com/zareee12/fraud-detection_analyst) | IYKRA | Python, GCP (Cloud Storage, BigQuery), Spark, Kafka, Looker Studio | End-to-end data pipeline that lets analysts choose between batched and real-time streamed data, plus an analytics dashboard built on the analytics database to generate insights for the organization. |
| [⚠️ Credit Card Application Dashboard](https://github.com/zareee12/Credit-Card-Application-Dashboard) | dibimbing | Python, Docker, Airflow, Looker Studio | Data engineering project that analyzes credit card applications with an ETL process orchestrated by Airflow. It aims to help organizations make the approval process more efficient through data processing and workflow automation. |

## SQL

| Project | Associated | Tools | Description |
|---|---|---|---|
| [Outbound Roaming Data Analysis and Processing](https://github.com/zareee12/Outbound-Roaming-Data-Analysis-and-Processing) | Bootcamp | SQL | Analyzes and processes roaming data from telecommunication operators to gain insights into the performance of operators and countries in providing roaming services. Metrics include number of active users, data traffic, session success rate, and latency. |
| [DVD Rental Analysis](https://github.com/zareee12/sql-rental-dvd/tree/main) | DNA Studio | SQL | Analisis data perusahaan rental DVD film di seluruh dunia. Untuk meningkatkan kualitas layanan dan memahami perilaku pelanggan, dibangun sistem basis data yang merekam proses bisnis: penyimpanan film, peminjaman, pembayaran, hingga laporan pelanggan terbaik. |

## Python

| Project | Associated | Tools | Description |
|---|---|---|---|
| [Mini Library Management System](https://github.com/zareee12/Mini-Library-Management-System/tree/main) | Pacmann | Python | Simple Python-based program to manage a collection of books in a library. |

## Dashboard

| Project | Associated | Tools | Description |
|---|---|---|---|
| [Online Bookstore Sales and Stock Dashboard](https://datastudio.google.com/reporting/e6e2ebf3-f9ec-44c9-854e-194defd2f27d) | Personal project | Looker Studio, PostgreSQL | Five-page dashboard (Summary, Stock, Sales, Pre-order, Data Quality) on top of the pipeline above, using anonymized data. |
| [Retail Sales Dashboard](https://docs.google.com/spreadsheets/d/1Prl-u4KZoZlAlFEZllfnYEuyrZOb0CxGZv2Hf9b35LI/edit?hl=id&gid=1053070746#gid=1053070746) | Challenge Edspert | Excel | Overview of product sales performance in the retail sector over one year (January to December), for retail managers or marketing teams to monitor sales trends across products using horizontal and vertical bar charts and line charts. |
