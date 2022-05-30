# AWS Infrastructure
AWS Cloud formation templates used for the Web application project

------
## Usage:
 > aws cloudformation --region <region> create-stack --stack-name <stack name> --template-body file://project-infrastructure.yaml
 
--- 
 
**This template will create:**
 - A VPC with:
     - 3 Public Subnets in each AZs
 - An Internet Gateway (with routes to it for Public Subnets)
 - Route table
 - EC2 instance with custom AMI
 - Application Security Group
 - S3 bucket
 - RDS Instance with SQL configuration
 - DB Security group
 - RDS Parameter group
 - S3 bucket IAM policy
 - CodeDeploy service role
 - EC2 instance profile
 - Elastic Load balancer
 - Code Deploy
 - Dynamo DB Table
 - SNS topic
 - Lambda function
 - Lambda execution role, Lambda SNS permission, Lambda s3 policy
 - RDS secret key, EBS secret key
 

     
