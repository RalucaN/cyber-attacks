# Cyber Attacks Analysis

This project leverages the [**University of Maryland CISSM Cyber Attacks Database**](https://cissm.liquifiedapps.com/) to create an end-to-end data engineering pipeline to ingest, process, store, and visualize data on cybers attacks around the world between 2014 and 2023. It uses various cloud, IaC, workflow orchestration, data warehouse, and visualization tools to build a dashboard that shows the trends and patterns of cyber events breaches across different sectors and regions.

CISSM dataset compiles open-source information related to a wide range of publicly acknowledged cyber events affecting both private and public organizations. This database covers events from 2014 to the present and provides standardized information on various aspects of each attack, including:

- *Threat Actors*: Identifying the entities responsible for the attacks.
- *Threat Actor Countries*: Understanding the geographical origins of these actors.
- *Motives*: Investigating the reasons behind the attacks.
- *Targets*: Identifying the specific organizations or systems affected.
- *Industries*: Categorizing attacks based on the affected sectors.
- *Location*: Analyzing the global reach of these incidents.

Please check the [Cyber Events Database Codebook](https://cissm.umd.edu/sites/default/files/2023-03/Cyber%20Events%20Database%20Codebook.pdf) for more information about the data collection, validation and coding process.


## Why this project?
Cybers attacks pose significant risks to individuals, organizations, and society at large. By analyzing attack data comprehensively, we can enhance our understanding of these threats and develop effective strategies to prevent, detect, and respond to cyber incidents. The insights gained from this project will contribute to a safer digital environment.

The project aims to answer the following research question: *What are the common attack vectors used by threat actors in different industries, and how do these vectors evolve over time and space?*

To address this research question, we will follow these steps:
- **Data Ingestion and Standardization**: Develop an end-to-end data pipeline to ingest, process, and standardize the information from the CISSM Cyber Attacks Database.
- **Exploratory Data Analysis (EDA)**: Conduct thorough exploratory analysis to uncover patterns, trends, and anomalies within the attack data
   - Temporal Trends: Investigate how the frequency and severity of attacks have evolved over time.
   - Geospatial Analysis: Map attack incidents to understand their global distribution.
   - Sector-Specific Insights: Analyze attack impact across different industries.
- Visualization and Dashboard Creation: Utilize data visualization tools to create an interactive dashboard that allows users to explore attack-related insights

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

``` mermaid
gantt
        dateFormat YYYY-MM-DD
        title Cyber Attacks Analysis Project Timeline
        section Data Collection & EDA
                Planning :2024-02-15, 3d
                Choose a data source :active, 2024-02-18, 1d
                Download or access the data source :active, 2024-02-18, 1d
                Inspect the data quality, size, and format :active, 2024-02-19, 1d
                Perform data cleaning and preprocessing :active, 2024-02-19, 1d
        section Cloud and IaC setup
                Choose a cloud platform and an IaC tool :after, 2024-02-20, 3d
                Create and configure the cloud resources :after, 2024-02-23, 3d
        section Data lake pipeline
                Design and implement the data lake pipeline :after, 2024-02-26, 6d
                Test and debug the data lake pipeline :after, 2024-03-03, 1d
        section Data warehouse pipeline
                Design and implement the data warehouse pipeline :after, 2024-03-04, 7d
                Test and debug the data warehouse pipeline :after, 2024-03-11, 1d
        section Data transformation
                Design and implement the data transformation :after, 2024-03-12, 7d
                Test and debug the data transformation :after, 2024-03-19, 1d
        section Dashboard creation
                Design and implement the dashboard :after, 2024-03-20, 7d
                Test and debug the dashboard :after, 2024-03-27, 1d
        section Documentation and review
                Write the readme and other documentation :after, 2024-03-28, 2d
                Final review and submission :after, 2024-03-29, 2d

```
## Citations/Links
CISSM dataset: Harry, C., & Gallagher, N. (2018). Classifying cyber events. Journal of Information Warfare, 17(3), 17-31.
