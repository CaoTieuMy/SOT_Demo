# Joyn — Video Streaming Analytics and Snowflake DWH

| Field | Details |
|---|---|
| Created | 2026-09-16 |
| Last Reviewed | 2026-09-16 |
| Author | Tieu My C |

## General Information

| Field | Details |
|---|---|
| **Project Name** | Joyn — Video Streaming Analytics and Snowflake DWH |
| **Project Owner, Co-Owner** | Sergio Spinatelli, No co-owner |
| **Customer** | Joyn |
| **Visibility** | no |
| **Industry** | Media |
| **Topic / Area** | Cloud data warehouse, QoS analytics, and real-time video-streaming data processing |
| **From** | 2019 |
| **To** | 2021 |

---

## Project Insights
> A real-time, event-driven analytics and decisioning platform processed video-stream events to improve viewer experience, support content discovery, enforce account-sharing restrictions, and provide quality-of-service analytics. The project achieved go-live after three months, data availability under one second, and supported more than 300,000 concurrent viewers.



## Business Needs

#### 1. Scalable cloud data warehouse

A cloud-native data warehouse was needed to handle customer-base growth and increasing data loads with minimal operational overhead.

#### 2. Real-time quality and user-experience analytics

Quality-of-service and user-experience KPIs had to be computed and analyzed in real time and made available through flexible visualizations.

#### 3. Real-time decisioning for viewer experience and compliance

Video-stream events had to drive real-time decisions, including concurrent-stream blocking, trending-content calculation, and accurate resume playback positions.



## Provided Services
### Cloud/ onPrem: Cloud (AWS)

#### 1. Cloud data warehouse architecture and data modelling

Designed the data warehouse and surrounding infrastructure on Snowflake, including a custom Data Vault 2.0 model implemented with dbt.

#### 2. Real-time data processing architecture

Designed and implemented a microservice-based, event-driven architecture using Confluent Cloud, Apache Kafka, and Kafka Streams applications deployed on AWS.

#### 3. AWS infrastructure and automation

Implemented AWS architecture using best practices and Infrastructure as Code, including container orchestration, monitoring, credential management, CI/CD, user management, and further automation.



## Frameworks & Tech Stack

- AWS
- Snowflake
- Apache Kafka
- Confluent Cloud
- Kafka Streams
- dbt
- Data Vault
- Amazon DynamoDB
- AWS Fargate
- Amazon ECS
- AWS CloudFormation
- AWS Secrets Manager
- AWS CloudWatch
- REST APIs
- Microservices
- Tableau
- JavaScript

## Working methodology
- OFFEN
- OFFEN


## Mastering Challenges

#### 1. Legacy-system replacement under a tight timeline

Delivered the first MVP within two months and achieved go-live after three months while replacing legacy solutions.

#### 2. Real-time processing at peak scale

Built a real-time processing layer able to withstand viewing spikes of more than ten times the normal baseline.

#### 3. Scalable and adaptable data platform

Created a data warehouse architecture that could accommodate growth, volatile capacity requirements, and incremental model changes while supporting GDPR compliance.

