# AWS Infrastructure
AWS Cloud formation templates used for the Web application project

------
## Usage:
 > aws cloudformation --region <region> create-stack --stack-name <stack name> --template-body file://project-infrastructure.yaml
    
**This template will:**
- Create a VPC with:
    - 3 Public Subnets in each AZs
- An Internet Gateway (with routes to it for Public Subnets)
- Route table    
     
