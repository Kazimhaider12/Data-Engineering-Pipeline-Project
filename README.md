# 🚀 Weather Data Pipeline Project

An end-to-end Data Engineering Pipeline that extracts live weather data from the Weatherstack API, stores raw data in PostgreSQL, orchestrates workflows using Apache Airflow, transforms data with dbt, and prepares analytics-ready tables for Power BI dashboards.

---

## 📌 Project Architecture

Python → PostgreSQL → Apache Airflow → dbt → Power BI

🐳 Docker is used to containerize the complete environment.

🤖 Codex assisted during development, debugging, and workflow optimization.

---

## ⚡ Project Overview

This project demonstrates how modern data engineering workflows are built using industry-standard tools.

The pipeline performs the following tasks:

* Extracts live weather data from the Weatherstack API
* Stores raw JSON data into PostgreSQL
* Automates workflows using Apache Airflow DAGs
* Cleans and transforms data using dbt models
* Creates analytics-ready tables for reporting
* Connects transformed data to Power BI dashboards

---

# 🛠️ Tech Stack

| Tool           | Purpose                   |
| -------------- | ------------------------- |
| Python         | API Extraction            |
| PostgreSQL     | Raw Data Storage          |
| Apache Airflow | Workflow Orchestration    |
| dbt            | Data Transformation       |
| Docker         | Containerized Environment |
| Power BI       | Dashboard & Reporting     |

---

# 📂 Project Structure

```bash
weather-data-pipeline/
│
├── airflow/
│   ├── dags/
│   └── logs/
│
├── dbt/
│   ├── models/
│   └── profiles/
│
├── scripts/
│   └── extract_weather_data.py
│
├── postgres/
│
├── powerbi/
│
├── docker-compose.yml
├── requirements.txt
└── README.md
```

---

# 🔄 Pipeline Workflow

### 1️⃣ Data Extraction

Python fetches live weather data from the Weatherstack API.

### 2️⃣ Data Storage

Raw JSON response is stored inside PostgreSQL tables.

### 3️⃣ Workflow Orchestration

Apache Airflow schedules and manages the ETL workflow using DAGs.

### 4️⃣ Data Transformation

dbt transforms raw weather data into clean analytical models.

### 5️⃣ Reporting Layer

Power BI connects with transformed tables to create dashboards and insights.

---

# 🚀 Features

✅ End-to-End ETL/ELT Pipeline
✅ API Integration
✅ PostgreSQL Data Warehouse Layer
✅ Airflow DAG Scheduling
✅ dbt Transformations
✅ Dockerized Environment
✅ Power BI Reporting
✅ Production-Style Workflow

---

# 📊 Example Use Cases

* Weather Monitoring Dashboards
* Analytics Reporting
* ETL Workflow Demonstration
* Data Engineering Portfolio Project
* Airflow + dbt Integration Practice

---

# 🐳 Run With Docker

```bash
docker-compose up --build
```

---

# ▶️ Airflow Access

```bash
http://localhost:8080
```

Default Credentials:

```bash
Username: airflow
Password: airflow
```

---

# 📈 Learning Outcomes

This project helped in understanding:

* API data extraction workflows
* PostgreSQL database operations
* Apache Airflow orchestration
* dbt transformations & modeling
* Analytics engineering concepts
* Docker-based deployment
* Building production-style pipelines

---

# 🔥 Final Thoughts

A simple weather API became a complete modern Data Engineering Pipeline.

This project reflects how raw data moves through extraction, storage, orchestration, transformation, and finally becomes business-ready insights.

---

# 📬 Connect With Me

If you liked this project or want to collaborate on Data Engineering / Analytics projects, feel free to connect on LinkedIn 🚀
