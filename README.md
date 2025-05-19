# Data Engineering YouTube Analysis Project

## Overview

This project focuses on the secure management, efficient processing, and insightful analysis of structured and semi-structured YouTube video data, categorized by video genres and trending metrics.

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier

## Services Used
1. Amazon S3: A highly scalable object storage service that ensures high availability, durability, and security for storing structured and semi-structured data.
2. AWS IAM (Identity and Access Management): Enables secure access control and management of permissions for AWS services and resources.
3. Amazon QuickSight: A cloud-native, serverless business intelligence (BI) service that provides interactive dashboards and ML-powered insights.
4. AWS Glue: A serverless data integration service used for discovering, preparing, and combining data for analytics, ML, and application development.
5. AWS Lambda: A serverless compute service that runs backend code in response to events without provisioning or managing servers.
6. Amazon Athena: An interactive query service that allows SQL-based analysis directly on data stored in Amazon S3, with no need for data loading or transformation.

## Dataset Used
This Kaggle dataset comprises daily statistics on popular YouTube videos collected over several months. For multiple regions, up to 200 trending videos are recorded each day, with data for each region stored in separate files. The dataset includes details such as video title, channel name, publication time, tags, views, likes, dislikes, description, and comment count. Additionally, a category_id field—unique to each region—is provided in associated JSON files to map videos to their respective categories.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
![architecture](https://github.com/user-attachments/assets/e208b2af-3736-474b-bc98-fb84c84facbf)
