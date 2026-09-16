# Joyn — Video Streaming Analytics and Snowflake DWH

| Field | Details |
|---|---|
| Created | 2026-09-16 |
| Last Reviewed | 2026-09-16 |
| Author | Tieu My |

## General Information

| Field | Details |
|---|---|
| **Project Name** | Joyn — Video Streaming Analytics and Snowflake DWH |
| **Project Owner, Co-Owner** | Sergio Spinatelli, no Co-Owner |
| **Customer** | Joyn |
| **Visibility** | no |
| **Industry** | Media |
| **Topic / Area** | Cloud DWH, QoS analytics, and real-time data processing |
| **From** | 2019 |
| **To** | 2021 |

---

## Project Insights
> The project delivered a real-time, event-driven streaming analytics and decisioning platform. It enabled concurrent stream blocking, trending-content detection, precise resume playback, user-session tracking, and video-stream quality analytics. The solution went live after three months, supported more than 300,000 concurrent viewers, and made data available in under one second.



## Business Needs

#### 1. Scalable Cloud Data Warehouse

Build a cloud-native data warehouse that can accommodate customer growth and increasing data volumes while minimizing operational overhead.

#### 2. Real-Time Quality and Experience Analytics

Compute and analyze quality-of-service and user-experience KPIs in real time and provide flexible visual access to the results.

#### 3. Real-Time Decisioning and Compliance

Process video-stream events in real time to enforce simultaneous-login restrictions, support content licensing rules, and improve the viewer experience.



## Provided Services
### Cloud/ onPrem: Cloud AWS

#### 1. Data Warehouse Architecture and Data Modelling

Designed the Snowflake-based data warehouse and surrounding infrastructure, including a custom Data Vault 2.0 model implemented with dbt.

#### 2. Real-Time Streaming Architecture

Designed and implemented a microservice-based real-time processing architecture using Confluent Cloud, Apache Kafka, and Kafka Streams applications deployed on AWS.

#### 3. AWS Infrastructure and Automation

Designed and implemented AWS architecture using Infrastructure as Code, including CI/CD, user management, automation, monitoring, and secure credential management.



## Frameworks & Tech Stack

- AWS
- Apache Kafka
- Kafka Streams
- Snowflake
- Data Vault 2.0
- dbt
- Confluent Cloud
- Amazon DynamoDB
- AWS Fargate
- Amazon ECS
- AWS CloudFormation
- AWS Secrets Manager
- AWS CloudWatch
- REST APIs
- Tableau
- JavaScript

## Working methodology
- No working methodology available.
- OFFEN


## Mastering Challenges

#### 1. Legacy-System Replacement Under a Tight Timeline

Replace legacy solutions and deliver an MVP within two months, with go-live achieved after three months.

#### 2. High-Volume Real-Time Processing

Handle streaming-activity peaks exceeding ten times the normal baseline while maintaining low-latency event processing.

#### 3. Immediate Account-Sharing Enforcement

Analyze continuous user-generated events and enforce concurrent-stream restrictions within seconds.

