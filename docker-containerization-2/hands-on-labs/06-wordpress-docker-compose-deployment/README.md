# 🐳 Hands-On – Deploying WordPress using Docker Compose

---

## 📌 Lab Overview

Deployed a **multi-container WordPress application** using Docker Compose, integrating a web server and database service in a containerized environment.

This hands-on demonstrates real-world multi-tier application deployment using Infrastructure as Code principles.

---

## 🎯 Objective

✔ Create a dedicated WordPress deployment directory  
✔ Define WordPress and Database services using Docker Compose  
✔ Deploy interconnected containers  
✔ Validate WordPress application accessibility  

---

# 🏗 Implementation Summary

---

## 🔹 Step 1 – Project Directory Setup

- Created a structured project directory for WordPress deployment
- Ensured isolated and organized Compose environment

### Outcome
Clean workspace prepared for multi-container deployment.

---

## 🔹 Step 2 – Defining Multi-Container Architecture

- Created `docker-compose.yml` configuration file
- Defined:
  - WordPress service
  - Database service (MySQL)
- Configured environment variables
- Mapped required ports
- Established service dependencies
- Enabled persistent storage through volumes

### Outcome
Fully defined multi-tier application using YAML configuration.

---

## 🔹 Step 3 – Deploying Application Stack

- Executed Docker Compose build and deployment process
- Automatically provisioned:
  - WordPress container
  - Database container
- Established internal networking between services

### Outcome
WordPress and database services successfully orchestrated together.

---

## 🔹 Step 4 – Deployment Verification

- Confirmed both containers were running
- Accessed WordPress via browser using exposed port
- Validated successful web application initialization

### Outcome
Fully functional containerized WordPress application deployed.

---

# 🧩 Architecture Components

- Docker Compose
- WordPress Container
- MySQL Database Container
- Docker Volumes (Persistent Storage)
- Container Networking

---

# 📈 Real-World Use Case

This architecture is widely used for:

- CMS deployments
- Rapid application prototyping
- Multi-tier web applications
- Development & staging environments
- Cloud-native WordPress hosting

---

# 🛠 Skills Demonstrated

- Multi-Container Orchestration
- Docker Compose Architecture
- Service Dependency Management
- Container Networking
- Persistent Storage Configuration
- Infrastructure as Code Implementation

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 📚 Module & Course Reference

**Module 10 – Docker II**  
**Docker Course**  
Part of **DevOps Architect Master’s Program – Intellipaat**

---
