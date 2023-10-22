# Twitter Data Pipeline using Airflow 


## Introduction

Access Twitter API, create an app, get API keys, and generate access tokens.Write Python ETL script using pandas and tweepy, install libraries.Set up AWS EC2, install and configure Apache Airflow.
Create Twitter DAG, establish S3 storage.Deploy and run DAG in Airflow, monitor, and store data in S3.

## Architecture

![Project Architecture](https://github.com/AbhishekTheCoder00/Airflow_proj1_etl_pipelin4/blob/main/Architecture%20Diagram.png)

## Technology Used

- Programming Language: Python
- Twitter API
- AWS Cloud Platform:
  1. Aamzon S3 Bucket
  2. Amazon EC2 instance
  3. IAM role
  4. Using EC2 instance deploy Airflow server


## Project Workflow

### Step 1:
Search for the Twitter API and understand its capabilities and limitations.
### Step 2:
Twitter Developer App: Create a Twitter Developer App with API keys and tokens: API key API secret key Access token Access token secret These keys are essential for authentication.
### Step 3:
Python ETL Code: Write Python code for Twitter data extraction and transformation. Use pip install to install necessary Python libraries. 
### Step 4:
EC2 Instance: Create an Amazon EC2 instance on AWS with suitable specifications. 
### Step 5:
SSH Connection: SSH into the EC2 instance using a command like ssh -i YOUR_KEY.pem ubuntu@YOUR_EC2_INSTANCE_IP. 
### Step 6:
Airflow Installation: Install Apache Airflow on the EC2 instance following the official guide for your OS.
### Step 7:
Airflow Configuration: up and configure Apache Airflow. Ensure proper installation and configuration.
### Step 8:
Airflow DAG: Write an Airflow DAG Python code defining the Twitter ETL process. Specify tasks, dependencies, and scheduling. 
### Step 9:
Connection Setup: Create necessary Airflow connections for external resources or API keys. 
### Step 10:
DAG Directory: Organize your DAG files: Create a dedicated directory for the Twitter DAG. Place the Twitter DAG Python code and Twitter ETL Python code in this directory. 
### Step 11:
Run the DAG: Use the Airflow CLI to trigger and run your Twitter DAG: airflow trigger_dag DAG_NAME airflow run DAG_NAME TASK_NAME Monitoring and Troubleshoot


This project aims to provide insights into Uber data through comprehensive data analytics. For a detailed explanation of each step and further project updates, please refer to the GitHub repository.
