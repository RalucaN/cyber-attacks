# Cybersecurity Breaches Analysis
This is a data engineering project that creates an end-to-end data pipeline to ingest, process, store, and visualize data on cybersecurity breaches reported by different entities. The project uses various cloud, IaC, workflow orchestration, data warehouse, and visualization tools to build a dashboard that shows the trends and patterns of cybersecurity breaches across different sectors and regions.


## Why this project?
Cybersecurity is a crucial and challenging domain that affects many aspects of our society and economy. Cybersecurity breaches can have severe consequences for individuals, organizations, and governments, such as data loss, identity theft, financial damage, reputational harm, or even physical harm. Therefore, it is important to understand the nature, causes, and impacts of cybersecurity breaches, and to develop effective strategies and solutions to prevent, detect, and mitigate them.


This project aims to provide a comprehensive and interactive analysis of cybersecurity breaches data, using data engineering and data visualization techniques. The project will help users to explore and answer questions such as:

- How many cybersecurity breaches have occurred over time, and what are the main types and sources of breaches?
- Which industries and regions are most affected by cybersecurity breaches, and what are the average costs and impacts of breaches for each sector and area?
- How can we identify and classify anomalous or suspicious cybersecurity events, and what are the best practices to respond to them?
- How can we improve the security and resilience of our systems and networks, and what are the emerging trends and challenges in cybersecurity?


## How to install and use this project?
To install and use this project, you need to have the following prerequisites:

- A cloud platform account (such as AWS, GCP, or Azure) and an IaC tool (such as Terraform, Pulumi, or Cloud Formation) to deploy and configure the cloud resources for the project.
- A data source that contains information about cybersecurity breaches, such as the dataset from Kaggle, or any other reliable and relevant data source.
- A data lake service (such as S3, GCS, or Azure Blob Storage) to store the raw and processed data.
- A data warehouse service (such as BigQuery, Snowflake, or Redshift) to store the transformed and aggregated data.
- A data processing tool (such as Spark, Flink, AWS Batch, Kafka, Pulsar, Kinesis, etc.) to ingest, clean, and transform the data.
- A workflow orchestration tool (such as Airflow, Prefect, or Luigi) to schedule and monitor the data pipeline tasks.
- A data transformation tool (such as dbt, Spark, or SQL) to create the datasets for the dashboard.
- A visualization tool (such as Tableau, Power BI, or Looker) to create the dashboard.


## Project timeline
The project timeline is as follows:

```
gantt
        dateFormat YYYY-MM-DD
        title Project timeline
        section Data source selection and inspection
        Choose a data source :done, 2024-02-18, 1d
        Download or access the data source :done, 2024-02-19, 1d
        Inspect the data quality, size, and format :done, 2024-02-20, 1d
        Perform preliminary data cleaning and preprocessing :done, 2024-02-21, 1d
        section Cloud and IaC setup
        Choose a cloud platform and an IaC tool :done, 2024-02-24, 1d
        Create and configure the cloud resources :done, 2024-02-25, 1d
        section Data lake pipeline
        Design and implement the data lake pipeline :done, 2024-02-26, 2d
        Test and debug the data lake pipeline :done, 2024-02-28, 1d
        section Data warehouse pipeline
        Design and implement the data warehouse pipeline :done, 2024-03-01, 2d
        Test and debug the data warehouse pipeline :done, 2024-03-03, 1d
        section Data transformation
        Design and implement the data transformation :done, 2024-03-04, 2d
        Test and debug the data transformation :done, 2024-03-06, 1d
        section Dashboard creation
        Design and implement the dashboard :done, 2024-03-08, 2d
        Test and debug the dashboard :done, 2024-03-10, 1d
        section Documentation and presentation
        Write the readme and other documentation :active, 2024-03-11, 2d
        Prepare and deliver the presentation : 2024-03-15, 2d

```