# Stock Market Kafka Real-Time Data Engineering Project

## Introduction

I developed an end-to-end real-time data engineering solution for ingesting, processing, and analyzing live stock market data using Apache Kafka. The objective was to build a system that could efficiently handle and process streaming data. I employed technologies such as Python and Amazon Web Services (AWS) to create a robust, scalable data pipeline.

## Architecture

![Architecture Diagram](https://github.com/RamdasCoundinya0716/realtimedataanalysis/blob/main/Architecture.jpg)

## Technology Used
- **Programming Language**: Python
- **Amazon Web Services (AWS)**:
    1. **S3**: I stored processed stock market data in Amazon S3, ensuring secure and scalable storage solutions.
    2. **Athena**: I utilized Athena to query and analyze the data stored in S3 without requiring additional transformations.
    3. **Glue Crawler**: I implemented AWS Glue Crawler to automatically extract metadata from stock data and populate the AWS Glue Data Catalog.
    4. **Glue Catalog**: I organized and managed dataset metadata in the Glue Catalog, making querying and data management straightforward.
    5. **EC2**: I ran Apache Kafka on EC2 instances to manage real-time data ingestion and ensure seamless data processing.

- **Apache Kafka**: I used Kafka to handle the real-time data streams, ensuring efficient ingestion and processing of live stock market information.
