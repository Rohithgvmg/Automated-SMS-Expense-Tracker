# Automated-SMS-Expense-Tracker
An automated expense management platform that extracts financial transactions from bank SMS messages, converts them into structured expense records, and provides centralized expense tracking.
Tracks transactions made across UPI apps in common place using bank SMS messages. This helps in user not to juggle between apps whether money has been received or not.
 
This is built using java spring boot as backend framework and microservices architecture. Kafka is used for inter microservice communication. Entire infrastructure is deployed on aws following scalable, highly available and secure principles using aws cdk. frontend is react native mobile application. Database used is MySQL.

# Architecture

## Data Flow
./assets/Data_flow.png

## System Architecture
./assets/System_architecture.png

# Technology Stack

Backend: Java, Spring Boot

Frontend: React Native

Database: MySQL

Messaging: Apache Kafka (inter microservices), HTTP (Client - Server)

API Gateway: Kong

Infrastructure: AWS, Docker, AWS CDK

Authentication: JWT (Access & Refresh Tokens)

