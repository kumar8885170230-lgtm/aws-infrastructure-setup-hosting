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
