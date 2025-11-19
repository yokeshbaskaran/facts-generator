# facts-generator

- Cloud Fun Facts 📔 Generator using AWS Services.

## 🛠️ Services used:

1. **AWS Lambda:** Serverless backend to generate cloud fun facts.
2. **Amazon API Gateway:** Exposes the Lambda as a REST API endpoint.
3. **Amazon DynamoDB:** Database for storing facts.
4. **Amazon Bedrock:** Generative AI to make facts witty.
5. **AWS Amplify:** Hosting service for the React frontend.
6. **AWS IAM:** Identity and Access Management for secure permissions.

## Steps:

- Deploy Backend with AWS Lambda + API Gateway
- Enhance with DynamoDB (store facts in a table)
- Integrate Amazon Bedrock (GenAI) to make facts
- Deploy Frontend with AWS Amplify (to display facts)

## Architecture Diagram:

<img width="1147" height="621" alt="Image" src="https://github.com/user-attachments/assets/1fddc984-86bf-4378-bbd3-b31c4e3970fb" />

## Output:

![Image](https://github.com/user-attachments/assets/c1e27cef-c553-4366-8cad-c2e390cab901)

API URL:
https://ljmj29fbz4.execute-api.ap-south-1.amazonaws.com/funfact
