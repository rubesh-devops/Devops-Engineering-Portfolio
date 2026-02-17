# 🐳 Hands-On – Initializing and Managing a Docker Swarm Cluster

---

## 📌 Lab Overview

Configured and managed a **Docker Swarm cluster** to understand distributed container orchestration across multiple nodes.

This hands-on demonstrates swarm initialization, worker node joining, cluster validation, and swarm lifecycle management.

---

## 🎯 Objective

✔ Initialize Docker Swarm on manager node  
✔ Join worker node to the cluster  
✔ Verify cluster node status  
✔ Understand swarm join tokens  
✔ Demonstrate node removal and cluster teardown  

---

# 🏗 Implementation Summary

---

## 🔹 Step 1 – Swarm Initialization (Manager Node)

- Initialized Docker Swarm on the primary node
- Generated secure join token for worker nodes
- Promoted node automatically as **Swarm Manager**

### Outcome
Swarm cluster successfully created with one manager node.

---

## 🔹 Step 2 – Joining Worker Node to Swarm

- Started worker node session
- Used manager-generated join token
- Successfully joined worker node to the swarm cluster

### Outcome
Cluster expanded to include manager and worker node.

---

## 🔹 Step 3 – Cluster Validation

- Verified node list from manager node
- Confirmed both nodes were in **Ready state**
- Observed role distinction (Manager / Worker)

### Outcome
Swarm cluster functioning correctly with active node membership.

---

## 🔹 Step 4 – Worker Node Removal

- Executed swarm leave operation from worker node
- Validated node removal from manager perspective

### Outcome
Cluster reflected worker node status change accurately.

---

## 🔹 Step 5 – Manager Node Leave & Swarm Teardown

- Executed leave operation on manager node
- Dissolved swarm cluster

### Outcome
Swarm cluster cleanly terminated.

---

# 🧩 Concepts Demonstrated

- Docker Swarm Architecture  
- Manager vs Worker Node Roles  
- Secure Join Tokens  
- Cluster Node Management  
- Distributed Container Orchestration  
- Swarm Lifecycle Operations  

---

# 📈 Real-World Use Case

Docker Swarm is used for:

- Multi-node container orchestration  
- High availability container deployments  
- Service replication  
- Distributed application management  
- Production-ready container clusters  

---

# 🛠 Skills Demonstrated

- Swarm Cluster Initialization  
- Node Join & Removal Management  
- Distributed Container Orchestration  
- Infrastructure Validation  
- Container Cluster Lifecycle Handling  

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
