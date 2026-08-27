# Terraform ec2 Deployment

##Overview
Provisioned an AWS EC2 instance using Terraform (Infrastructure as code) instead of manual AWS console steps, referencing an existing custom VPC and security group.

##What I Built
-Terraform configuration ("main.tf") defining an AWS EC2 instance
-Referrenced existing custom VPC subnet and security group (built manually in an earlier project) via 'subnet_id' and "vpc_security_group_ids"
-Used 'terraform init' , "terraform plan" , and 'terraform apply' to provisioning infrastructure as code
-Debugged real deployment issues: missing VPC/subnet reference, troubleshooting real deployment errors

##Skills demonstrated
Terraform, Infrastructure as Code(IaC) ,AWS CLI, EC2, VPC integration, troubleshooting real deployment errors

##Why Terraform
Enables repeatable, version-controlled infrastructure instead of manual console clicks - critical for consistency and across teams.
