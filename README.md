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

[rest-client](docs/rest-client/README.md)	
It contains a dedicated Java utility or shared component designed to simplify and standardize synchronous HTTP communication between microservices. It wraps a modern Java HTTP client (such as Spring WebClient or RestClient) to provide robust, reusable configurations for timeouts, error recovery, and header propagation.


[memory-leak-prometheus](docs/memory-leak-prometheus/README.md)	
It contains a specialized diagnostic application and configuration testbed designed to simulate, monitor, and troubleshoot application memory leaks using Prometheus and Grafana. It serves as a practical blueprint for setting up real-time alerting rules and visualization dashboards to catch Out-of-Memory (OOM) boundary threats before they crash containerized workloads.


[ecommerce-app](docs/ecommerce-app/README.md)
It serves as a centralized orchestrator or reference workspace for an e-commerce platform built on a distributed microservices architecture. It ties together domain-specific services like ordering, product catalog, and inventory, providing a single ecosystem for local development and cloud deployment.