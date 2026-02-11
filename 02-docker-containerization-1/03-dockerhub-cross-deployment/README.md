# 🐳 Docker Assignment 3 – Image Publishing & Cross-Machine Deployment

---

## 📌 Assignment Overview

This assignment focuses on publishing a custom Docker image to a public container registry and deploying it on a separate machine.

The objective was to understand how container images can be shared, distributed, and reused across environments using Docker Hub.  
This demonstrates portability — one of the core strengths of containerization in DevOps workflows.

---

## 🎯 Objective

To gain hands-on experience in:

- Using a previously created Docker image
- Publishing custom images to Docker Hub
- Pulling images on a different system
- Running containers from remote registry images
- Validating application availability across machines

---

## 🗂 Task Breakdown / Implementation Overview

### 📦 Image Reuse
- Used the previously saved custom Docker image
- Ensured the image contained Apache and required configuration
- Verified image readiness for distribution

---

### 🌍 Image Publishing to Docker Hub
- Tagged the custom image appropriately
- Uploaded the image to Docker Hub
- Verified successful availability on the remote registry

---

### 💻 Cross-Machine Deployment
- Accessed a separate machine environment
- Pulled the published image from Docker Hub
- Launched a container instance from the pulled image
- Mapped the container port to host port 80

---

### 🌐 Service Initialization & Validation
- Started the Apache2 service inside the container
- Accessed the application via browser
- Confirmed successful rendering of the Apache page
- Validated container portability and registry-based deployment

---

## 🔁 Workflow Demonstrated

- Image creation → Registry publishing → Cross-machine deployment
- Public container registry usage
- Host-to-container networking
- Portable application distribution

This mirrors real-world DevOps practices in CI/CD pipelines and cloud-native deployments.

---

## 📈 Key Learning Outcomes

- Understanding container registry concepts
- Publishing custom Docker images
- Pulling images from remote registries
- Deploying consistent environments across machines
- Validating container portability

---

## 🏆 Real-World Relevance

This workflow is widely used in:

- CI/CD pipelines
- Cloud deployments
- Microservices architecture
- Distributed development teams
- Production container orchestration platforms

Docker Hub and similar registries act as the backbone for container-based delivery systems.

---

## 🛠 Skills Demonstrated

- Docker image tagging and publishing
- Docker Hub registry integration
- Cross-environment deployment
- Container networking and service validation
- DevOps container lifecycle management

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(https://drive.google.com/file/d/1LuGU5egASkB3Gjt6lGb4TQkJYH4WfCvN/view?usp=drive_link)*

---

## 📚 Course Context

This assignment is part of:

**Module – Docker**  
**DevOps Course**  
**DevOps Architect Master’s Program – Intellipaat**

---

⭐ *This assignment demonstrates container image portability and registry-based deployment — essential skills for scalable DevOps and cloud-native application delivery.*
