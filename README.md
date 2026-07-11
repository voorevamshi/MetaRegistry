# MetaRegistry

## JAVA
[product-service-loadtest](docs/product-service-loadtest/README.md)
It contains  automated performance and load testing scripts designed to evaluate the scalability, throughput, and reliability of a "product microservice" under high-traffic simulation. It typically utilizes modern performance testing tools to identify system bottlenecks and measure API latency before production deployments.

[order-notification-lambda](docs/order-notification-lambda/README.md)
It contains an AWS Lambda function designed to automatically process order events and trigger notifications (such as emails, SMS, or Slack alerts). It acts as a serverless event consumer that typically integrates with managed message queues like Amazon SQS or event streams like Amazon SNS/EventBridge.

[spring-order-service](docs/spring-order-service/README.md)	
It contains a backend microservice built with Spring Boot that is responsible for managing the entire lifecycle of customer orders. It handles essential transactional workflows including order creation, status updates, and orchestration with inventory, payment, and notification systems.	

[springboot-crud-k8s](docs/springboot-crud-k8s/README.md)		
It contains a full-stack deployment blueprint that builds a Java Spring Boot CRUD REST API and orchestrates it alongside a MySQL database on a Kubernetes cluster. It leverages optimized multi-stage containerization and declarative Kubernetes manifests to achieve automated scaling, self-healing, and secure environment configuration via ConfigMaps and Secrets.	

[inventory-service](docs/inventory-service/README.md)		
It contains a dedicated microservice designed to track, manage, and audit real-time product stock levels across an e-commerce ecosystem. It exposes critical endpoints for checking stock availability during browsing and handles inventory reservations to prevent overselling during checkout workflows.

[product-service](docs/product-service/README.md)		
It contains a core Java and Spring Boot backend microservice dedicated to managing the e-commerce application's catalog item data. It acts as the single source of truth for creating, retrieving, and updating product information, descriptions, categories, and prices.

[DesignPatterns](docs/DesignPatterns/README.md)		
It serves as a practical blueprint and reference guide demonstrating the implementation of classic Gang of Four (GoF) design patterns using Java. It provides clean, decoupled code examples across creational, structural, and behavioral design paradigms to promote maintainable and scalable software architecture.

[rest-common](docs/rest-common/README.md)	
It likely functions as a shared library or "common" module containing reusable utilities, base classes, and configuration logic for RESTful APIs. It is designed to standardize error handling, response formatting, and authentication patterns across multiple microservices within an application ecosystem.	

