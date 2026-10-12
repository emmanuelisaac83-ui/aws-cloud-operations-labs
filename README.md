# AWS Cloud Operations Labs

Hands-on AWS labs covering serverless application deployment with AWS Lambda, cost monitoring with AWS Budgets, and foundation model experimentation with Amazon Bedrock.

## About This Project

This repository documents my practical learning journey with Amazon Web Services (AWS). It showcases three cloud labs focused on serverless computing, cloud cost management, and generative AI.

## Lab 1: Serverless Web Application with AWS Lambda

**Objective:** Build, deploy, and test a simple serverless web application using Python.

**AWS Services and Technologies:**
- AWS Lambda
- Python
- JSON
- Lambda Function URL

**What I Did:**
1. Created a Lambda function named `cloud-lab-web-app`.
2. Wrote and deployed a Python function that returns a JSON response.
3. Tested the function in the AWS Lambda console.
4. Created a Function URL to access the application through a browser.
5. Verified that the application returned an HTTP 200 response and the expected JSON data.

**Sample Response:**

```json
{
  "message": "Hello from my AWS Lambda web app!",
  "project": "Cloud Operations Lab",
  "status": "success"
}
```

**Key Learning:** Deploying and testing serverless applications, handling HTTP responses, and understanding public endpoint security.

## Lab 2: AWS Cost Monitoring with AWS Budgets

**Objective:** Create a monthly budget to monitor AWS spending.

**What I Did:**
- Created a monthly budget named `Cloud-Lab-Monthly-Cost-Budget`.
- Configured a budget alert.
- Explored how AWS Budgets helps monitor cloud spending.

**Key Learning:** Cost awareness, budget monitoring, and the importance of responding to spending alerts.

*Note: AWS Budgets provides monitoring and alerts; a budget does not automatically stop resources or guarantee a spending limit.*

## Lab 3: Foundation Models with Amazon Bedrock

**Objective:** Explore foundation models using the Amazon Bedrock playground.

**What I Did:**
- Accessed the Amazon Bedrock playground.
- Selected and interacted with a foundation model.
- Explored prompt-based interaction and generated responses.

**Key Learning:** Introduction to foundation models, prompt engineering, and AWS generative AI services.

## Skills Practised

- AWS Lambda deployment and testing
- Python fundamentals
- JSON and HTTP responses
- AWS cost monitoring
- Amazon Bedrock fundamentals
- Cloud security awareness
- Technical documentation

## Environment

- **Cloud Provider:** Amazon Web Services (AWS)
- **Lambda Region:** `eu-north-1`
- **Runtime:** Python
- **Response Format:** JSON

## Security and Cost Considerations

The Lambda Function URL was configured for public access during this demonstration. Public endpoints should be secured appropriately for production workloads.

AWS resource usage may incur charges depending on usage, service pricing, and applicable free-tier or credit allowances.

## Author

**Emmanuel Okogun**

Cloud & DevOps Engineering | Cloud Infrastructure | IT Support | IAM and Security

---

*This repository documents hands-on learning labs and is not intended to represent production-ready implementations.*
