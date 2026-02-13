# 🧪 Hands-On Lab – Kubernetes Deployment & NodePort Service Exposure

---

## 📌 Lab Overview

Executed structured implementation of a **Kubernetes Deployment and NodePort Service configuration** to expose containerized workloads externally.

This lab demonstrates how containerized applications are deployed within a Kubernetes cluster and exposed through controlled networking mechanisms.

---

## 🎯 Objective

Design and implement Kubernetes resources to:

- Deploy application pods via Deployment object  
- Ensure high availability through replica management  
- Expose services externally using NodePort  
- Enable browser-based validation of application  
- Maintain scalable and fault-tolerant container orchestration  

---

# 🏗 Kubernetes Architecture Design

Implemented a layered orchestration model consisting of:

- Kubernetes Deployment managing application pods  
- Replica-based workload distribution  
- Kubernetes Service abstraction  
- NodePort exposure for external access  
- Label-based pod selection mechanism  

This architecture simulates production-ready container orchestration patterns.

---

# 🔄 Implementation Strategy

---

## 🔹 Deployment Creation

Configured a Kubernetes Deployment to:

- Launch NGINX-based containerized workload  
- Maintain desired state with replica control  
- Automatically restart failed pods  
- Ensure cluster-level high availability  

Deployment ensures declarative infrastructure management.

---

## 🔹 Service Configuration (NodePort)

Created a Kubernetes Service with:

- Type: NodePort  
- Port mapping from cluster to external node port  
- Label selector to bind service with deployment pods  
- External exposure for browser validation  

NodePort enables controlled public access to internal pods.

---

# 🛠 Execution Highlights

✔ Created Kubernetes Deployment object  
✔ Managed pod lifecycle through ReplicaSet  
✔ Configured NodePort service exposure  
✔ Implemented label-based pod-service binding  
✔ Verified service accessibility externally  
✔ Simulated production-style workload exposure  

---

# 🔐 DevOps Engineering Outcomes

✔ Achieved scalable container deployment  
✔ Enabled external access to Kubernetes workloads  
✔ Implemented service abstraction layer  
✔ Maintained high availability through replicas  
✔ Improved infrastructure resiliency  

---

# 🧠 DevOps Skills Demonstrated

- **Kubernetes Deployment Architecture**
- **Replica Management Strategy**
- **NodePort Service Configuration**
- **Pod Lifecycle Governance**
- **Container Orchestration Concepts**
- **Cluster Networking Fundamentals**
- **Label & Selector-Based Routing**

---

# 📊 Enterprise Relevance

This implementation reflects real-world Kubernetes practices used in:

- Containerized web application hosting  
- Production workload exposure  
- Scalable microservices deployment  
- Cloud-native infrastructure management  
- DevOps CI/CD environments  

Understanding service exposure patterns is critical for distributed systems design.

---

# 📸 Validation & Evidence

📄 **Hands-On Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

This hands-on lab is part of:

**Module 7 – Kubernetes**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
