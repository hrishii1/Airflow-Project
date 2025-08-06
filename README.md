# Airflow-Project
# 📚 Amazon Books ETL with Airflow, Docker, and Postgres

This project is a beginner-friendly example demonstrating how to use **Apache Airflow** for building an ETL (Extract, Transform, Load) pipeline. It fetches book data from Amazon (mocked/scraped), transforms it using Python, and stores the cleaned data into a **PostgreSQL** database — all orchestrated using **Dockerized Airflow**.

## 🛠️ Tech Stack

- **Apache Airflow** (2.9.2)
- **Docker & Docker Compose**
- **PostgreSQL**
- **Python 3**
- **Pandas** for data cleaning

---

## 🚀 Project Structure

```bash
.
├── dags/
│   └── amazon_books_dag.py       # Main Airflow DAG
├── docker-compose.yaml           # Docker setup for Airflow & Postgres
├── requirements.txt              # Python dependencies
└── README.md                     # This file
