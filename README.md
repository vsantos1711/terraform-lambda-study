# 🟪 Training the use of Terraform to create a lambda function

![Frame](https://raw.githubusercontent.com/vsantos1711/terraform-lambda-study/main/assets/tech.png)

## Description

This project is a basic example of how to create a lambda function using TypeScript and Terraform. The lambda function is written in TypeScript and then transpiled to JavaScript for use by AWS Lambda. Terraform is used to create the necessary infrastructure on AWS and configure the lambda function.

## Technologies Used

- **[Typescript (Javascript):](https://www.typescriptlang.org/)** The primary programming language for the project.
- **[Terraform:](https://www.terraform.io/)** Infrastructure as Code (IaC) tool used to provision AWS services.
- **[AWS Services:](https://aws.amazon.com/)**
  - **[API Gateway:](https://aws.amazon.com/api-gateway/)** Handles HTTP requests, serving as the entry point to the serverless architecture.
  - **[Lambda Functions:](https://aws.amazon.com/lambda/)** Enables serverless compute for efficient and scalable processing.
  - **[DynamoDB:](https://aws.amazon.com/dynamodb)** NoSQL database service for scalable and low-latency data storage and retrieval.

## System Architecture

![Frame](https://raw.githubusercontent.com/vsantos1711/terraform-lambda-study/main/assets/diagram.png)

## To-do

- [ ] Add API Gateway terraform code
- [ ] Add DynamoDB terraform code
- [ ] Add a real lambda function
