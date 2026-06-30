# AI Serverless Content Platform

## Project Overview

This project is a fully serverless cloud application built on AWS that generates AI-powered cloud facts through a REST API.

The application integrates AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Bedrock, and AWS Amplify to provide a scalable, cloud-native solution without managing servers.

---

## AWS Services Used

- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- Amazon Bedrock
- AWS Amplify
- AWS IAM
- Amazon CloudWatch

---

## Features

- Serverless REST API
- AI-powered cloud fact generation
- DynamoDB data storage
- React frontend hosted on Amplify
- Automatic scaling
- Secure IAM permissions

---

## Architecture

```text
User
   │
   ▼
AWS Amplify (React Frontend)
   │
   ▼
Amazon API Gateway
   │
   ▼
AWS Lambda
   ├────────────► Amazon DynamoDB
   │
   └────────────► Amazon Bedrock
```

## Project Structure

```text
.
├── README.md
├── architecture/
├── screenshots/
└── docs/
```

---

## Future Improvements

- Authentication with Amazon Cognito
- CI/CD using GitHub Actions
- Infrastructure as Code using AWS SAM or Terraform
