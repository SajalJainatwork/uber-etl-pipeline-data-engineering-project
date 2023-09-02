# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction

The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

✅ How to understand raw data

✅ Building Data Model (Lucid Chart)

✅ Writing ETL Script (Python)

✅ Modern Data Pipeline Tool (mage)

✅ SQL queries for analysis

I created an ETL pipeline using the open-source data pipeline tool called Mage. The pipeline is designed to process the ETL job for data stored in a GCP Bucket. Then, I used Google Cloud Storage (GCS) to store the raw data, Compute Engine (VM/SSH Instance) to run Mage, and Big Query to store the transformed data for analysis. Finally, utilized Looker Studio to create an interactive dashboard for data visualization and insights.

## Architecture 
![uber architecture](https://github.com/SajalJainatwork/uber-etl-pipeline-data-engineering-project/assets/106689439/4e7af070-b278-4744-923c-d3ab7785e47e)

## Technology Used
✅Programming Language - Python

Google Cloud Platform

➡️Google Storage

➡️Compute Instance 

➡️BigQuery

➡️Looker Studio

Mage - Data Pipeline Tool
(Mage is an open-source data pipeline tool for transforming and integrating data.)

Modern Data Pipeine Tool - https://www.mage.ai/

Contibute to this open source project - https://github.com/mage-ai/mage-ai


## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used in the project - https://github.com/SajalJainatwork/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
![uber model](https://github.com/SajalJainatwork/uber-etl-pipeline-data-engineering-project/assets/106689439/2d855d8b-598a-4dd7-aac1-90e0a7da935e)
![uber orginal data model](https://github.com/SajalJainatwork/uber-etl-pipeline-data-engineering-project/assets/106689439/9785b1b5-5b79-4877-8337-9b1fc0b95fe9)

## ETL Pipeline - Mage
![ETL Pipeline - Mage](https://github.com/SajalJainatwork/uber-etl-pipeline-data-engineering-project/assets/106689439/dcbe9918-a0e7-44e4-b8e3-09affcb15029)


## Dashboard
![uber dashboard](https://github.com/SajalJainatwork/uber-etl-pipeline-data-engineering-project/assets/106689439/14f6485c-778f-4b06-b155-f217ed649f06)




