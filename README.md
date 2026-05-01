<h1 align="center">
🌐 Cloud Native Web Application
</h1>

### Built With
- ![gcp](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
- ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
- ![Packer](https://img.shields.io/badge/packer-%23E7EEF0.svg?style=for-the-badge&logo=packer&logoColor=%2302A8EF)
- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
- ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
- ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
- ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
- ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Architecture Diagram

![test drawio](https://github.com/chebrolusai/DocBook/assets/144749543/65d55fcf-fbfa-4c21-b471-f563c67a2bc6)

### 🚀 Project Overview 

This project is a comprehensive demonstration of cloud application development and deployment, emphasizing robust security, availability and scalability:

- RESTful Application Development & Enhanced CI:
     - Developed a scalable RESTful application, with Continuous Integration via GitHub Actions ensuring code reliability and quality
     - Integrated detailed logging and metrics for effective monitoring and performance analysis
- Application Scaling and Event-Driven Architecture:
     - Implemented AutoScaling for dynamic capacity management targetting CPU utilization
     - Used Google Cloud Pub/Sub for an efficient, event driven architecture
- Robust Infrastructure Deployment with Security:
     - Deployed a secure GCP infrastructure, with a focus on network and resource isolation
     - Utilized IAM roles and security groups to enforce strict access controls and security best practices
     - Configured the Application Load Balancer to only accept HTTPS requests, enhancing data security in transit, with SSL/TLS certificates managed through GCP managed Certificate
     - Employed Cloud DNS for reliable domain registration and DNS management
- Cloud Functions for Automation:
     - Integrated GCP Cloud functions for automated responses to specific events, streamlining operations and increasing efficiency
- Encryption
     - Used Customer Managed Encryption Keys to manage encryption for the Cloud Database, Instance Templates and Bucket Storage

### ☁️ List of Cloud services used:
- 🌐 VPC (Virtual private cloud)
- ⚖️ External Application Load Balancer (ALB)
- ⚖️ Auto Scaler for Managed Group Instances (MIG)
- 🔍 Ops Agent (Logs and metrics)
- 🔑 Cloud Key Management Service
- ☁️  Cloud DNS
- 💻 Virtual Machines
- 🗄️ Cloud SQL

### 🛠️ Code
- For more specific implementation details, visit the repos :

- Application and REST APIs : https://github.com/CloudNative-py/webapp
- Infrastructure: https://github.com/CloudNative-py/-tf-gcp-infra
- Cloud Function: https://github.com/CloudNative-py/serverless_main

