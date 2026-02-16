# 🐳 Assignment 1 – Docker Volume Persistence Implementation

---

## 📌 Project Overview

Implemented **persistent storage management in Docker** by attaching a **Docker Volume** to an existing Apache2 container created in the previous module.

This assignment demonstrates how to:

- Maintain application data outside container lifecycle
- Enable persistent web content storage
- Apply volume mounting for production-ready container setups

---

## 🎯 Objectives

✔ Launch previously created Apache2 container  
✔ Create a Docker Volume  
✔ Mount the volume to `/var/www/html`  
✔ Enable persistent storage for Apache web content  

---

## 🏗 Architecture Components

- Docker Engine  
- Apache2 Container  
- Docker Volume  
- Bind Mount to `/var/www/html`  

---

## ⚙️ Implementation Summary

### 1️⃣ Container Deployment

- Reused previously built Apache2 Docker image
- Launched container with port mapping
- Verified Apache service accessibility via browser

### 2️⃣ Docker Volume Creation

- Created a named Docker volume
- Mounted the volume to `/var/www/html`
- Ensured data persistence independent of container lifecycle

### 3️⃣ Persistence Validation

- Modified web content inside container
- Restarted container
- Verified that content persisted after container restart

---

## 🔐 Production Significance

Using Docker volumes enables:

- Persistent web content storage
- Data durability during container restart
- Safe container upgrades without data loss
- Separation of application layer and data layer

---

## 📈 Key Learning Outcomes

- Docker Volume creation & management  
- Data persistence architecture in containers  
- Container lifecycle understanding  
- Web server content management in Docker  
- Production-ready container configuration  

---

## 🛠 Skills Demonstrated

- Docker Volume Management  
- Container Data Persistence  
- Apache2 Container Configuration  
- Linux File System Mounting  
- DevOps Environment Preparation  

---

## 🏢 Real-World Application

This setup is commonly used in:

- Web server container deployments  
- CMS hosting environments  
- Microservices with persistent data  
- CI/CD containerized applications  
- Stateful container workloads  

---

## 📊 Outcome

Successfully implemented persistent storage using Docker volumes, ensuring:

- Web content survives container restarts  
- Separation of compute and storage  
- Production-aligned container deployment  

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Context

**Module – Docker II**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
