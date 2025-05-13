---
title: "AWS EC2 Load Balancer Deployment"
output: github_document
---

# AWS EC2 Load Balancer Deployment

## Project Description
Deployed a web application on AWS by launching an EC2 instance, configuring a Load Balancer, and hosting the application using Apache Web Server on a Linux-based system.  
Managed traffic distribution and ensured high availability through Load Balancer setup.

## Skills Practiced
- AWS EC2 instance launch and configuration
- Elastic Load Balancer (ELB) setup
- Linux server management
- Apache Web Server installation and configuration
- Basic cloud networking and security group setup

## Tech Stack
- **AWS Services:** EC2, Elastic Load Balancer (ELB)
- **Operating System:** Amazon Linux 2
- **Web Server:** Apache HTTP Server
- **Tools:** AWS Management Console, SSH

## Steps Performed
1. Launched an EC2 instance with Amazon Linux 2 AMI.
2. Installed and configured Apache Web Server (`sudo yum install httpd -y`).
3. Created a custom webpage hosted on the EC2 instance.
4. Configured security groups to allow HTTP and SSH access.
5. Set up an Elastic Load Balancer (Application Load Balancer).
6. Registered the EC2 instance with the Load Balancer target group.
7. Tested the application accessibility via the Load Balancer DNS.

## Best Practices Followed
- Security groups configured with minimum required access.
- Stopped instances after usage to manage AWS Free Tier billing.
- Monitored resource usage with AWS Budgets.

## Repository Highlights
- **Deployed on AWS EC2 with Load Balancer**
- **Skills:** EC2 | Load Balancer | Linux | Apache Web Server

## Future Enhancements
- Auto-scaling group integration for dynamic scaling
- SSL certificate integration for HTTPS traffic
- Deployment automation using AWS CLI and Infrastructure as Code (IaC)

