# 🧪 Hands-On Lab – Kubernetes Cluster Installation & Network Configuration on AWS

---

## 📌 Lab Overview

Designed and implemented a **multi-node Kubernetes cluster on AWS**, consisting of a Master node and a Worker node.

This lab demonstrates complete cluster bootstrap, container runtime setup, node joining process, and cluster networking configuration using production-style Kubernetes installation practices.

---

## 🎯 Objective

Establish a functional Kubernetes cluster capable of:

- Orchestrating containerized workloads  
- Managing cluster nodes centrally  
- Supporting pod networking across nodes  
- Enabling ingress-based traffic routing  
- Preparing environment for scalable deployments  

---

# 🏗 Infrastructure Architecture

Provisioned AWS infrastructure including:

- Master Node (Control Plane)
- Worker Node (Data Plane)
- Ubuntu 20.04 OS environment
- Docker container runtime
- Kubernetes core components:
  - kubeadm
  - kubelet
  - kubectl

This architecture simulates real-world Kubernetes cluster design.

---

# 🔄 Implementation Strategy

---

## 🔹 Container Runtime Installation

Installed and configured Docker as the container runtime across both nodes to:

- Enable container lifecycle management  
- Provide runtime support for Kubernetes pods  
- Prepare environment for orchestration  

---

## 🔹 Kubernetes Component Installation

Installed Kubernetes core components on both nodes:

- kubeadm for cluster initialization  
- kubelet for node management  
- kubectl for cluster interaction  

Version control ensured environment consistency.

---

## 🔹 Cluster Initialization

On the Master node:

- Initialized the control plane  
- Generated cluster join token  
- Configured kubectl access  
- Established cluster administrative control  

Worker node was successfully joined using secure token-based authentication.

---

## 🔹 Cluster Networking Configuration

Implemented networking layer to enable:

- Pod-to-pod communication  
- Cross-node workload connectivity  
- Internal service communication  

Configured:

- Pod network CIDR  
- Calico networking plugin  
- Ingress controller support  

This ensures production-ready cluster networking behavior.

---

# 🛠 Execution Highlights

✔ Provisioned multi-node Kubernetes cluster  
✔ Installed and configured container runtime  
✔ Bootstrapped control plane successfully  
✔ Joined worker node securely  
✔ Configured cluster networking plugin  
✔ Enabled ingress controller for traffic management  
✔ Validated cluster node readiness  

---

# 🔐 DevOps Engineering Outcomes

✔ Established scalable container orchestration environment  
✔ Enabled distributed workload execution  
✔ Configured secure node authentication  
✔ Implemented cluster-level networking governance  
✔ Prepared infrastructure for production workloads  

---

# 🧠 DevOps Skills Demonstrated

- **Kubernetes Cluster Bootstrapping**
- **Control Plane & Worker Node Configuration**
- **Container Runtime Integration**
- **Token-Based Node Authentication**
- **Pod Networking Architecture**
- **Ingress Controller Setup**
- **Cloud-Based Orchestration Deployment**
- **Infrastructure Readiness Validation**

---

# 📊 Enterprise Relevance

Kubernetes cluster installation is foundational for:

- Microservices architecture deployment  
- Containerized CI/CD environments  
- Scalable SaaS platforms  
- Production-grade orchestration systems  
- Cloud-native infrastructure modernization  

Proper cluster setup ensures stability, scalability, and security of distributed systems.

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
