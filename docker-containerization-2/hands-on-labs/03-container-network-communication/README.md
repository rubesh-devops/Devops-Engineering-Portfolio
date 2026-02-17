# 🐳 Hands-On – Linking Two Containers & Inter-Container Communication

---

## 📌 Lab Overview

Implemented container-level networking by launching two Docker containers and enabling communication between them using container networking concepts.

This hands-on demonstrates internal container communication and validation using ICMP (ping) between isolated runtime environments.

---

## 🎯 Objective

✔ Launch two Ubuntu-based Docker containers  
✔ Access container shell environment  
✔ Install networking utilities  
✔ Validate inter-container communication  
✔ Demonstrate container network isolation and connectivity  

---

# 🏗 Implementation Summary

---

## 🔹 Step 1 – Deploying Two Containers

- Created and launched two independent Docker containers:
  - **container1**
  - **container2**
- Used Ubuntu base image for both
- Ensured both containers were running simultaneously

### Outcome
Two isolated runtime environments successfully provisioned.

---

## 🔹 Step 2 – Accessing Container Environment

- Entered interactive shell inside **container2**
- Updated package repositories to prepare for tool installation

### Outcome
Container ready for networking utility configuration.

---

## 🔹 Step 3 – Installing Networking Utility

- Installed ping/ICMP utility inside container2
- Prepared container for connectivity testing

### Outcome
Networking tools successfully configured.

---

## 🔹 Step 4 – Validating Inter-Container Communication

- Initiated ping request from **container2 → container1**
- Verified successful response packets

### Outcome
Confirmed successful container-to-container communication.

---

# 🌐 Networking Concepts Demonstrated

- Docker Container Networking
- Internal Name Resolution
- Inter-Container Communication
- ICMP Connectivity Testing
- Container Isolation vs Network Reachability
- Linux Networking inside Containers

---

# 📈 Real-World Use Case

This architecture is commonly used in:

- Microservices communication testing
- Backend service-to-service communication
- Internal API connectivity validation
- Overlay network validation in Swarm/Kubernetes
- Container-based distributed applications

---

# 🛠 Skills Demonstrated

- Docker Container Deployment
- Container Shell Access
- Runtime Networking Configuration
- Service Communication Validation
- Linux Networking Fundamentals
- Troubleshooting Container Connectivity

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
