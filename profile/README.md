# 💧 Drucom

## 🎯 Mission

Data-Driven Applications for the Drupal Community. **Drucom** serves as the centralized hub for modern **Data Engineering** and **MLOps** projects dedicated to extracting value and insights from Drupal community data (e.g., issue queues, usage statistics). Our core mission is to transform raw community data into reliable, actionable intelligence using best-in-class, production-grade architectures.


## ⚙️ Tech Stack

Every project in the `Drucom` organization is built on a consistent, scalable MLOps foundation. This consistency ensures rapid development and reliable deployment.

### Central Data Hub
The single source of truth for all data, metrics, and models.
* **Data Warehouse:** **Snowflake**
* **Infrastructure:** Defined and managed by **Terraform** (IaC).

### Data & ML Flow Components
The functional components of our MLOps pipelines are strictly separated:
* **Data Ingestion:** Pipelines are orchestrated by **Apache Airflow**, use **dbt** for ELT/transformations, and enforce quality with **Great Expectations**.
* **ML/Analytics:** Model development and experiment tracking are managed with **MLflow**, and real-time serving is done via **FastAPI** microservices.
* **Monitoring:** Visualization of pipeline health, data quality, and model performance is handled by **Apache Superset**.


## 📚 Projects

### 🎏 Drudis

**Drudis (Duplicate Issue Detection System)** is a full-stack MLOps pipeline designed to automatically identify and flag duplicate issue reports using Natural Language Processing (NLP).

* **Goal:** Optimize developer time by ensuring a cleaner, organized issue queue.
* **Status:** Work in progress

**Drudis repositories**:

* **`drucom/drudis-infra`** (Infrastructure as Code - IaC): Manages all cloud resources and the **Snowflake** data hub. \[Link to IaC Repo]
* **`drucom/drudis-ingestion`** (Data Ingestion & Orchestration): Contains **Airflow**, **dbt**, and **Great Expectations** code for the ETL/ELT pipeline. \[Link to Ingestion Repo]
* **`drucom/drudis-training`** (ML Model Development & Tracking): Manages model training, feature engineering, and **MLflow** experiment tracking. \[Link to ML Training Repo]
* **`drucom/drudis-api`** (MLOps Serving & Deployment): The **FastAPI** service that serves predictions and logs real-time metrics. \[Link to API Repo]
* **`drucom/drudis-monitoring`** (Business Intelligence & Monitoring): The configuration for the **Apache Superset** dashboard. \[Link to Monitoring Repo]


## 🌟 Skills Showcase

This project demonstrates expertise across the modern data and ML ecosystem:

* **Data Engineering:** Snowflake, Airflow, dbt, Great Expectations
* **MLOps & Serving:** MLflow, FastAPI, Docker
* **Infrastructure:** Terraform (IaC), AWS/GCP/Azure
* **Analytics & BI:** Apache Superset, SQL


## 🤝 Contributing

We welcome collaboration on new data-driven applications for the Drupal community. Please refer to the **`CONTRIBUTING.md`** file for setup instructions and code standards before submitting any Pull Requests.