# AWS Budgets — Cloud Cost Monitoring

## Objective

Configure an AWS monthly cost budget to monitor cloud spending and improve cost awareness when working with AWS services.

## AWS Service

- AWS Budgets

## Implementation

I created a monthly cost budget in AWS with the following configuration:

- **Budget name:** `Cloud-Lab-Monthly-Cost-Budget`
- **Budget type:** Cost budget
- **Budget period:** Monthly
- **Planned budget amount:** $5
- **Alert:** Configured to notify me when the budget threshold is reached.

*The alert configuration should be verified against the actual settings in the AWS Console.*

## Why This Matters

Cloud cost monitoring is an important part of cloud operations. Resources used for learning, testing, and development can generate charges if they are not monitored.

AWS Budgets helps users track spending against a planned amount and receive alerts when configured thresholds are reached.

## Key Learnings

- Creating and configuring a monthly AWS cost budget.
- Setting up budget alerts.
- Understanding the importance of cost visibility in cloud environments.
- Recognizing that budgets alert users but do not automatically stop resources.

## Evidence

<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/a22523e6-5873-4dd1-9a90-9a9df1cbecb5" />


## Security and Cost Note

Budget alerts do not guarantee that spending will remain within the configured amount. Actual charges depend on resource usage, service pricing, and applicable credits or free-tier allowances.

This lab was completed for learning and portfolio purposes.
