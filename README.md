# Kafka Producer with Schema Registry & MongoDB Sink Connector

## Overview
This project includes a Kafka **Producer** that generates random shipment data and publishes it to a Kafka topic. The data is validated using **Schema Registry**, and a **Confluent MongoDB Sink Connector** is used to push the streamed data into **MongoDB**. Finally, a real-time dashboard is created in **MongoDB** to visualize the data.

## **Project Flow**
1. **Kafka Producer**: Generates random shipment data and publishes it to a Kafka topic.
2. **Schema Registry**: Ensures the produced data follows a predefined schema.
3. **MongoDB Sink Connector**: Captures data from Kafka and writes it to MongoDB.
4. **MongoDB Real-Time Dashboard**: Displays real-time shipment insights.

## **Tech Stack**
- **Apache Kafka** (Message Broker)
- **Confluent Schema Registry** (Schema Validation)
- **Confluent MongoDB Sink Connector** (Kafka to MongoDB Integration)
- **MongoDB** (Storage & Real-Time Dashboard)
- **Python** (Kafka Producer Implementation)