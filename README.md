# Spring Boot API Gateway Sample Application

This repository contains a sample Spring Boot API Gateway application that demonstrates how to create an API Gateway using Spring Cloud Gateway.

## Services Using API Gateway

The following microservices are utilizing the API Gateway, with configurations added programmatically:

- [Department Microservice](https://github.com/sagarwaghunde/springboot-microservice-department)
- [Employee Microservice](https://github.com/sagarwaghunde/springboot-microservice-employee)

## Prerequisites

- Java 8 or higher
- Maven
- Spring Boot

## Getting Started

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/sagarwaghunde/api-gateway.git
2. Navigate to the project directory:
   ```bash
   cd api-gateway
3. Build the project using Maven:
   ```bash
   mvn clean install
4. Run the API Gateway application:
   ```bash
   mvn spring-boot:run
