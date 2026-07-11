[← Back to README](../README.md)

# springboot-crud-k8s
https://github.com/voorevamshi/springboot-crud-k8s



### Two-Line Summary

This repository contains a full-stack deployment blueprint that builds a Java Spring Boot CRUD REST API and orchestrates it alongside a MySQL database on a Kubernetes cluster. It leverages optimized multi-stage containerization and declarative Kubernetes manifests to achieve automated scaling, self-healing, and secure environment configuration via ConfigMaps and Secrets.

### Full Summary

The `springboot-crud-k8s` project showcases a complete cloud-native lifecycle for a microservice, bridging application code with automated infrastructure management.

-   **Application Architecture:** A standalone Spring Boot REST API using Spring Data JPA to execute core CRUD (Create, Read, Update, Delete) operations. It is designed to interface with a relational database backend.
    
-   **Container Layer (`Dockerfile`):** Rather than running raw Java, the project utilizes a optimized multi-stage `Dockerfile` that packages the application into a lightweight, isolated container image, making it ready to upload to Docker Hub or an internal registry.
    
-   **Kubernetes Orchestration Layer:** The heart of the repository consists of declarative YAML manifests that map out the infrastructure deployment:
    
    -   **`db-deployment.yaml`:** Manages the lifecycle and storage configurations of the MySQL database instance.
        
    -   **`app-deployment.yaml`:** Spins up highly available replicas of the Spring Boot application, linking them seamlessly to the database service.
        
    -   **State & Security Management:** Utilizes `mysql-configMap.yaml` and `mysql-secrets.yaml` to decouple environments from code. This keeps non-sensitive variables (like database URLs) organized while strictly encrypting sensitive credentials (like root passwords).