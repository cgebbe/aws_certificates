# Table of Content

## CHAPTER 1 Introduction

Course Introduction
About the Training Architect

## CHAPTER 2 AWS Fundamentals

The Building Blocks of AWS: Availability Zones and Regions
Who Owns What in the Cloud?
Compute, Storage, Databases, and Networking
What Is the Well-Architected Framework?
AWS Fundamentals Exam Tips
AWS Certified Solutions Architect - Associate (SAA-C03) - AWS Fundamental Building Blocks Quiz

## CHAPTER 3 Identity and Access Management (IAM)

Securing the Root Account
Controlling Users' Actions with IAM Policy Documents
Permanent IAM Credentials
IAM Exam Tips
Introduction to AWS Identity and Access Management (IAM)
Create and Assume Roles in AWS

## CHAPTER 4 Simple Storage Service (S3)

S3 Overview
Securing Your Bucket with S3 Block Public Access
Hosting a Static Website Using S3
Versioning Objects in S3
S3 Storage Classes
Lifecycle Management with S3
S3 Object Lock and Glacier Vault Lock
Encrypting S3 Objects
Optimizing S3 Performance
Backing up Data With S3 Replication
S3 Exam Tips

## CHAPTER 5 Elastic Compute Cloud (EC2)

EC2 Overview
Demo: Launching an EC2 Instance
AWS Command Line
Using Roles
Security Groups and Bootstrap Scripts
EC2 Metadata and User Data
Networking with EC2
Optimizing with EC2 Placement Groups
Solving Licensing Issues with Dedicated Hosts
Timing Workloads with Spot Instances and Spot Fleets
Deploying vCenter in AWS with VMware Cloud on AWS
Extending AWS Beyond the Cloud with AWS Outposts
EC2 Exam Tips

## CHAPTER 6 Elastic Block Storage (EBS) and Elastic File System (EFS)

EBS Overview
Volumes and Snapshots
Protecting EBS Volumes with Encryption
EC2 Hibernation
EFS Overview
FSx Overview
Amazon Machine Images: EBS vs. Instance Store
AWS Backup
EBS Exam Tips

## CHAPTER 7 Databases

Relational Database Service (RDS) Overview
Increasing Read Performance with Read Replicas
What Is Amazon Aurora?
DynamoDB Overview
When Do We Use DynamoDB Transactions?
Saving Your Data with DynamoDB Backups
Taking Your Data Global with DynamoDB Streams and Global Tables
Operating MongoDB-Compatible Databases in Amazon DocumentDB
Running Apache Cassandra Workloads with Amazon Keyspaces
Implementing Graph Databases Using Amazon Neptune
Leveraging Amazon Quantum Ledger Database (Amazon QLDB) for Ledger Databases
Analyzing Time-Series Data with Amazon Timestream
Databases Exam Tips

## CHAPTER 8 Virtual Private Cloud (VPC) Networking

VPC Overview
Demo: Provisioning a VPC - Part 1
Demo: Provisioning a VPC - Part 2
Using NAT Gateways for Internet Access
Protecting Your Resources with Security Groups
Controlling Subnet Traffic with Network ACLs
Private Communication Using VPC Endpoints
Building Solutions across VPCs with Peering
Network Privacy with AWS PrivateLink
Securing Your Network with VPN CloudHub
Connecting On-Premises with Direct Connect
Simplifying Networks with Transit Gateway
5G Networking with AWS Wavelength
VPC Networking Exam Tips

## CHAPTER 9 Route 53

Route 53 Overview
Register a Domain Name
Demo: Using a Simple Routing Policy
Demo: Using a Weighted Routing Policy
Demo: Using a Failover Routing Policy
Demo: Using a Geolocation Routing Policy
Demo: Using a Geoproximity Routing Policy
Demo: Using a Latency Routing Policy
Demo: Using a Multivalue Answer Routing Policy
Route 53 Exam Tips

## CHAPTER 10 Elastic Load Balancing (ELB)

ELB Overview
Using Application Load Balancers
Extreme Performance with Network Load Balancers
Using the Classic Load Balancer
Getting "Stuck" with Sticky Sessions
Leaving the Load Balancer with Deregistration Delay
ELB Exam Tips

## CHAPTER 11 Monitoring

CloudWatch Overview
Application Monitoring with CloudWatch Logs
Monitoring with Amazon Managed Service for Prometheus and Amazon Managed Grafana
Monitoring Exam Tips

## CHAPTER 12 High Availability and Scaling

Horizontal vs. Vertical Scaling Overview
What Are Launch Templates and Launch Configurations?
Scaling EC2 Instances with Auto Scaling
Diving Deeper into Auto Scaling Policies
Scaling Relational Databases
Scaling Non-Relational Databases
High Availability and Scaling Exam Tips

## CHAPTER 13 Decoupling Workflows

Decoupling Workflows Overview
Messaging with SQS
Sidelining Messages with Dead-Letter Queues
Ordered Messages with SQS FIFO
Delivering Messages with SNS
Fronting Applications with API Gateway
Executing Batch Workloads Using AWS Batch
Brokering Messages with Amazon MQ
Coordinating Distributed Apps with AWS Step Functions
Ingesting Data from SaaS Applications to AWS with Amazon AppFlow
Decoupling Workflows Exam Tips

