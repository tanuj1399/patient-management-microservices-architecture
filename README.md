# patient-management-microservices-architecture
This project is a microservices-based Patient Management System that demonstrates modern distributed architecture using Spring Boot, gRPC, Kafka, PostgreSQL, Docker, and JWT authentication. It supports both synchronous (gRPC) and asynchronous (Kafka) communication patterns.

Features :

Microservices-based architecture (loose coupling & scalability).
Synchronous Communication: gRPC between services for fast inter-service RPC calls.
Asynchronous Communication: Kafka event-driven messaging for notifications & background processing.
PostgreSQL as the database for persistence.
Dockerized Services for easy local setup and deployment.
API Gateway to expose REST endpoints to clients securely.
JWT Authentication for securing APIs and inter-service communication.
