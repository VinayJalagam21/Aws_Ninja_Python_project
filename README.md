Project Title: Python-Powered Cloud Governance with AWS CloudWatch and Lambda

Introduction:
This AWS Lambda project automatically converts Amazon Elastic Block Store (EBS) volumes of type GP2 to GP3 using Amazon CloudWatch Events and Lambda. The Lambda function is triggered whenever a new EBS volume is created, and it checks if the volume is of type GP2. If so, it converts the volume to type GP3 to optimize costs and performance according to organizational policies.
