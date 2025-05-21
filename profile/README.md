# 🍔 Welcome to Tech Snack!

This organization centralizes the projects developed during the Tech Challenge of the Software Architecture postgraduate
program at FIAP. Below, you'll find an overview of the projects that make up our fast-food self-service system.

## 📂 Projects

### 1. fastfood-infra
Infrastructure provisioning, necessary for the fast-food self-service system using Terraform and AWS cloud services.

- **Terraform Modules:** Cognito, Compute (EKS), Database (RDS), Gateway (API Gateway), Lambda
- **Objective:** Create a scalable and automated infrastructure to support the ordering system

[More details](https://github.com/tech-snack-fiap-soat-tech-challenge/fastfood-infra)

### 2. fastfood-order-service
Microservice responsible for managing the order lifecycle, from creation to completion.

- **Technologies:** NestJS, TypeScript, and DynamoDB
- **Features:** Order creation, status tracking, order history management

[More details](https://github.com/tech-snack-fiap-soat-tech-challenge/fastfood-order-service)

### 3. fastfood-checkout-service
Microservice that handles payment processing and checkout flow for orders.

- **Technologies:** NestJS, TypeScript, TypeORM, and PostgreSQL
- **Features:** Payment processing, integration with payment gateways, transaction management

[More details](https://github.com/tech-snack-fiap-soat-tech-challenge/fastfood-checkout-service)

### 4. fastfood-customer-service
Microservice for customer management and user profile operations.

- **Technologies:** NestJS, TypeScript, TypeORM, and PostgreSQL
- **Features:** Customer registration, profile management, customer loyalty programs

[More details](https://github.com/tech-snack-fiap-soat-tech-challenge/fastfood-customer-service)

### 5. fastfood-product-service
Microservice that manages the product catalog, categories, and inventory.

- **Technologies:** NestJS, TypeScript, TypeORM, and PostgreSQL
- **Features:** Product catalog management, inventory tracking, pricing management

[More details](https://github.com/tech-snack-fiap-soat-tech-challenge/fastfood-product-service)

### 6. fastfood-auth-lambda
Authentication Lambda for the fast-food ordering system. This project manages user registration and login 
flow using Amazon Cognito and CPF as a unique identifier.

- **Technologies:** Node.js, Amazon Cognito, AWS Lambda
- **Features:** User registration and login via CPF, JWT token generation

[More details](https://github.com/tech-snack-fiap-soat-tech-challenge/fastfood-auth-lambda)

### 7. fastfood-app
Initial monolithic application for the fast-food self-service system, designed to improve efficiency and customer satisfaction.

- **Technologies:** Node.js, Docker, PostgreSQL
- **Features:** Order management, QR Code payment, administrative panel

[More details](https://github.com/tech-snack-fiap-soat-tech-challenge/fastfood-app)

## 🏗️ Architecture

Our project follows a microservice architecture pattern, with each service responsible for a specific domain within the fast-food self-service ecosystem. 
All services are deployed on AWS using infrastructure-as-code principles through Terraform.

## 🚀 Getting Started

To run the entire project locally, please refer to the instructions in each repository's individual README file.