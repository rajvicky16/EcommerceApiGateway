# EcommerceApiGateway

## Overview
EcommerceApiGateway is an API Gateway built using Spring Boot and Spring Cloud Gateway. It serves as a gateway for routing requests to various microservices in an e-commerce application.

## Features
- Routes requests to the `Product Service` for handling product-related operations.
- Supports path-based routing for `/products/**` and `/search/**`.
- Configurable via `application.properties`.

## Prerequisites
- Java 23 or higher
- Maven 3.8 or higher
- Spring Boot 3.4.1
- Spring Cloud Gateway 4.2.0

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/rajvicky16/EcommerceApiGateway.git
cd EcommerceApiGateway
```

 ### Build the Project
 Run the following command to build the project:
 ```bash
 mvn clean install
 ```

 ### Run the Application
You can use the following command to start the application:
 ```bash
 mvn spring-boot:run
 ```
The application will start on port 7070 by default.
