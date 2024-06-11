# Uber Trips ETL Pipeline - A Data Engineering Project using Transportation Data

## Project Overview
The goal of this project is to perform data analytics on uber trip data using various tools and technologies, including Python, PostgreSQL, Apache Airflow and Tableau.

## Data Architecture
This project involves the development of a robust ETL pipeline with a specific focus on uber trips sourced from the TLC Trip Record Data for Yellow Car trips. The scope encompasses:
- Data Extraction and Transformation:
    - Data extraction from the TLC Trip Records data page available here: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page 
    - Implementation of Python scripts to seamlessly fetch parquet files and transform trip data
- Data Cleaning and Standardization:
    - Creation of data cleaning routines to rectify inconsistencies and handle missing values.
    - Implementation of standardization formatting to enhance overall data quality.
- Database Loading and Optimization:
    - Design of an optimized loading process to efficiently insert transformed data into PostgreSQL database.
- Automation and Monitoring:
    - Development of an automated ETL pipeline scheduled at defined intervals.
    - Integration of logging and monitoring mechanisms to track pipeline performance and identify potential issues.

## Tech Stack
- Python: For scripting data extraction, cleaning, and transformation processes
- SQL: For database design, schema creation, and data transformation logic
- PostgreSQL: A relational database to store and manage data files during the ETL process

## Data Source
TLC Trip Record Data Yellow taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. Available in .parquet format

Here is the dataset used in this project - https://drive.google.com/file/d/1jvS9PH9St6qfagEYrmhiAQ9gp_WlupRu/view?usp=sharing

More info about dataset can be found here:

- Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
![image](https://github.com/bomodambo/uber-trips-etl-pipeline/assets/41348052/1462ce15-4d00-46b6-959f-06bb0dfd63e3)

