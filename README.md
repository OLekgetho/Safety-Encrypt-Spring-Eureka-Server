# Safety Encrypt – Eureka Server

This repository contains the Service Registry (Eureka Server) for the Safety Encrypt microservices architecture.

## 📌 Overview

The Eureka Server acts as the central service discovery mechanism for the Safety Encrypt platform.

In a microservices architecture, services need a way to locate and communicate with each other dynamically. Instead of hardcoding service URLs, each microservice registers itself with the Eureka Server when it starts.

Other services can then discover and communicate with them through the registry.
