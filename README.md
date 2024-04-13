# Covid19_Analysis_Using_Azure_Data_Factory

## Overview

This project utilizes data from the European Centre for Disease Prevention and Control (ECDC) to track weekly cases, deaths, and hospital admissions related to COVID-19 in Europe leveraging Azure Data Engineering services.

## Solution Architecture

The architecture aims to integrate data from different sources utilizing Azure Data Factory for data ingestion, orchestration, and scheduling, Azure Storage solutions, SQL Database, HDInsight, Databricks, and Power BI for data processing and analysis, with monitoring and reporting enabled through Azure Monitor and Log Analytics.

![Solution Architecture](https://github.com/AliMagdy100/Covid19_Analysis_Using_Azure_Data_Factory/assets/87953057/fdca07db-68e1-4786-823a-d562ef64b172)

## Data Ingestion

Data is ingested from Azure Blob Storage and from HTTP connector into Azure Gen2 Data Lake storage account in its raw form, which represents the **bronze** layer of our architecture.

### 1-Population Data Ingestion
![Population Data Ingestion](https://github.com/AliMagdy100/Covid19_Analysis_Using_Azure_Data_Factory/assets/87953057/404a7656-64e0-4707-ae40-adffeb960447)

### 2-ECDC Data Ingestion
![ECDC Data Ingestion](https://github.com/AliMagdy100/Covid19_Analysis_Using_Azure_Data_Factory/assets/87953057/ad7adcd4-930a-479f-b775-764f81a48f65)

## Data Transformation

This stage include processing data using three different services:

### 1-Data Flow 

-Processing Case and death data

![3-Transform_case_and_death](https://github.com/AliMagdy100/Covid19_Analysis_Using_Azure_Data_Factory/assets/87953057/d3c457cb-4591-4e72-9c69-962aa0c66839)

-Processing hosbital admission

![4-Transform_hosbital_admission](https://github.com/AliMagdy100/Covid19_Analysis_Using_Azure_Data_Factory/assets/87953057/f80dd0cc-d4b0-4859-b537-d8889b3413ea)



