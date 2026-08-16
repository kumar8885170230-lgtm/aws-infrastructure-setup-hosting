AWS Infrastructure Setup & Hosting

📌 Project Overview

This project demonstrates the design and configuration of AWS cloud infrastructure for reliable application hosting, with a focus on high availability, scalability, security, monitoring, and fault tolerance.

The infrastructure was configured using core AWS services including EC2, IAM, VPC, EBS, S3, CloudWatch, Auto Scaling, Application Load Balancer, and Route 53.

🏗️ AWS Services Used

Service

Purpose

Amazon EC2

Compute resources and application hosting

Amazon VPC

Network isolation and infrastructure networking

IAM

Roles, policies and access control

Amazon EBS

Persistent storage for EC2 instances

Amazon S3

Application/static workload hosting and storage

CloudWatch

Metrics, dashboards and monitoring

Auto Scaling

Automatic scaling based on workload requirements

Application Load Balancer

Traffic distribution and high availability

Route 53

DNS and traffic routing

🔐 Security & Access Management

Configured IAM roles and policies

Applied least-privilege access controls

Validated permissions for AWS resources

Configured security controls for cloud infrastructure

Used secure access practices for AWS resources

💾 Storage & Backup

Configured EBS volumes for EC2 instances

Performed Linux storage mounting

Worked with backup strategies

Validated server recovery procedures

Managed storage for reliable application hosting

⚙️ High Availability & Scalability

The infrastructure was designed with cloud reliability principles:

Auto Scaling for workload scalability

Application Load Balancer for traffic distribution

EC2-based application hosting

High availability and fault tolerance

Scalable cloud infrastructure

📊 Monitoring & Observability

Amazon CloudWatch was used for:

Infrastructure metrics

Monitoring dashboards

Alerts

Resource monitoring

Application infrastructure visibility

🐧 Linux Administration

Linux was used for server-side infrastructure operations, including:

Storage mounting

File-system operations

Process management

Log monitoring

Server validation

Troubleshooting

🔄 Infrastructure Flow

                    Route 53
                       │
                       ▼
              Application Load Balancer
                       │
              ┌────────┴────────┐
              ▼                 ▼
           EC2-1             EC2-2
              │                 │
              └────────┬────────┘
                       │
                  EBS Storage
                       │
                       ▼
                  Application


      ┌─────────────────────────────────┐
      │          AWS Services           │
      │ IAM | VPC | S3 | CloudWatch     │
      │ Auto Scaling | ALB | Route 53   │
      └─────────────────────────────────┘

🎯 Key Skills Demonstrated

AWS Cloud Infrastructure

EC2

VPC

IAM

EBS

S3

CloudWatch

Auto Scaling

Application Load Balancer

Route 53

Linux Administration

Cloud Security

High Availability

Scalability

Fault Tolerance

Monitoring & Troubleshooting

## 📸 AWS Implementation Screenshots

### 1. VPC
![VPC](01-vpc%5B1%5D.png)

### 2. Subnets
![Subnets](02-subnets%5B1%5D.png)

### 3. Internet Gateway
![Internet Gateway](03-internet-gateway%5B1%5D.png)

### 4. NAT Gateway
![NAT Gateway](04-nat-gateway%5B1%5D.png)

### 5. Route Tables
![Route Tables](05-route-tables%5B1%5D.png)

### 6. Security Groups
![Security Groups](06-security-groups%5B1%5D.png)

### 7. EC2 Instances
![EC2 Instances](07-ec2-instances%5B1%5D.png)

### 8. Target Groups
![Target Groups](08-target-groups%5B1%5D.png)

### 9. Application Load Balancer
![Load Balancer](09-load-balancer%5B1%5D.png)

### 10. AMI
![AMI](10-ami%5B1%5D.png)

### 11. Auto Scaling Groups
![Auto Scaling](11-auto-scaling-groups%5B1%5D.png)

### 12. Public EC2 Instance 1
![Public EC2 Instance 1](12-public-instance-1%5B1%5D.png)

### 13. Public EC2 Instance 2
![Public EC2 Instance 2](13-public-instance-2%5B1%5D.png)

### 14. RDS MySQL
![RDS MySQL](14-rds-mysql%5B1%5D.png)

### 15. Database Output
![Database Output 1](15-database-output-1%5B1%5D.png)

### 16. Database Output
![Database Output 2](16-database-output-2%5B1%5D.png)
