# Smart Inventory Management System: IoT & Predictive Data Analytics

This repository features the comprehensive project planning, architecture design, and risk modeling framework for an **IoT-driven Smart Inventory Management System**. Developed as a final group project for Istanbul Medipol University's Project Management course (Spring 2022-2023).

The project bridges the gap between hardware tracking (IoT sensors/RFID) and software execution by embedding **Data Science and Predictive Analytics** methodologies into core supply chain workflows.

---

## 📊 Data Science & Data Analytics Highlights

While the project encompasses full-lifecycle management, it is structurally engineered around data-driven decisions:
* **Predictive Demand Forecasting:** Leverages historical sales data and statistical trend analysis to forecast item consumption, shifting inventory management from reactive to proactive.
* **Automated Data-Driven Replenishment:** Real-time stream processing of inventory thresholds triggers automated vendor notifications, reducing manual entry errors and maintaining optimal stock levels.
* **Statistical Risk Modeling:** Includes a quantitative and qualitative Risk Severity Matrix (5x5 Likelihood vs. Impact Assessment) to mathematically classify and mitigate technical, software, and data integrity vulnerabilities.
* **Data Integration & Schema Architecture:** Designed to seamlessly ingest large data volumes from distributed network environments (IoT Gateways) into centralized relational/structural databases, maintaining strict transactional consistency (no database updates on failed pipelines).

---

## 🗺️ System Architecture & Work Breakdown Structure (WBS)

The project executed a strict **90-day pipeline** with an **85% completion rate** as of late May 2023, effectively operating within the allocated budgetary and scheduling baselines.

### Core Project Phases:
1. **Project Preparation & Budgeting**
2. **Business Analysis & Requirements Gathering** (Use case modeling & market research)
3. **Design & Architecture** (Database schema design, UI/UX frontend wireframing, and network infrastructure)
4. **Development & System Integration** (Backend logic, IoT sensor stream integration, and Unit/UAT testing)
5. **Deployment & Support**

---

## ⚠️ Data Governance & Risk Assessment Framework

A major milestone of this project was engineering a robust **Risk Breakdown Structure (RBS)**. Data quality, real-time synchronization latency, and cybersecurity vectors were analyzed.

| Risk Event | Category | Likelihood (1-5) | Impact (1-5) | Data Mitigation Strategy |
| :--- | :--- | :---: | :---: | :--- |
| **IoT Connectivity Issues** | Technology | 5 | 3 | Deploy redundant gateways, implement edge-caching to avoid data loss during intermittent outages. |
| **Software Dev Risks** | Technical | 4 | 5 | Continuous continuous-integration testing, thorough schema validation. |
| **Data Quality / Security** | Operational | 5 | 2 | End-to-end data encryption (AES), RBAC (Role-Based Access Control), and firewall protection. |


