# AMDA

| Field | Details |
|---|---|
| Created | 2026-09-03 |
| Last Reviewed | 2026-09-03 |
| Author | Tieu My Cao |

## General Information

| Field | Details |
|---|---|
| **Project Name** | AMDA |
| **Project Owner, Co-Owner** | Andrea Patelli, OFFEN |
| **Customer** | VW |
| **Visibility** | no |
| **Industry** | Automotive |
| **Topic / Area** | Monitoring and Observability |
| **From** | Nov 2022 |
| **To** | Mar 2025 |

---

## Project Insights
> Ongoing DevOps project for custom application monitoring of workloads on a Big Data platform based on OpenShift. The goal was to improve the development and deployment process for monitoring, alerting, and visualization of metrics and logs to increase the efficiency of the monitoring team. The solution was rolled out for 3 productive applications of the Data Analytics Platform; further rollouts are ongoing or planned.



## Business Needs

#### 1. Lack of End-to-End System Transparency

In the project context, there was a recurring need for more transparency about what is actually happening within individual systems, especially when multiple components interact and errors cannot be immediately attributed. Rather than simply collecting additional technical metrics, the focus was on creating a shared understanding of platform stability, identifying bottlenecks, and detecting anomalies early. In the automotive environment with on-premises hosting and longer operational periods, it is critical that operations, development, and business stakeholders do not only react to acute incidents but ideally receive early warnings when a problem is developing. Discussions revealed that much information already exists somewhere but is not always centralized, consistent, or presented in an understandable way. Therefore, the need arose to expand monitoring and observability so that technical states become more traceable and all stakeholders can more quickly identify whether a problem is caused by infrastructure, application, or process issues.

#### 2. Slow Root Cause Analysis and Incident Response

A recurring theme was that during outages or unexpected behavior, too much time is lost before the root cause is identified and the responsible party can act. Especially in complex system landscapes, it is difficult to manually correlate individual logs, metrics, and events when they are not properly correlated or uniformly structured. This created the need to improve observability capabilities so that error patterns can be narrowed down more quickly and operations teams do not have to start from scratch every time. Important is not only pure technical monitoring but also the ability to retrospectively trace what happened, when, which component was affected, what dependencies existed, and whether similar patterns occurred before. For a long-running project like AMDA, it is business-critical to reduce downtime, improve response times, and make coordination between teams more efficient. The goal is a better decision-making basis during incidents without teams having to laboriously gather information from different systems.

#### 3. Lack of a Unified Operational Quality View

Discussions also made clear that monitoring should not only be understood as a purely technical control instrument but also as a foundation for steering operations more purposefully in the long term and deriving improvements. There is a need to prepare relevant information so that it is understandable and usable for both technical teams and project stakeholders. This includes stability, availability, performance, error frequencies, and recurring anomalies, but also the question of how well existing processes function in daily operations. Currently, much information appears distributed or situational, making it difficult to obtain a unified picture of the actual project and system state. For VW and the AMDA project, it would therefore be important to create a consistent view of operational quality to recognize risks earlier, prioritize measures better, and justify technical optimizations transparently to stakeholders. Overall, observability should not only help with troubleshooting but also provide a reliable basis for continuous improvement and long-term operational stability.



## Provided Services
### Cloud/ onPrem: OnPrem

#### 1. CI/CD Pipeline for Automated Deployment

CI/CD pipeline for automatic deployment of dashboards, alerts, and workloads.

#### 2. Infrastructure-as-Code Workspace

Infrastructure-as-Code workspace with Helm packages and Docker images.

#### 3. Custom Monitoring Tool for Trino Queries

Custom monitoring tool for Trino query monitoring and analysis.

#### 4. Grafana Dashboards for Metrics Visualization

Grafana dashboards for metrics visualization with real-time visibility into system health and resource consumption.



## Frameworks & Tech Stack

- OpenShift
- Helm
- Prometheus
- Grafana Loki
- Grafana
- Kubernetes
- Bamboo

## Working methodology
- OFFEN


## Mastering Challenges

#### 1. Building DevOps Structure from Scratch

Setting up a DevOps structure from the ground up for existing manually created resources.

#### 2. Optimizing for Multi-Application Onboarding

Optimizing and refactoring the solution to enable onboarding and support of additional applications.

#### 3. Balancing Generic and Application-Specific Solutions

Understanding the specifics of individual applications to deliver a stable yet generic and simultaneously tailored solution.

