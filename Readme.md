This code is to provide the below requirement

Create a repository in GitHub and use one of your favourite programming languages with a simple
project (e.g., Python, Java, etc.).
Create the below resources using either Terraform or CloudFormation:
1. Create a VPC with the CIDR block "10.10.10.0/24".
2. Create 2 public subnets.
3. Create 2 private subnets.
4. Create an Internet Gateway.
5. Create an Elastic IP for the NAT Gateway.
6. Create a NAT Gateway.
7. Create 1 public route table and associate it with the 2 public subnets.
8. Create 1 private route table and associate it with the 2 private subnets.
9. Create a security group for EC2 instances with the following rules:
o Allow inbound traffic on port 80 only from the ALB security group.
o Allow inbound traffic on port 443 only from the ALB security group.
o Allow inbound traffic on port 22 from all sources.
10. Create a security group for the ALB with the following rule:
o Allow inbound traffic on port 80 from all sources.
11. Create VPC endpoints for services that are necessary to access the EC2 instance from the
AWS Systems Manager (SSM).
12. Launch a private EC2 instance with the instance type t2.micro. Ensure that it is a private
instance without any public IP. Also install the required software like Python, Java and
etc..
13. Create an Application Load Balancer (ALB) for the EC2 instance.
14. Set up a CI/CD pipeline using AWS CodePipeline, CodeBuild, or CodeDeploy. You can use
one, two, or all of these tools.
