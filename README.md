# Covid19_Analysis_Using_Azure_Data_Factory

## Overview

This project utilizes data from the European Centre for Disease Prevention and Control (ECDC) to track weekly cases, deaths, and hospital admissions related to COVID-19 in Europe leveraging Azure Data Engineering services.

## Solution Architecture

The architecture aims to integrate data from differnt sources utilizing Azure Data Factory for data ingestion, orchestration, and scheduling, Azure Storage solutions, SQL Database, HDInsight,Databricks and Power BI for data processing and analysis, with monitoring and reporting enabled through Azure Monitor and Log Analytics.

![Arch](https://github.com/AliMagdy100/Covid19_Analysis_Using_Azure_Data_Factory/assets/87953057/fdca07db-68e1-4786-823a-d562ef64b172)


## Data Ingestion
Data is ingested from azure blob storage and from http connector into Azure Gen2 Data Lake storage account in its raw form which represent the silver layer of our architechture.

1. *Population Data Ingestion** 
![Population Data Ingestion](https://github.com/AliMagdy100/Covid19_Analysis_Using_Azure_Data_Factory/assets/87953057/404a7656-64e0-4707-ae40-adffeb960447)

2. *ECDC Data Ingestion** 
![ECDC Data Ingestion](https://github.com/AliMagdy100/Covid19_Analysis_Using_Azure_Data_Factory/assets/87953057/ad7adcd4-930a-479f-b775-764f81a48f65)

## Data Processing
