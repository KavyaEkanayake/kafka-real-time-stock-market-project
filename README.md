# Stock Market Real-Time Data Engineering Pipeline with Kafka and AWS

## Introduction 
This project is an end-to-end real-time data engineering pipeline that captures and processes live stock market data using Apache Kafka, AWS services, and Python. It is inspired by an open-source implementation and extended with customized workflows to ensure scalability, data cataloging, and query-ability in a cloud-native environment.

## Architecture 
<img src="Architecture.jpg">

## Key Features
🔄 Real-time ingestion of stock market data <br>
☁️ Cloud-native storage using Amazon S3  <br>
🧠 Automated schema inference and metadata cataloging with AWS Glue <br>
🔍 Ad-hoc querying via Amazon Athena (using SQL) <br>
💡 Modular and easily scalable architecture <br>

## Technology Used
- **Programming Language**: Python  
- **Data Streaming**: Apache Kafka  
- **Cloud Platform**: Amazon Web Services (AWS)  
  - **S3**: Storage for raw stock market data  
  - **EC2**: Kafka deployment (likely broker or consumer/producer nodes)  
  - **Glue Crawler**: Automatically infers schema from S3 data  
  - **Glue Catalog**: Central metadata store for Athena  
  - **Athena**: SQL-based querying of data stored in S3  


## Dataset Used
https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv

