# 🐳 Assignment 4 – Docker Swarm Cluster & Service Replication

---

## 📌 Project Overview

Designed and deployed a **Docker Swarm Cluster** with 3 nodes and implemented container orchestration by deploying an Apache service with 4 replicas.

This assignment demonstrates distributed container management, service scaling, and high availability using Docker Swarm.

---

## 🎯 Objectives

✔ Create a Docker Swarm cluster with 3 nodes  
✔ Configure manager and worker nodes  
✔ Deploy Apache container as a Swarm service  
✔ Scale service to 4 replicas  
✔ Validate service distribution across cluster  

---

## 🏗 Architecture Design

- 1 Manager Node  
- 2 Worker Nodes  
- Apache container deployed as a Swarm service  
- 4 Replicas distributed across cluster  
- Built-in Swarm load balancing  

---

## ⚙️ Implementation Approach

### 1️⃣ Swarm Cluster Setup

- Initialized Docker Swarm on Manager node  
- Generated join token  
- Added 2 worker nodes to the cluster  
- Verified cluster membership  

---

### 2️⃣ Service Deployment

- Created Apache service inside Swarm  
- Configured desired replica count = 4  
- Enabled port exposure for external access  

Swarm automatically:
- Scheduled containers across nodes  
- Balanced workload  
- Ensured availability  

---

### 3️⃣ Service Scaling & Validation

- Verified 4 running replicas  
- Confirmed containers distributed across nodes  
- Validated Apache page via browser  

---

## 🧪 Cluster Validation

- Checked node status  
- Verified service replica count  
- Confirmed automatic container placement  
- Accessed Apache page successfully  

---

## 🔐 Production Relevance

This setup simulates:

- High Availability architecture  
- Container clustering  
- Distributed application hosting  
- Basic container orchestration  
- Fault-tolerant deployment  

If one node fails:
- Swarm automatically reschedules containers  
- Maintains desired state  

---

## 📈 Skills Demonstrated

- Docker Swarm Initialization  
- Cluster Management  
- Service-Based Deployment  
- Replica Scaling  
- Container Scheduling  
- High Availability Architecture  
- Load Distribution  

---

## 📊 Outcome

Successfully deployed:

- 3-Node Docker Swarm Cluster  
- Apache service with 4 replicas  
- Automatic container orchestration  
- Production-like distributed architecture  

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Context

**Module – Docker II**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
