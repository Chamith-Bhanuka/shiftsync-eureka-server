# ShiftSync — Netflix Eureka Service Discovery

**Student Name:** Chamith Bhanuka Widanapathirana  
**Student ID / Number:** 241711051  
**Slack Handle:** Chamith Bhanuka  
**GCP Project ID:** project-a58ee7a4-4913-4af2-a6d  
**Course:** ITS 2130 — Enterprise Cloud Architecture  

---

## Description

Service registry and discovery server for the ShiftSync microservices platform powered by Spring Cloud Netflix Eureka. Dynamically tracks, monitors health, and registers microservice instances across Compute Engine Managed Instance Groups (MIGs).

---

## Key Responsibilities

- **Service Registry**: Maintains active instance records for `SCHEDULING-SERVICE`, `NOTIFICATION-SERVICE`, and `CREDENTIAL-SERVICE`.
- **High Availability & Health Auditing**: Performs automatic heartbeat detection and deregistrations for failing nodes.
- **Client-Side Load Balancing**: Enables Spring Cloud Gateway and inter-service Feign/HTTP clients to load-balance traffic across multiple service instances.

---

## Technology Stack

- Java 25
- Spring Boot 3.x
- Spring Cloud Netflix Eureka Server
