# 🐳 Hands-On – Deploying a Multi-Tier Application in Docker Swarm

---

## 📌 Lab Overview

Designed and deployed a **multi-tier web application architecture** using Docker Swarm with an overlay network.

This hands-on demonstrates distributed service deployment, inter-container communication, database integration, and real-time application validation in a clustered environment.

---

## 🎯 Objective

✔ Create an overlay network for inter-service communication  
✔ Deploy web application service in Swarm  
✔ Deploy database (MySQL) service  
✔ Enable communication between application and database  
✔ Validate real-time data persistence  

---

# 🏗 Architecture Components

- Docker Swarm Cluster  
- Overlay Network  
- Web Application Service  
- MySQL Database Service  
- Distributed Container Nodes  

---

# 🧭 Implementation Summary

---

## 🔹 Step 1 – Creating Overlay Network

- Created a distributed overlay network within Docker Swarm
- Enabled cross-node communication between services
- Ensured network isolation and secure container interaction

### Outcome
Cluster-wide virtual network established.

---

## 🔹 Step 2 – Deploying Web Application Service

- Created Swarm service for web application
- Attached service to overlay network
- Exposed necessary port for browser access

### Outcome
Web application successfully deployed across cluster.

---

## 🔹 Step 3 – Deploying Database Service

- Deployed MySQL container as a Swarm service
- Connected database service to overlay network
- Configured environment variables for authentication

### Outcome
Database service integrated within distributed architecture.

---

## 🔹 Step 4 – Database Configuration & Initialization

- Identified node hosting database container
- Accessed database container environment
- Created SQL schema and tables
- Executed database initialization script
- Verified successful table creation

### Outcome
Backend database successfully initialized and operational.

---

## 🔹 Step 5 – Application Validation

- Accessed web application via browser
- Submitted test data through application interface
- Verified data persistence in MySQL table
- Confirmed successful application-to-database communication

### Outcome
Fully functional multi-tier application deployed and validated.

---

# 🧩 Concepts Demonstrated

- Multi-Tier Architecture Design  
- Docker Swarm Overlay Networking  
- Service-to-Service Communication  
- Distributed Database Deployment  
- Containerized Application Integration  
- Data Persistence in Containerized Environments  

---

# 📈 Real-World Use Case

This architecture pattern is commonly used for:

- Scalable web applications  
- Microservices architectures  
- Production-ready container clusters  
- Cloud-native application deployments  
- Distributed backend systems  

---

# 🛠 Skills Demonstrated

- Docker Swarm Orchestration  
- Overlay Network Configuration  
- Multi-Service Deployment  
- MySQL Container Integration  
- Database Initialization & Validation  
- Distributed Application Architecture  

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
