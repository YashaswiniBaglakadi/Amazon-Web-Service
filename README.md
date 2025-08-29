![banner](https://github.com/YashaswiniBaglakadi/Amazon-Web-Service/blob/086d8f1fb4133c7eadef2820589f805dc18510c9/Banner/Screenshot%202025-08-29%20210342.png)
# AWS Case Study: Querying Data from S3 to Athena Using AWS Glue Crawler

## Overview
This project demonstrates how to query data stored in Amazon S3 using Amazon Athena. AWS Glue Crawler is used to automatically discover and catalog the schema of your data, making it queryable in Athena without manual schema setup. Query results are stored in Amazon S3, enabling a serverless and cost-effective data analysis solution—all managed through the AWS Management Console.
In this project I worked on Techskill institute students anlysis, throught the project I
have worked on different AWS platform.
## Prerequisites
- An active AWS account with permissions to use Amazon S3, AWS Glue, and Amazon Athena.
- Data files stored in an S3 bucket (CSV). 
- Basic familiarity with AWS services: S3, Glue, Athena, and SQL.
## Step-by-Step Guide

### 1. Set Up an S3 Bucket
- Open the Amazon S3 console.
- Create a new bucket or use an existing one.
- Upload your data files to the bucket, organizing them logically for easier crawling and querying.

### 2. Create and Configure AWS Glue Crawler
- Open the AWS Glue console and navigate to **Crawlers**.
- Click **Add crawler** and provide a name.
- Select **S3** as the data store and specify your bucket path.
- Choose or create an IAM role with necessary permissions.
- Select or create the target AWS Glue database for discovery results.
- Review configuration and finish.
- Start the crawler to analyze and catalog your data schema.
### 3. Configure Athena Query Result Location
- Open the Amazon Athena console.
- Go to **Settings** and set an S3 bucket for storing query results.
- Save the settings.
### 4. Query Data Using Athena
- In Athena, select the database created by Glue crawler.
- Write SQL queries to analyze your S3 data.
- Run queries and view results in Athena or the S3 bucket.
## Example Outputs
The project includes analysis such as:
- Students with their orders
- Total orders and revenue by course
- Top 10 students by orders
- Number of students
- Top 5 orders placed by each student
## Benefits
- Cost-effective data storage using Amazon S3.
- Automated schema discovery with AWS Glue Crawler.
- Serverless, scalable SQL querying using Amazon Athena.
- No need to manage traditional database infrastructure.
## Project overview on:
(https://github.com/YashaswiniBaglakadi/Amazon-Web-Service/tree/d3b6120df6149d7cd549432bde192085f1382256/AWS%20Project%20Data)
