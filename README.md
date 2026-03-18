# Microservices E-Commerce System

## Introduction
This project is a microservices-based e-commerce system built using Spring Boot. It demonstrates how to design and develop a scalable application by separating functionalities into independent services such as user management, product management, order processing, and inventory management.

The project also integrates containerization, CI/CD practices, and cloud deployment using Microsoft Azure.

## Architecture
The system follows a microservices architecture where each service runs independently and communicates via REST APIs.

Main services:
- User Authorization Service  
- Product Service  
- Order Service  
- Inventory Service  

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/Chathuni1012/CTSE-Assignment-01.git
cd CTSE-Assignment-01
```

## Running the Project (Local)

Navigate into each microservice folder and run:

```bash
mvn spring-boot:run
```
Each service will start on its configured port.

## Running with Docker

Navigate into each microservice folder and run:

```bash
docker build -t <service-name> .
docker run -p <port>:<port> <service-name>
```

## Technologies Used
- Java, Spring Boot  
- MongoDB, PostgreSQL  
- Docker  
- Microsoft Azure (Azure Container Apps)  
- GitHub Actions (CI/CD)  
- Terraform (Infrastructure as Code)  

## CI/CD & Deployment
- Automated build and testing using GitHub Actions  
- Docker images built and pushed to Docker Hub  
- Deployment to Azure Container Apps  
- Infrastructure managed using Terraform
