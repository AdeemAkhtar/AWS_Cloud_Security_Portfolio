# AWS_Cloud_Security_Portfolio

All the projects that I have completed on AWS to learn and demonstrate Security.

## Project (Part 1): Encrypt Data with AWS KMS

![<# alt text #>](1_Encrypt_Data_with_AWS_KMS/Encrypt%20Data%20with%20AWS%20KMS%20Architecture.png "Screenshot")

### The Used Services:

* IAM
* KMS
* DynamoDB

### Summary:
* Created and configured a Customer Managed Key in AWS KMS
* Encrypted a DynamoDB table using the CMK
* Controlled access to data via IAM and KMS key policies

---

## Project (Part 2): Secure Secrets with Secrets Manager
![<# alt text #>](2_Secure_Secrets_with_Secrets_Manager/Architecture.png "Screenshot")

### The Used Services:

* IAM
* AWS Secret Manager
* Github

### Summary:
* Used GitHub to scan for secrets
* Retrieved secrets from AWS Secrets Manager
* Cleaned Git history with rebasing

---

## Project (Part 3):Build a Security Monitoring System 
![<# alt text #>](3_Build_a_Security_Monitoring_System/Architecture.png "Screenshot")

### The Used Services:

* AWS Secrets Manager
* AWS CloudTrail
* AWS CloudWatch Metric
* AWS CloudWatch Alarm
* Amazon SNS

### Summary:
Here's what I did:

* Set up AWS Secrets Manager to securely store sensitive data
* Configured AWS CloudTrail to track and log every access attempt
* Created a CloudWatch Metric Filter to detect secret access events
* Set up CloudWatch Alarms to trigger alerts when secrets are accessed
* Integrated Amazon SNS to send me instant email notifications

---