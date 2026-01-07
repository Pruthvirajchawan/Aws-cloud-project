# Serverless API using AWS

This repository contains a simple serverless application built using AWS services.
The goal of this project is to understand how AWS serverless architecture works.

## Author
**Name:** Pruthviraj  
**GitHub:** https://github.com/Pruthvirajchawan

## What I Built
I built a basic REST API using AWS Lambda and API Gateway.
The API responds to HTTP requests without using any server or virtual machine.

## AWS Services Used
- AWS Lambda
- Amazon API Gateway
- Amazon S3 (for static files / testing)
- Amazon CloudWatch (logs and monitoring)

## How It Works
1. A request is sent to the API Gateway endpoint.
2. API Gateway triggers the Lambda function.
3. The Lambda function processes the request.
4. The response is sent back to the client.

## Why I Built This
I wanted to learn how to build scalable backend services on AWS without managing servers.
This project helped me understand event-driven architecture and cloud-native design.

## What I Learned
- Basics of AWS Lambda
- How API Gateway integrates with Lambda
- IAM permissions and security basics
- Monitoring logs using CloudWatch

## Future Improvements
- Add DynamoDB for data storage
- Add authentication
- Improve error handling
