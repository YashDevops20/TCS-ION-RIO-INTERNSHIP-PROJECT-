# Containerized Jenkins Pipeline on AWS Cloud

## Description
This project demonstrates the creation of a containerized Jenkins pipeline on AWS. The pipeline automates the build, test, and deployment processes for a Java application using Docker and AWS services.

## Features
- CI/CD pipeline using Jenkins
- Docker containerization of the application
- Deployment on AWS ECS
- Integration with GitHub for version control

## Technologies Used
- **Jenkins**: Automation server for CI/CD
- **Docker**: Containerization of the application
- **AWS**: Amazon Elastic Container Service (ECS) and Elastic Container Registry (ECR)
- **Java**: Application programming language
- **GitHub**: Source code repository

## Prerequisites
- An AWS account
- Basic knowledge of AWS services (ECS, ECR)
- Docker installed on your local machine
- Jenkins installed on an EC2 instance

## Installation

1. **Set Up AWS Environment**:
   - Launch an EC2 instance and install Docker and Jenkins.
   - Configure security groups to allow HTTP (port 80) and Jenkins (port 8080).

2. **Configure Jenkins**:
   - Install necessary plugins (Docker Pipeline, GitHub Integration).
   - Create a new pipeline job and configure it with the provided Jenkinsfile.

3. **Set Up AWS ECR and ECS**:
   - Create an ECR repository for your Docker images.
   - Create an ECS cluster and define a task definition for your application.

4. **Set Up GitHub Webhook**:
   - Create a webhook in your GitHub repository to trigger Jenkins builds on code push.

