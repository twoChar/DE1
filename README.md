# Realtime Data Streaming Pipeline

This project demonstrates how to build a real-time data pipeline from scratch using Apache Airflow, Kafka, Spark, and Cassandra — all containerized with Docker. It simulates streaming user data, processes it, and stores the output in a scalable database.

## Overview

- **Data Source**: Random user data from `randomuser.me` API  
- **Airflow**: Ingests and loads data into PostgreSQL  
- **Kafka + Zookeeper**: Streams data from PostgreSQL  
- **Spark**: Processes streaming data  
- **Cassandra**: Stores the final output  
- **Docker**: Runs everything in isolated containers

## Technologies

- Apache Airflow  
- Apache Kafka & Zookeeper  
- Apache Spark  
- PostgreSQL  
- Cassandra  
- Docker  
- Python


