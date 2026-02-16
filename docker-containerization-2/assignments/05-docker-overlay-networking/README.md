# 🌐 Assignment 5 – Docker Overlay Networking & Inter-Container Communication

---

## 📌 Project Overview

Extended the previously created **Docker Swarm Cluster** by implementing an **Overlay Network** and deploying two containers inside it.

Validated secure inter-container communication by enabling containers to ping each other across nodes in the Swarm cluster.

This assignment demonstrates container networking in a distributed production-grade environment.

---

## 🎯 Objectives

✔ Use existing Docker Swarm deployment  
✔ Create an Overlay Network  
✔ Deploy 2 containers inside the overlay network  
✔ Enable cross-container communication  
✔ Validate connectivity using internal networking  

---

## 🏗 Architecture Design

- Docker Swarm Cluster (3 Nodes)  
- Custom Overlay Network  
- 2 Containers deployed as Swarm services  
- Distributed networking across nodes  

Overlay network enables:
- Cross-host container communication  
- Service discovery  
- Secure internal traffic  

---

## ⚙️ Implementation Approach

### 1️⃣ Overlay Network Creation

- Created a custom overlay network within Swarm  
- Enabled multi-host communication  
- Ensured network driver supports distributed services  

---

### 2️⃣ Service Deployment in Overlay Network

- Deployed two containers attached to the overlay network  
- Containers scheduled across different nodes  
- Enabled internal DNS-based resolution  

---

### 3️⃣ Inter-Container Communication Testing

- Accessed container shell  
- Pinged second container using service/container name  
- Verified successful packet transmission  
- Confirmed internal network routing  

---

## 🧪 Networking Validation

✔ Containers resolved each other via service name  
✔ Cross-node connectivity verified  
✔ No external IP required for communication  
✔ Overlay network handled internal routing automatically  

---

## 🔐 Production Relevance

Overlay networks are used in:

- Microservices architecture  
- Multi-host container environments  
- Secure internal service communication  
- Enterprise container orchestration platforms  

This setup simulates:

- Internal service mesh foundation  
- Container-to-container communication  
- Production-grade distributed networking  

---

## 📈 Skills Demonstrated

- Docker Swarm Networking  
- Overlay Network Configuration  
- Service-to-Service Communication  
- Container DNS Resolution  
- Distributed Application Networking  
- DevOps Network Troubleshooting  

---

## 📊 Outcome

Successfully implemented:

- Overlay networking across Swarm cluster  
- Multi-host container communication  
- Internal service discovery  
- Secure distributed container architecture  

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Context

**Module – Docker II**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
