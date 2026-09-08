# AMDA v2

| Field | Details |
|---|---|
| Created | 2026-09-08 |
| Last Reviewed | 2026-09-08 |
| Author | Tieu My Cao |

## General Information

| Field | Details |
|---|---|
| **Project Name** | AMDA v2 |
| **Project Owner, Co-Owner** | Andrea Patelli; No co-owner |
| **Customer** | VW |
| **Visibility** | no |
| **Industry** | Automotive |
| **Topic / Area** | Monitoring and Observability |
| **From** | November 2022 |
| **To** | March 2025 |

---

## Project Insights
> Ongoing DevOps project for custom application monitoring of workloads on an OpenShift-based big data platform. The goal was to improve development and deployment processes for monitoring, alerting, and visualization of metrics and logs, increasing the monitoring team's efficiency. The solution was rolled out to three production applications of the Data Analytics Platform; further rollouts are ongoing or planned.



## Business Needs

#### 1. Increase platform transparency

Create a shared, understandable view of platform stability, bottlenecks, and early anomalies across interacting system components. Monitoring and observability should make technical conditions traceable and help stakeholders identify whether issues are infrastructure-, application-, or process-related.

#### 2. Accelerate incident analysis and response

Improve correlation and consistent structuring of logs, metrics, and events so teams can isolate root causes faster, reconstruct incidents, reduce downtime, improve response times, and coordinate more efficiently.

#### 3. Enable continuous operational improvement

Provide consistent, usable information on stability, availability, performance, error frequency, and recurring anomalies for technical teams and project stakeholders. This supports earlier risk detection, prioritization of measures, and long-term operational stability.



## Provided Services
### Cloud/ onPrem: OnPrem

#### 1. Automated monitoring deployment pipeline

Implemented a CI/CD pipeline for automated deployment of dashboards, alerts, and workloads.

#### 2. Infrastructure-as-Code workspace

Created an Infrastructure-as-Code workspace with Helm packages and Docker images.

#### 3. Custom Trino query monitoring

Developed a custom monitoring tool for Trino queries.

#### 4. Grafana dashboard visualization

Delivered Grafana dashboards for metric visualization with real-time visibility into system health and resource consumption.



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

#### 1. Establish a DevOps structure from scratch

Set up a DevOps structure from the ground up for existing resources that had been created manually.

#### 2. Scale the solution for additional applications

Optimize and refactor the solution to enable onboarding and support for further applications.

#### 3. Balance generic and application-specific requirements

Understand the characteristics of specific applications to deliver a stable solution that is both generic and appropriately tailored.
