# Introduction to AWS -- Study Guide

## 1. What is AWS?

Amazon Web Services (AWS) is a cloud computing platform provided by
Amazon. It offers on-demand computing resources such as servers,
storage, databases, networking, analytics, and machine learning over the
internet.

### Key Characteristics:

-   On-demand self-service
-   Broad network access
-   Resource pooling
-   Rapid elasticity
-   Measured service (pay-as-you-go)

------------------------------------------------------------------------

## 2. Cloud Computing Models

### Service Models

#### IaaS (Infrastructure as a Service)

-   Virtual machines
-   Storage
-   Networking Example: Amazon EC2

#### PaaS (Platform as a Service)

-   Managed platforms for development Example: AWS Elastic Beanstalk

#### SaaS (Software as a Service)

-   Fully managed software solutions Example: AWS WorkMail

------------------------------------------------------------------------

## 3. AWS Global Infrastructure

### Regions

-   Physical geographic locations (e.g., us-east-1, sa-east-1)

### Availability Zones (AZs)

-   Multiple isolated data centers within a region

### Edge Locations

-   Used for content delivery (CloudFront)

------------------------------------------------------------------------

## 4. Core AWS Services

### Compute

-   **EC2** -- Virtual servers
-   **Lambda** -- Serverless functions
-   **Elastic Beanstalk** -- Application deployment platform

### Storage

-   **S3 (Simple Storage Service)** -- Object storage
-   **EBS (Elastic Block Store)** -- Block storage for EC2
-   **Glacier** -- Archival storage

### Databases

-   **RDS** -- Managed relational databases
-   **DynamoDB** -- NoSQL database
-   **Aurora** -- High-performance relational database

### Networking

-   **VPC (Virtual Private Cloud)** -- Isolated cloud network
-   **Route 53** -- DNS service
-   **CloudFront** -- Content delivery network

------------------------------------------------------------------------

## 5. Security in AWS

### Shared Responsibility Model

-   AWS: Security *of* the cloud
-   Customer: Security *in* the cloud

### IAM (Identity and Access Management)

-   Users
-   Roles
-   Policies
-   Groups

### Best Practices

-   Use least privilege principle
-   Enable MFA
-   Rotate access keys
-   Monitor with CloudTrail

------------------------------------------------------------------------

## 6. Pricing and Billing

### Pricing Models

-   On-demand
-   Reserved instances
-   Spot instances
-   Savings Plans

### Cost Management Tools

-   AWS Cost Explorer
-   AWS Budgets
-   AWS Pricing Calculator

------------------------------------------------------------------------

## 7. Basic Architecture Example

Simple Web Application Architecture: 1. Route 53 (DNS) 2. CloudFront
(CDN) 3. EC2 or Elastic Beanstalk (Application Layer) 4. RDS (Database)
5. S3 (Static files & backups)

------------------------------------------------------------------------

## 8. Benefits of AWS

-   Scalability
-   High availability
-   Global reach
-   Security compliance
-   Pay-as-you-go pricing

------------------------------------------------------------------------

## 9. Certification Path (Optional Study Goal)

-   AWS Cloud Practitioner (Foundational)
-   AWS Solutions Architect -- Associate
-   AWS Developer -- Associate
-   AWS SysOps Administrator -- Associate

------------------------------------------------------------------------

## 10. Study Tips

-   Create a Free Tier AWS account
-   Practice launching EC2 instances
-   Upload files to S3
-   Configure IAM roles
-   Build a small project (e.g., static website on S3)

------------------------------------------------------------------------

### Recommended Next Steps

-   Learn VPC networking basics
-   Understand EC2 pricing models
-   Practice IAM policy creation
-   Explore serverless architecture with Lambda

------------------------------------------------------------------------

**End of Study Guide**
