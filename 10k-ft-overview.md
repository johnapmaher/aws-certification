# AWS 10,000 Foot Overview

This lesson provides a very brief overview of the current AWS landscape.


## Compute
EC2 - Elastic Compute Cloud.
ECS - Elastic Container Service - orchestrates docker containers.
Elastic Beanstalk - PaaS-style upload application and the rest is taken care of.
Lambda - serverless/function as a service.
Lightsail - VPS service, provisioned server - think Digital Ocean.
Batch - Batch processing.

## Storage
S3 - Simple Storage Service.
EFS - Elastic File System/NAS.
Glacier - Data archival/Cheap storage.
Snowball - Physical transfer of data.
Storage Gateway - Physical replication of S3.

## Databases
RDS - Relational Database Service.
DynamoDB - Amazon's own noSQL.
Elasticache - caching service.
Red Shift - Data-warehousing.

## Migration
AWS Migration Hub - centralizes metrics on and the current progress of migrations
Application Discovery Service - Tracking application and app dependencies
Database Migration Service - simplify migration of db to AWS
Server Migration Service - simplify migration of server to AWS
Snowball - Physical transfer of data.

## Network & Content Delivery
VPC - Virtual Private Cloud.
CloudFront - Amazon's CDN.
Route53 - DNS service, DNS mapping from domain to ipv4/ipv6.
API Gateway - Edge service providing an access point to an API.
Direct Connect - provides a connection between AWS and a company's own data center.


## Developer Tools
CodeStar - Continous Delivery collab tool.
CodeCommit - version control
CodeBuild - Build pipeline
CodeDeploy - Deploy pipeline
CodePipeline - Continous Delivery service
X-Ray - Serverless analysis tool
Cloud9 - IDE build into AWS console

## Management Tools
CloudWatch - Sys Ops management tool
CloudFormation - Infrastructure as code
CloudTrail - Logging configuration changes
Config - Tranverse config history
OpsWorks - Chef & Puppet Automation
Service Catalog - cataloging available service, governance etc.
Systems Manager - Grouping/Patching bunch of Systems
Trusted Advisor - Advises on security/cost improvements
Managed Services - autoscaling etc.

## Media Services
Elastic Transcoder - Transcoding video for multi-device.
MediaConvert - File based media Transcoder.
MediaLive - HQ video streams.
MediaPackage - Prep for transport across web.
MediaStore - Storage optimized for media.
MediaTailor - Content monetization.

## Machine Learning
SageMaker - Deep Learning
Comprehend - Natural language processing, providing insight into text.
DeepLens - Hardware camera with onboard deep-learning processing.
Lex - Alexa engine.
Machine Learning - Creation of traditional machine learning models.
Polly - Text to speech.
Rekognition - Image/Video item recognition.
Amazon translate - translation service.
Transcribe - automatic speech recognition.

## Analytics
Athena - Serverless analysis of data in S3 quering via standard SQL.
EMR - Elastic Map-Reduce.
CloudSearch - Enables rich search capability in a website or application.
ElasticSearch Service - Managed Elasticsearch.
Kinesis - Ingestion large amounts of machine data.
Kinesis Video Stream - Ingest large amounts of video feed.
QuickSight - Business Intelligence tool.
Data Pipeline - Interval-based data transfer, processing and storage.
Glue - Managed serverless extract, transform and load (ETL) service.