# alura-microservices

## This project is part of the Alura course on Microservices, aiming to demonstrate the development and deployment of microservices architecture using Java and Spring Cloud.

## Overview
The Alura Microservices Project is divided into several modules, each representing a different microservice component. The main modules include:

config-server: Centralized configuration server using Spring Cloud Config.

discovery-server: Service discovery server using Netflix Eureka.

gateway: API Gateway service using Spring Cloud Gateway.

loja: Microservice handling operations related to a store, such as product listing and order creation.

fornecedor: Microservice managing supplier information.

transportador: Microservice handling order delivery and tracking.

## Features
Microservices Architecture: Implemented using Java and Spring Boot, showcasing independent service modules communicating via RESTful APIs.

Service Registration and Discovery: Utilizes Netflix Eureka for service registration and discovery.

Centralized Configuration: Demonstrates centralized configuration management using Spring Cloud Config Server.

API Gateway: Includes an API Gateway built with Spring Cloud Gateway to handle routing and filtering.

Containerization: Docker is used for containerization of individual microservices.

Integration Testing: Includes integration tests to verify interactions between microservices.

## Getting Started
To run the Alura Microservices Project locally, follow these steps:

Clone this repository:

```git clone https://github.com/SantosCristiano/alura-microservices.git```

Navigate into the cloned directory:

```cd alura-microservices```

Build the project using Maven:

```./mvnw clean install```

Start each microservice individually:

```java -jar <microservice-name>/target/<microservice-name>.jar```

Replace <microservice-name> with the name of each microservice module.

Access the services via their respective endpoints (e.g., http://localhost:8080 for Gateway, http://localhost:8761 for Eureka Dashboard).

Contributing
Contributions are welcome! If you find any issues or improvements, feel free to create a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Alura for providing the course material and guidance on microservices architecture.
Netflix and Spring teams for their powerful frameworks used in this project.
