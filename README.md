# **Cloud Fun Facts 📔 Generator**

A serverless project built on AWS that generates fun and witty cloud-computing facts using generative AI.

- Built from scratch with guidance from _Tech with Lucy’s AWS course_
- Combines Serverless architecture + GenAI for dynamic fact generation

## 🛠️ **AWS Services Used**

1. **AWS Lambda** – Serverless compute for processing and generating facts
2. **Amazon API Gateway** – Publishes the Lambda function via a REST API
3. **Amazon DynamoDB** – NoSQL database storing cloud fun facts
4. **Amazon Bedrock** – Adds wit and personality using generative AI
5. **AWS Amplify** – Hosts and deploys the React frontend
6. **AWS IAM** – Provides secure access control across services

## 🚀 **Project Workflow**

- Deploy backend using **Lambda + API Gateway**
- Add **DynamoDB** for data persistence
- Integrate **Amazon Bedrock** for generative AI enhancements
- Deploy frontend through **AWS Amplify** (or S3 in the GenAI version)

Please review the full documentation for detailed implementation steps.

## Project Documents

Full step-by-step instructions are available in the documentation.

### 📄 Documentation

- **Doc 1:** [Deploy Backend (Lambda + API Gateway)](https://github.com/user-attachments/files/23718741/01_Backend_Deployment_Lambda_API_Gateway.pdf)

- **Doc 2:** [Database Version (DynamoDB + Lambda)](https://github.com/user-attachments/files/23718808/02_Database_Integration_DynamoDB_Lambda.pdf)

- **Doc 3:** [GenAI Version + Deploying App on S3](https://github.com/user-attachments/files/23718860/03_GenAI_Enhancement_and_App_Deployment.pdf)

## 📌 Architecture Diagram

<img width="1147" height="621" alt="Architecture Diagram" src="https://github.com/user-attachments/assets/1fddc984-86bf-4378-bbd3-b31c4e3970fb" />

## 📸 Output

![Output Screenshot](https://github.com/user-attachments/assets/c1e27cef-c553-4366-8cad-c2e390cab901)
