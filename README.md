# Youtube-analysis-using-AWS-

# Data Engineering YouTube Analysis Project

## Project Overview
This project aims to securely manage, streamline, and perform analysis on structured and semi-structured YouTube video data based on video categories and trending metrics.

## Project Goals
1. **Data Ingestion:** Build a mechanism to ingest data from different sources.
2. **ETL System:** Transform raw data into the proper format.
3. **Data Lake:** Create a centralized repository to store data from multiple sources.
4. **Scalability:** Ensure the system scales as the data size increases.
5. **Cloud:** Utilize AWS for processing vast amounts of data.
6. **Reporting:** Build a dashboard to answer analytical questions.

## Services Used
- **Amazon S3:** Object storage service for scalability, data availability, security, and performance.
- **AWS IAM:** Identity and access management for secure AWS resource access.
- **Amazon QuickSight:** Scalable, serverless, machine learning-powered business intelligence (BI) service.
- **AWS Glue:** Serverless data integration service for data discovery, preparation, and combining.
- **AWS Lambda:** Computing service for running code without managing servers.
- **AWS Athena:** Interactive query service for S3 data without loading data.

## Dataset Used
The dataset used in this project is sourced from Kaggle and contains statistics (CSV files) on daily popular YouTube videos over several months. It includes up to 200 trending videos published daily for various locations. Data points include video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count. A category_id field, varying by region, is also included in the JSON file linked to each region.

## Usage
1. **Data Ingestion:** Describe how to ingest data from different sources.
2. **ETL System:** Explain how to transform raw data into the proper format.
3. **Data Lake:** Detail the creation and management of the centralized data repository.
4. **Scalability:** Discuss how the system scales with increasing data size.
5. **Cloud Setup:** Provide instructions for setting up AWS services.
6. **Reporting Dashboard:** Describe how to access and use the reporting dashboard.

## Project Structure
- `/data`: Directory for storing data.
- `/scripts`: Scripts for data ingestion, ETL, and analysis.
- `/dashboard`: Dashboard-related files and code.
- `/docs`: Documentation files.
- `/examples`: Example code or notebooks for analysis.
- `/config`: Configuration files for AWS services.


