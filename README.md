# Config Server for Operationly

## Overview

The **Config Server** is a centralized configuration management service used to **externalize and manage configuration properties** for all microservices across environments.

It is built using **Spring Boot** and **Spring Cloud Config Server**, enabling dynamic, consistent, and environment-specific configuration without redeploying services.

---

## Why Config Server?

In a microservices architecture:

- Each service has multiple environment configurations
- Configuration changes should not require redeployment
- Sensitive properties must be managed securely
- Consistency across services is critical

The Config Server solves these challenges by:
- Centralizing all configuration in one place
- Supporting environment-specific configurations
- Allowing dynamic refresh of properties
- Integrating with Git-based version control

---

## Key Responsibilities

- Acts as a **central configuration provider**
- Serves configuration files from a **Git repository**
- Supports **profiles** (dev, qa, prod, etc.)
- Enables **runtime configuration refresh**
- Ensures consistent configuration across services

---

## Tech Stack

- **Java 21**
- **Spring Boot**
- **Spring Cloud Config Server**
- **Git (Configuration Repository)**
- **Maven**
- **Docker (optional)**

---
