# DalVacationHome

A serverless vacation rental management platform leveraging AWS and Google Cloud services.

## Overview

DalVacationHome is a modern vacation rental management platform that combines the power of AWS and Google Cloud Platform to deliver a seamless experience for guests, customers, and property agents. The platform features:

- Multi-cloud serverless architecture
- Role-based access control
- Intelligent virtual assistance
- Real-time booking management
- Advanced analytics dashboard

## Key Features

### Guest Portal
- Real-time room availability checker
- AI-powered virtual assistant
- Public feedback and ratings system

### Customer Dashboard
- Secure multi-factor authentication
  - Password protection
  - Security questions
  - Caesar cipher challenge
- Online room booking system
- Enhanced virtual assistant support
- Personalized feedback system

### Agent Console
- Comprehensive room management
- Customer query dashboard
- Real-time analytics
- Dynamic pricing control

## Technical Architecture

### Cloud Services
- **AWS Services**
  - Cognito: User authentication
  - Lambda: Serverless computing
  - DynamoDB: Data storage
  - SNS/SQS: Notifications
  - API Gateway:
  - AWS Lex: Chatbot and NLP
  
- **Google Cloud Services**
  - Cloud Functions: Event handling
  - Firestore: Real-time database
  - Cloud Run: Frontend hosting
  - Looker Studio: Analytics


## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js
- **Authentication**: AWS Cognito
- **Databases**: 
  - AWS DynamoDB
  - Google Firestore
- **Message Handling**: 
  - Google Cloud Pub/Sub
  - AWS SNS/SQS
- **Analytics**: Google Looker Studio

## Setup Guide

### Prerequisites
1. AWS Account with appropriate permissions
2. Google Cloud Platform account
3. Node.js and npm installed
4. AWS CLI configured
5. Google Cloud SDK installed

### Infrastructure Deployment

### AWS Deployment (CloudFormation)

The serverless infrastructure in AWS is managed using CloudFormation:

Key components in CloudFormation:
- AWS Lex
- API Gateway
- SNS ans SQS Topic
- DynamoDB 
- Cognito

### GCP Deployment (Terraform)

The frontend infrastructure in GCP is managed using Terraform:

```bash
# Initialize Terraform
cd infra
terraform init

# Apply the changes
terraform apply

# Destroy infrastructure
terraform destroy
```
