# Módulo 3 - AWS Global Infrastructure

A AWS Region is a geographic location and usualy consists of two or more Avaliability Zones.

We should consider a few factors when selecting a Region:
- Legal requirements (laws)
- Proximity with customers (latency)
- Availble services for the region
- Costs (it may vary from Region to Region)

### Availability Zone
Each Region has multiple AZs
Avaliabilty Zones consists of multiple distincts Data Centers
Are projected for isolating failures and are interconected to other avaliability zones.

### Presence Points
Amazon CloudFront is a CDN (Content Delivery Network) used to distribute content to end user at a low latency.
Amazon Route 53 is a DNS (Domain Name Service) that routes any requests to the nearest presence point
Edge Locations and Regional Edge Caches improve performance by caching content in locations closer to users.

***

AWS Global Infrastrucutre can be broken down into 3 elements:
- Regions
- Avaliability Zones
- Points of Presence (which include Edge Locations)

This infrastructure provides the platform to network, compute, storage and database services.

#### Storage Services
- Amazon S3 (Simple Storage Service)
- Amazon EBS (Elastic Block Storage)
- Amazon EFS (Elastic File System)

#### Compute Services
- Amazon EC2 - Virtual Machines
- Amazon EC2 Auto Scaling
- Amazon ECS (Elastic Container Service) - Container Orchestration 
- Amazon EC2 Container Registry - Docker container images
- AWS Elastic Beanstalk 
- AWS Lambda
- Amazon EKS (Elastic Kubernetes Service)
- AWS Fargate

#### Database Services
- Amazon RDS (Relational Database Service)
- Amazon Aurora
- Amazon Redshift
- Amazon DynamoDB

#### Networking and Content Delivery Services
- Amazon VPC (Virtual Private Cloud)
- Amazon ELB (Elastic Load Balacing)
- Amazon CloudFront
- AWS Transit Gateway
- Amazon Route 53
- AWS Direct Connect
- AWS VPN 

#### Security, Identity and Complicance Services
- AWS IAM (Identity and Access Management)
- AWS Organizations
- Amazon Incognito
- AWS Artifact
- AWS KMS (Key Management Service)
- AWS Shield

#### Cost Management Services
- AWS Cost and Usage Report
- AWS Budgets
- AWS Cost Explorer

#### Management and Governance Services
- AWS Management Console
- AWS Config
- Amazon CloudWatch
- AWS Auto Scaling
- AWS CLI 
- AWS Trusted Advisor
- AWS Well-Architected Tool
- AWS CloudTrail