# 🐳 Assignment 3 – Multi-Container Deployment using Docker Compose

---

## 📌 Project Overview

Designed and deployed a multi-container architecture using **Docker Compose**, where 5 custom Apache containers serve 5 different default pages on separate ports.

This assignment demonstrates container orchestration, service definition, and multi-port exposure using Docker Compose.

---

## 🎯 Objectives

✔ Create 5 custom containers  
✔ Configure 5 different default HTML pages  
✔ Use Docker Compose for orchestration  
✔ Expose services on ports 81, 82, 83, 84, 85  
✔ Validate service accessibility via browser  

---

## 🏗 Architecture Design

- 5 Custom Apache Containers  
- Each container serves a unique default page  
- Docker Compose manages service lifecycle  
- Ports mapped as follows:

| Container | Port Mapping |
|-----------|-------------|
| Container 1 | 81 |
| Container 2 | 82 |
| Container 3 | 83 |
| Container 4 | 84 |
| Container 5 | 85 |

---

## ⚙️ Implementation Approach

### 1️⃣ Created 5 Custom Docker Images
- Based on Ubuntu/Apache base image  
- Modified default `index.html` for each container  
- Tagged images uniquely  

---

### 2️⃣ Created Docker Compose Configuration
- Defined 5 services  
- Each service mapped to:
  - Unique container name  
  - Specific image  
  - Dedicated port mapping  
- Centralized orchestration via `docker-compose.yml`

---

### 3️⃣ Deployed Using Docker Compose

Deployment performed using Docker Compose, which:

- Built and launched all containers
- Managed networking automatically
- Exposed services on required ports

---

## 🧪 Validation

Verified each container by accessing:

- http://server-ip:81  
- http://server-ip:82  
- http://server-ip:83  
- http://server-ip:84  
- http://server-ip:85  

Each port displayed a unique default page confirming correct deployment.

---

## 🔐 Production Relevance

This architecture simulates:

- Multi-service application hosting  
- Microservice-based deployments  
- Scalable container orchestration  
- Simplified infrastructure management  

Docker Compose allows:

- Infrastructure as Code for containers  
- Single-command deployment  
- Easy scaling & modification  

---

## 📈 Skills Demonstrated

- Docker Image Customization  
- Multi-Container Deployment  
- Docker Compose Orchestration  
- Port Mapping & Networking  
- Web Server Containerization  
- Service Isolation  

---

## 📊 Outcome

Successfully deployed 5 independent web services using Docker Compose with:

- Clean orchestration  
- Structured configuration  
- Port-based service separation  
- Production-aligned architecture design  

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Context

**Module – Docker II**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
