# AWS Cloud Architecture for a Medical Startup

## Project Overview
This repository contains the architecture design and supporting files for creating a secure, scalable, and highly available AWS infrastructure for a medical startup. The solution supports a medical social networking and diagnosis application, facilitating secure interactions between patients and doctors.

## Features
- **Secure Cloud Infrastructure**: VPCs with public and private subnets, IAM roles, and security groups.
- **Scalability and High Availability**: Autoscaling groups, Application Load Balancers, and Multi-AZ RDS configurations.
- **Global Reach**: Regional configurations across North America, EMEA, and APAC with Route 53 for latency-based routing.
- **Monitoring and Auditing**: AWS CloudTrail and CloudWatch for continuous monitoring and log storage.
- **Business Continuity**: Fault tolerance and disaster recovery mechanisms using Multi-AZ RDS and Autoscaling.

## Architecture Diagram: 

https://github.com/shivamsinha2000/Network_Infrastructure_Design-Healthcare_Industry/blob/1a42100657a861140973352ca7e80f9ef51966db/Architecture%20Diagram.svg


## AWS Services Used
- **Compute**: EC2, Autoscaling Groups
- **Networking**: VPC, Internet Gateway, NAT Gateway, Route 53, Load Balancers
- **Database**: Amazon RDS (Microsoft SQL Server)
- **Security**: IAM, Security Groups, Multi-Factor Authentication (MFA)
- **Monitoring**: CloudWatch, CloudTrail
- **Storage**: Amazon S3
- **Others**: AWS Well-Architected Tool
