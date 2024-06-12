# 🟪 Training the use of Terraform to create a lambda function

<div align="center">
 <img src="https://raw.githubusercontent.com/vsantos1711/terraform-lambda-study/main/assets/terraform-image.png" alt="Terraform logo" width="180px" height="155px" />
 <img src="https://raw.githubusercontent.com/vsantos1711/terraform-lambda-study/main/assets/lambda-image.png" alt="AWS Lambda function logo" width="180" height="155px"/>
</div>

## Description

This project is a basic example of how to create a lambda function using TypeScript and Terraform. The lambda function is written in TypeScript and then transpiled to JavaScript for use by AWS Lambda. Terraform is used to create the necessary infrastructure on AWS and configure the lambda function.

## Technologies Used

- **Typescript (Javascript):** The primary programming language for the project.
- **Terraform:** Infrastructure as Code (IaC) tool used to provision AWS services.
- **AWS Services:**
  - **API Gateway:** Handles HTTP requests, serving as the entry point to the serverless architecture.
  - **Lambda Functions:** Enables serverless compute for efficient and scalable processing.
  - **DynamoDB:** NoSQL database service for scalable and low-latency data storage and retrieval.

## System Architecture

![Frame](https://raw.githubusercontent.com/vsantos1711/terraform-lambda-study/main/assets/diagram.png)

## To-do

- [ ] Add API Gateway terraform code
- [ ] Add DynamoDB terraform code
- [ ] Add a real lambda function
