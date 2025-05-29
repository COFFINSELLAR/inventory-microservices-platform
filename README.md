# Inventory Microservices Platform

A scalable backend system built using Spring Boot microservices. This project simulates a real-world inventory management architecture with modular services for inventory tracking, order placement, authentication, and notification handling.

## 🔧 Architecture Overview

This platform is composed of the following microservices:

| Service               | Description                                                   | Repository Link |
|-----------------------|---------------------------------------------------------------|-----------------|
| **Inventory Service** | Manages products, stock levels, and inventory updates.        | [inventory-service](https://github.com/COFFINSELLAR/inventory-service) |
| **Order Service**     | Handles order placement, updates, and payment simulation.     | [order-service](https://github.com/COFFINSELLAR/order-service) |
| **Auth Service**      | Provides JWT-based user login, registration, and validation.  | [auth-service](https://github.com/COFFINSELLAR/auth-service) |
| **Notification Service** | Sends notifications via RabbitMQ (e.g., order status alerts). | [notification-service](https://github.com/COFFINSELLAR/notification-service) |

## 🛠 Tech Stack

- **Languages**: Java (Spring Boot), SQL
- **Authentication**: JWT (JSON Web Token)
- **Message Broker**: RabbitMQ
- **Database**: PostgreSQL / MSSQL
- **Caching**: Redis
- **CI/CD**: Jenkins (local pipeline)
- **Containerization**: Docker
- **API Documentation**: Swagger/OpenAPI

## 📦 Features

- JWT-secured APIs for service-to-service communication.
- Inventory synchronization with order flow.
- Asynchronous notifications via RabbitMQ.
- Redis-based caching to reduce DB load.
- Unit + integration tests (JUnit, Mockito).
- Clean layered architecture (Controller → Service → Repo).
- Ready for Docker Compose orchestration (optional).

## 🚀 Getting Started

Each service has its own repository with:
- Setup instructions
- Swagger docs
- Docker config (optional)

You can run them independently or integrate via Docker Compose.

## 📚 Learn More

To explore each service:
- Visit the linked repositories above.
- Check out the Swagger UI for each microservice.

## 👨‍💻 Author

Shivam Rawat  
📧 [shivamr7860@gmail.com](mailto:shivamr7860@gmail.com)  
🔗 [linkedin.com/in/shivam-rawat7860](https://linkedin.com/in/shivam-rawat7860)
