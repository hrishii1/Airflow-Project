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

## Steps: 
## Initialize Airflow with docker compose up airflow-init:
<img width="960" height="600" alt="Airflow-1" src="https://github.com/user-attachments/assets/5f7ab905-fffd-4733-bc1d-bdaf710ff00c" />

## Once initialized the docker container will start running:
<img width="955" height="520" alt="airflow-2" src="https://github.com/user-attachments/assets/9440ddac-b2b6-4613-83e3-40c7995bfb49" />

## Airflow is being initialized: 
<img width="956" height="555" alt="airflow-3" src="https://github.com/user-attachments/assets/5e1e8573-b6ff-4757-b4fe-4862d6371683" />

## Once done the Webserver shows the Dags and other operations involved in the Airflow. Can be accessed through the localhost:8080: 
<img width="949" height="469" alt="airflow-dags" src="https://github.com/user-attachments/assets/f4782bd0-c2c4-4957-83f0-a82b79360f9c" />

## This is the Pgadmin which can be accessed through localhost:5050
<img width="947" height="462" alt="airflow-5" src="https://github.com/user-attachments/assets/7074500c-7041-4c98-874a-cebdb32ab8fb" />

## Displays the containers in the docker:
<img width="955" height="562" alt="airflow-6" src="https://github.com/user-attachments/assets/be12ba8e-0266-4dd1-8e5a-296da5348619" />

## Dashboard of the PgAdmin UI:
<img width="950" height="519" alt="airflow-7" src="https://github.com/user-attachments/assets/bd793a29-0fd8-4a15-ae62-54e6e6380087" />

## Connection has to be made to connect the airflow with the database: 
<img width="948" height="472" alt="airflow-8" src="https://github.com/user-attachments/assets/232f672a-463d-465b-bd58-08c9a9350de0" />

## Displays the connection made through the .py code:
<img width="955" height="475" alt="airflow-9" src="https://github.com/user-attachments/assets/35400be4-e5eb-428e-a18f-736c3b47c627" />

## Displays the ETL process in the graph: 
<img width="948" height="468" alt="airflow-10" src="https://github.com/user-attachments/assets/73c57d82-97ee-4474-97f0-8b26e06a6758" />


