# Youtube-Analysis-Data-Pipeline-on-AWS-Cloud
This project focuses on securely managing, streamlining, and analyzing structured and semi-structured YouTube video data, with an emphasis on video categories and trending metrics

# Project Objectives
Data Ingestion: Develop a robust mechanism to ingest data from multiple sources.
ETL Pipeline: Transform raw data into a structured format suitable for analysis.
Data Lake: Establish a centralized repository to store data from various sources.
Scalability: Ensure the architecture can scale efficiently as data volume grows.
Cloud Integration: Leverage AWS cloud services to process and manage large-scale data that cannot be handled locally.
Reporting: Build an interactive dashboard to provide insights into video trends and categories.

# AWS Services Used
Amazon S3: Scalable object storage for storing raw and processed datasets with high availability and durability.
AWS IAM: Identity and Access Management to securely control access to AWS resources.
Amazon QuickSight: A serverless, scalable BI tool used to create interactive visualizations and dashboards.
AWS Glue: A serverless ETL service to clean, transform, and catalog data for analysis and machine learning.
AWS Lambda: A serverless compute service for running backend logic without managing infrastructure.
AWS Athena: An interactive query service that enables data analysis directly in S3 using standard SQL.

# Dataset
The dataset, sourced from Kaggle, includes daily statistics on trending YouTube videos from various regions. It contains up to 200 trending videos per day per country and includes details such as video title, channel title, publish time, tags, views, likes, dislikes, comments count, description, and category ID. Region-specific metadata is stored in accompanying JSON files.
https://www.kaggle.com/datasets/datasnaek/youtube-new
# Project Architechture
<img width="910" alt="Screenshot 2025-04-15 at 10 36 17 PM" src="https://github.com/user-attachments/assets/5af98d3d-ca95-4136-9b24-20b2a87231e0" />
