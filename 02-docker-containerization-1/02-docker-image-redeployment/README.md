# 🐳 Docker Assignment 2 – Image Creation & Container Redeployment

---

## 📌 Assignment Overview

This assignment focuses on converting a configured container into a reusable Docker image and deploying a new container instance from that image.

The objective was to understand how Docker images can be created from customized containers and reused for consistent deployments.  
This demonstrates how containerization ensures repeatability across environments.

---

## 🎯 Objective

To gain hands-on experience in:

- Creating a custom Docker image from a running container
- Managing Docker image lifecycle
- Launching containers from custom-built images
- Mapping different host ports
- Validating application accessibility

---

## 🗂 Task Breakdown / Implementation Overview

### 📦 Custom Image Creation
- Converted the configured Ubuntu + Apache container into a reusable Docker image
- Ensured application and configuration were preserved inside the new image
- Verified successful image creation

---

### ▶️ Container Deployment from Custom Image
- Launched a new container instance from the newly created image
- Mapped container port 80 to a different host port (81)
- Demonstrated flexible port mapping capability

---

### 🌐 Service Initialization
- Accessed the running container
- Started the Apache2 service
- Ensured the web server was active inside the container

---

### 🔎 Service Validation
- Accessed the application via the mapped host port
- Confirmed Apache page loaded successfully
- Validated container-to-host communication on a new port

---

## 🔁 Workflow Demonstrated

- Container customization → Image creation → Redeployment
- Reusable image strategy
- Flexible port mapping
- Service validation through browser access

This mirrors real-world DevOps practices for building and reusing container images.

---

## 📈 Key Learning Outcomes

- Understanding how to persist container configurations as images
- Managing Docker image lifecycle
- Deploying multiple container instances from a single image
- Handling port remapping scenarios
- Strengthening container deployment concepts

---

## 🏆 Real-World Relevance

This workflow is commonly used in:

- CI/CD image build pipelines
- Microservices deployments
- Environment replication (Dev, QA, Prod)
- Container-based application scaling
- Cloud-native infrastructure setups

---

## 🛠 Skills Demonstrated

- Docker image creation
- Container redeployment
- Port mapping strategies
- Service lifecycle management
- DevOps container workflow implementation

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(https://drive.google.com/file/d/17gv5LxvbvbNlqkrrBB2d_U5hxpf6HFzD/view?usp=drive_link)*

---

## 📚 Course Context

This assignment is part of:

**Module – Docker**  
**DevOps Course**  
**DevOps Architect Master’s Program – Intellipaat**

---

⭐ *This assignment demonstrates the ability to create reusable Docker images and deploy containerized services efficiently, a critical skill in DevOps automation workflows.*