## CHAPTER 14 Big Data

Exploring Large Redshift Databases
Processing Data with EMR (Elastic MapReduce)
Streaming Data with Kinesis
Amazon Athena and AWS Glue
Visualizing Data with QuickSight
Moving Transformed Data Using AWS Data Pipeline
Implementing Amazon Managed Streaming for Apache Kafka (Amazon MSK)
Analyzing Data with Amazon OpenSearch Service
Big Data Exam Tips

## CHAPTER 15 Serverless Architecture

Serverless Overview
Computing with Lambda
Leveraging the AWS Serverless Application Repository
Container Overview
Running Containers in ECS or EKS
Removing Servers with Fargate
Amazon EventBridge (CloudWatch Events)
Storing Custom Docker Images in Amazon Elastic Container Registry (Amazon ECR)
Using Open-Source Kubernetes in Amazon EKS Distro
Orchestrating Containers Outside AWS Using Amazon ECS Anywhere and Amazon EKS Anywhere
Auto Scaling Databases On Demand with Amazon Aurora Serverless
Using AWS X-Ray for Application Insights
Deploying GraphQL Interfaces in AWS AppSync
Serverless Architecture Exam Tips

## CHAPTER 16 Security

DDoS Overview
Logging API Calls with CloudTrail
Protecting Applications with Shield
Filtering Traffic with AWS WAF
Guarding Your Network with GuardDuty
Centralizing WAF Management via AWS Firewall Manager
Monitoring S3 Buckets with Macie
Securing Operating Systems with Inspector
Managing Encryption Keys with KMS and CloudHSM
Storing Your Secrets in Secrets Manager
Storing Your Secrets in Parameter Store
Temporarily Sharing S3 Objects Using Presigned URLs or Cookies
Advanced IAM Policy Documents
AWS Certificate Manager
Auditing Continuously with AWS Audit Manager
Downloading Compliance Documents from AWS Artifact
Authenticating Access with Amazon Cognito
Analyzing Root Cause Using Amazon Detective
Protecting VPCs with AWS Network Firewall
Leveraging AWS Security Hub for Collecting Security Data
Security Exam Tips

## CHAPTER 17 Automation

Why Do We Automate?
CloudFormation
Elastic Beanstalk
Systems Manager
Automation Exam Tips

## CHAPTER 18 Caching

Caching Overview
Global Caching with CloudFront
Caching Your Data with ElastiCache and DAX
Fixing IP Caching with Global Accelerator
Caching Exam Tips

## CHAPTER 19

Governance
Managing Accounts with Organizations
Sharing Resources with AWS RAM
Setting Up Cross-Account Role Access
Inventory Management with AWS Config
Offloading Active Directory to Directory Service
Exploring with Cost Explorer
Using AWS Budgets
Optimizing Costs with AWS Cost and Usage Reports
Reducing Compute Spend Using Savings Plans and AWS Compute Optimizer
Auditing with Trusted Advisor
Enforcing Account Governance via AWS Control Tower
Managing Software Licenses in AWS with AWS License Manager
Monitoring Health Events in the AWS Personal Health Dashboard
Standardizing Deployments Using AWS Service Catalog and AWS Proton
Optimizing Architectures with the AWS Well-Architected Tool
Governance Exam Tips
Creating AWS Tags and Resource Groups

## CHAPTER 20 Migration

Migrating Data with AWS Snow Family
Storage Gateway
AWS DataSync
AWS Transfer Family
Moving to the Cloud with Migration Hub
Migrating Workloads to AWS Using AWS Application Discovery Service or AWS Application Migration Service (AWS MGN)
Migrating Databases from On-Premises to AWS with AWS Database Migration Service (AWS DMS)
Replicating and Tracking Migrations with AWS Migration Hub and AWS Server Migration Service (AWS SMS)
Migration Exam Tips

## CHAPTER 21 Front-End Web and Mobile

Front-End Web and Mobile Overview
Quickly Deploying Web Apps with AWS Amplify
Testing App Services Using AWS Device Farm
Engaging Customers with Amazon Pinpoint
Front-End Web and Mobile Exam Tips

## CHAPTER 22 Machine Learning

Machine Learning Overview
Analyzing Text Using Amazon Comprehend, Amazon Kendra, and Amazon Textract
Predicting Time-Series Data Using Amazon Forecast
Protecting Accounts with Amazon Fraud Detector
Working with Text and Speech Using Amazon Polly, Amazon Transcribe, and Amazon Lex
Analyzing Images via Amazon Rekognition
Leveraging Amazon SageMaker to Train Learning Models
Translating Content into Different Languages with Amazon Translate
Machine Learning Exam Tips

## CHAPTER 23 Media

Media Overview
Converting Media Files with Amazon Elastic Transcoder
Streaming Live Video in AWS Using Amazon Kinesis Video Streams
Media Exam Tips

## CHAPTER 24

Exam Preparation
Revision for Success
Tackling Exam Questions
Booking Your Certification Exam
Preparing for Remote Proctored Exams
