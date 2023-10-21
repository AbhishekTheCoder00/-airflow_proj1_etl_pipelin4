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
Search for the Twitter API and understand its capabilities and limitations. Twitter Developer App:
### Step 2:
Create a Twitter Developer App with API keys and tokens: API key API secret key Access token Access token secret These keys are essential for authentication. Python ETL Code:
### Step 3;
Write Python code for Twitter data extraction and transformation. Use pip install to install necessary Python libraries. EC2 Instance:
### Step 4:
Create an Amazon EC2 instance on AWS with suitable specifications. SSH Connection:
### Step 5:
5.SSH into the EC2 instance using a command like ssh -i YOUR_KEY.pem ubuntu@YOUR_EC2_INSTANCE_IP. Airflow Installation:
### Step 6:
Install Apache Airflow on the EC2 instance following the official guide for your OS. Airflow Configuration:
### Step 7:
Set up and configure Apache Airflow. Ensure proper installation and configuration. Airflow DAG:
### Step 8:
Write an Airflow DAG Python code defining the Twitter ETL process. Specify tasks, dependencies, and scheduling. Connection Setup:
### Step 9:
Create necessary Airflow connections for external resources or API keys. DAG Directory:
### Step 10:
Organize your DAG files: Create a dedicated directory for the Twitter DAG. Place the Twitter DAG Python code and Twitter ETL Python code in this directory. Run the DAG:
### Step 11:
Use the Airflow CLI to trigger and run your Twitter DAG: airflow trigger_dag DAG_NAME airflow run DAG_NAME TASK_NAME Monitoring and Troubleshoot


This project aims to provide insights into Uber data through comprehensive data analytics. For a detailed explanation of each step and further project updates, please refer to the GitHub repository.
