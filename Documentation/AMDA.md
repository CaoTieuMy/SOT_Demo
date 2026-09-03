# AMDA

| Field | Details |
|---|---|
| Created | 2026-09-03 |
| Last Reviewed | 2026-09-03 |
| Author | Tieu My C. |

## General Information

| Field | Details |
|---|---|
| **Project Name** | AMDA |
| **Project Owner, Co-Owner** | Andrea Patelli, none |
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

#### 1. Lack of Cross-System Transparency and Proactive Monitoring

In the project context, there was a recurring need for more transparency into what is actually happening across individual systems — especially when multiple components interact and errors cannot be immediately attributed. Rather than simply collecting additional technical metrics, the goal was to create a shared understanding of platform stability, identify bottlenecks, and detect anomalies early. In an automotive environment with on-prem hosting and longer operational periods, it is critical that operations, development, and business stakeholders do not only react to acute incidents but ideally receive early warning signs. It became clear that much information already exists but is not always centrally, consistently, or clearly presented. Therefore, there is a need to expand monitoring and observability so that technical states become more traceable and all stakeholders can quickly identify whether a problem is infrastructural, application-related, or process-driven.

#### 2. Slow Root Cause Analysis and Inefficient Incident Response

A recurring theme was that during outages or unexpected behavior, too much time is lost before the root cause is identified and the responsible team can act. In complex system landscapes, it is difficult to manually correlate individual logs, metrics, and events when they are not cleanly correlated or uniformly structured. This creates the need to improve observability capabilities so that error patterns can be narrowed down faster and operations teams do not have to start from scratch every time. Beyond pure technical monitoring, it is also important to be able to retrospectively trace what happened, when, which component was affected, what dependencies existed, and whether similar patterns occurred before. For a long-running project like AMDA, reducing downtime, improving response times, and streamlining coordination between teams is highly relevant from a business perspective. The goal is a better decision-making basis during incidents without teams having to painstakingly gather information from various systems.

#### 3. Fragmented Operational Insights and Missing Basis for Continuous Improvement

It also became clear that monitoring should not only serve as a purely technical control instrument but also as a foundation for steering operations more effectively in the long term and deriving improvements. There is a need to prepare relevant information in a way that is understandable and usable for both technical teams and project stakeholders — covering stability, availability, performance, error frequencies, and recurring anomalies, as well as how well existing processes function in daily operations. Currently, much information appears distributed or situational, making it difficult to obtain a unified picture of the actual project and system state. For VW and the AMDA project, it is therefore important to create a consistent view of operational quality to identify risks earlier, prioritize measures more effectively, and justify technical optimizations to stakeholders in a traceable manner. Overall, observability should not only help with troubleshooting but also provide a reliable basis for continuous improvement and long-term operational stability.



## Provided Services
### Cloud/ onPrem: OnPrem

#### 1. CI/CD Pipeline for Automated Deployment

CI/CD pipeline for automatic deployment of dashboards, alerts, and workloads.

#### 2. Infrastructure-as-Code Workspace

Infrastructure-as-Code workspace with Helm packages and Docker images.

#### 3. Custom Monitoring Tool

Custom monitoring tool for Trino queries.

#### 4. Grafana Dashboards

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

#### 2. Optimizing for Scalable Onboarding

Optimizing and refactoring the solution to enable onboarding and support of additional applications.

#### 3. Balancing Generic and Application-Specific Solutions

Understanding the specifics of individual applications to deliver a stable yet generic and simultaneously tailored solution.

