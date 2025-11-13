# GCP Logging, Monitoring, and Incident Response Project

Welcome to our organization! We are a team of three students—**Eliza, Ewelina, and Maria**—collaborating on a comprehensive project for our Google Cloud Platform course.

Our mission is to design, implement, and document a robust, production-grade monitoring and observability system using GCP's native tools.

---

## Project Overview

The primary goal of this project is to build a centralized system capable of monitoring applications, logging critical events, and triggering an effective incident response procedure.

### Key Objectives:
* **Infrastructure Setup:** Deploy multiple Compute Engine instances running a sample application (e.g., Nginx).
* **Data Collection:** Install and configure the **GCP Ops Agent** on all instances to collect both logs and metrics.
* **Monitoring & Metrics:** Create custom metrics (e.g., HTTP error rates, specific application metrics) and dashboards in **Cloud Monitoring**.
* **Alerting:** Configure alerting policies for critical events, such as high CPU usage or application errors, with notifications sent to **Email, Slack, and/or Pub/Sub**.
* **Log Analysis:** Export logs to **BigQuery** for long-term storage, trend analysis, and advanced querying.
* **Incident Response:** Develop a formal **Incident Response Plan** detailing procedures for acknowledging, diagnosing, and resolving alerts.

---

## Technology Stack

This project leverages a suite of powerful GCP services:

* **Compute:** Google Compute Engine (GCE)
* **Observability:**
    * Cloud Monitoring
    * Cloud Logging
    * Ops Agent
* **Data & Integration:**
    * BigQuery (for log analysis)
    * Pub/Sub (for event-driven notifications)
* **Security & Access:** Identity and Access Management (IAM)
* **Application:** Nginx (as the sample service)

---

## The Team

Meet the members responsible for bringing this system to life!

| Name | Role(s) | GitHub Profile |
| :--- | :--- | :--- |
| **Maria** |  GCP Project Owner & Developer | [GitHub](https://github.com/mnukui) | 
| **Eliza** | Project Planning & System Design | [GitHub](https://github.com/epetrycka) |
| **Ewelina** | Developer & Team Coordinator | [GitHub](https://github.com/ewemalina) | 

---

## Repositories

You can find all our work, code, and documentation in our project repositories:

* **[gcp-monitoring-project](https://github.com/Level-Up-Team-2025/GCP-Incident-Respond-System)**: Main repository containing infrastructure configurations, Ops Agent settings, and application code.
