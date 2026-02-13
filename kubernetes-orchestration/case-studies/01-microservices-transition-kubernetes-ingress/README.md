# 📂 Case Study – Microservices Transition & Kubernetes Ingress-Based Deployment

---

## 📌 Business Scenario

Joined **Ventura Software** as a DevOps Lead Engineer during a strategic architectural shift from **Monolithic Architecture** to **Microservices Architecture**.

The newly appointed CTO mandated modernization of the infrastructure stack to:

- Improve scalability  
- Enable independent service deployment  
- Support container-native architecture  
- Prepare for production-grade orchestration  

As part of this transition, a test application needed to be containerized and deployed on Kubernetes to evaluate cluster behavior and ingress routing.

---

## 🎯 Objective

Design and implement a Kubernetes-based deployment architecture that:

- Deploys Apache-based workloads with high availability  
- Containerizes application code from GitHub repository  
- Pushes custom Docker image to Docker Hub  
- Deploys application with multiple replicas  
- Implements Ingress-based path routing  
- Supports microservices-style traffic segmentation  

---

# 🏗 Containerization & Orchestration Architecture

Implemented a layered container-native architecture consisting of:

- Custom Docker image built from GitHub source code  
- Docker Hub as container registry  
- Kubernetes Cluster (Multi-Node)  
- Apache Deployment with 2 replicas  
- Kubernetes Service for internal communication  
- Ingress Controller for HTTP path-based routing  

This architecture simulates production-ready microservice routing patterns.

---

# 🔄 Implementation Strategy

---

## 🔹 Step 1 – Application Containerization

- Cloned GitHub application repository  
- Built custom Docker image for the Apache-based application  
- Ensured application code resides inside web root directory  
- Tagged and pushed Docker image to Docker Hub  
- Validated image availability in remote registry  

This ensures container portability and deployment consistency.

---

## 🔹 Step 2 – Kubernetes Deployment

Created Kubernetes deployment with:

- Apache-based container image  
- 2 replicas for high availability  
- Controlled resource allocation  
- ReplicaSet management  
- Pod lifecycle governance  

This enables horizontal scaling and fault tolerance.

---

## 🔹 Step 3 – Kubernetes Service Configuration

Configured Kubernetes Service to:

- Expose Apache pods internally  
- Enable stable networking  
- Abstract pod-level communication  
- Prepare routing layer for ingress  

Service abstraction ensures traffic stability during scaling events.

---

## 🔹 Step 4 – Ingress-Based Path Routing

Implemented Ingress rules to achieve microservice-style routing:

- `/apache` → Routes to Apache deployment pods  
- `/custom` → Routes to containerized GitHub application  

This enables:

- Layer-7 traffic routing  
- URL-based service segregation  
- Reverse proxy behavior  
- Enterprise-grade traffic management  

---

# 🛠 Execution Highlights

✔ Designed Kubernetes-based microservices test architecture  
✔ Containerized GitHub application into custom Docker image  
✔ Pushed image to Docker Hub registry  
✔ Deployed Apache deployment with 2 replicas  
✔ Configured Kubernetes Service abstraction  
✔ Implemented Ingress-based path routing  
✔ Validated traffic segmentation via URL mapping  
✔ Simulated microservices-ready infrastructure  

---

# 🔐 DevOps Engineering Outcomes

✔ Enabled container-native deployment model  
✔ Demonstrated Kubernetes-based scaling  
✔ Achieved path-based service routing  
✔ Reduced monolithic dependency  
✔ Prepared foundation for microservices migration  
✔ Improved deployment flexibility  

---

# 🧠 DevOps Skills Demonstrated

- **Docker Image Creation & Registry Management**
- **Kubernetes Deployment Architecture**
- **ReplicaSet & Scaling Strategy**
- **Kubernetes Service Networking**
- **Ingress Controller Configuration**
- **Path-Based Traffic Routing**
- **Microservices Infrastructure Design**
- **Container Orchestration Strategy**

---

# 📊 Enterprise Relevance

This implementation reflects real-world modernization strategies used in:

- Monolith-to-Microservices migration  
- SaaS platform scaling  
- Cloud-native architecture adoption  
- Containerized production workloads  
- Enterprise traffic routing governance  

Kubernetes ingress-based routing is foundational for scalable distributed systems.

---

# 📸 Validation & Evidence

📄 **Consolidated Case Study Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

This case study is part of:

**Module 7 – Kubernetes**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
