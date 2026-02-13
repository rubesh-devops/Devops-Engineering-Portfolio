# 🧪 Hands-On Lab – Kubernetes NodePort Service Exposure & Validation

---

## 📌 Lab Overview

Executed structured implementation of a **Kubernetes NodePort Service** to expose an existing NGINX deployment externally.

This lab demonstrates how Kubernetes services abstract pod networking and enable controlled external access to containerized workloads.

---

## 🎯 Objective

Design and validate Kubernetes networking configuration to:

- Expose deployment pods via NodePort  
- Map internal container ports to external node ports  
- Enable browser-based access to Kubernetes workloads  
- Validate service-to-pod binding  
- Simulate production-style service exposure  

---

# 🏗 Kubernetes Networking Architecture

Configured service architecture consisting of:

- NGINX Deployment with active pods  
- Kubernetes Service abstraction layer  
- NodePort type service  
- External port mapping on cluster node  
- Label-selector based routing  

This architecture ensures decoupling between pods and external traffic.

---

# 🔄 Implementation Strategy

---

## 🔹 Service Creation

Created a Kubernetes Service configured as:

- Type: NodePort  
- Bound to NGINX deployment pods  
- Mapped container port 80 to a dynamically assigned external port  
- Associated using label selectors  

This ensures traffic routing stability even during pod rescheduling.

---

## 🔹 NodePort Identification

Validated service configuration by:

- Inspecting assigned NodePort  
- Confirming port mapping  
- Verifying service readiness  

This confirms external accessibility.

---

## 🔹 Service Validation

Tested external accessibility by:

- Accessing cluster node IP  
- Appending allocated NodePort  
- Confirming NGINX application response  

Successful validation confirms proper service exposure and routing.

---

# 🛠 Execution Highlights

✔ Created NodePort service for existing deployment  
✔ Implemented port mapping configuration  
✔ Ensured label-based pod-service binding  
✔ Validated service externally via browser  
✔ Confirmed deployment stability under service abstraction  

---

# 🔐 DevOps Engineering Outcomes

✔ Enabled controlled external access to workloads  
✔ Abstracted pod networking via service layer  
✔ Maintained high availability via deployment replicas  
✔ Prepared foundation for load balancing and ingress integration  
✔ Improved cluster-level traffic governance  

---

# 🧠 DevOps Skills Demonstrated

- **Kubernetes Service Architecture**
- **NodePort Exposure Strategy**
- **Container Networking Fundamentals**
- **Pod-to-Service Binding**
- **Cluster Traffic Validation**
- **Scalable Workload Exposure**

---

# 📊 Enterprise Relevance

NodePort service exposure is commonly used in:

- Development and staging environments  
- On-premise Kubernetes clusters  
- Controlled access testing environments  
- Pre-production validation setups  

Understanding service abstraction is critical for designing resilient microservices architectures.

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
