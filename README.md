# Real_Time_Data_Streaming_Using_Apache_Nifi_AWS_Snowflake


### Introduction:

This project focuses on generating synthetic datasets on an AWS EC2 instance using Docker and JupyterLab, orchestrating data movement to Amazon S3 through Apache NiFi, and performing transformation and loading operations into Snowflake tables. 

### Architecture:

Generating The Raw Data Using Python Jupyter lab on EC2 -> Push The Raw Data Into AWS S3 Using Apache NIFI -> Transform The Data and Load into Snowflake Tables.


### Services used:

1. **AWS EC2:**  Amazon EC2 (Elastic Compute Cloud) is a core service in Amazon Web Services (AWS) that provides virtual servers (called instances) you can use to run applications, host websites, process data, or do almost anything you’d do on a physical computer — but in the cloud.
   
2. **Docker:** Docker is a containerization platform — it helps you run applications in isolated environments so they work the same everywhere (your laptop, EC2, or any other server).
   
3. **Apache NIFI:** Apache NiFi is a data integration and automation tool — it helps you move, transform, and manage data between different systems easily and visually.

4. **Amazon S3:** Amazon S3 (Simple Storage Service) is a cloud-based storage service provided by AWS.
It lets you store and retrieve any amount of data (like files, images, videos, logs, or backups) from anywhere on the internet — safely, securely, and at scale.

5. **Snowflake:** Snowflake is a cloud-based data warehouse — a system used to store, process, and analyze large amounts of data efficiently.
