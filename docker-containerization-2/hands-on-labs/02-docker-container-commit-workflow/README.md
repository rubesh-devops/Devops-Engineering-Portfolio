# 🐳 Hands-On – Saving Changes to a Docker Container

---

## 📌 Lab Overview

Executed container lifecycle operations to understand how runtime changes inside a Docker container can be preserved by committing the modified container into a reusable Docker image.

This hands-on demonstrates practical container customization, image versioning, and Docker Hub integration workflow.

---

## 🎯 Objective

✔ Pull a base Docker image  
✔ Launch and access a running container  
✔ Install Apache2 inside the container  
✔ Commit container changes into a new Docker image  
✔ Prepare image for Docker Hub usage  

---

# 🏗 Implementation Summary

---

## 🔹 Step 1 – Pulling Base Docker Image

- Retrieved official container image from Docker Hub
- Verified successful download in local Docker environment

### Outcome
Base image available for container execution.

---

## 🔹 Step 2 – Running the Container

- Launched container from pulled image
- Exposed necessary ports for service validation

### Outcome
Container successfully initialized and accessible.

---

## 🔹 Step 3 – Accessing the Container Shell

- Entered interactive shell session inside running container
- Prepared environment for runtime software installation

### Outcome
Administrative access gained inside container environment.

---

## 🔹 Step 4 – Installing Apache2 Inside Container

- Installed Apache2 web server within container
- Verified installation and service availability

### Outcome
Container now functions as a web server runtime.

---

## 🔹 Step 5 – Committing Container as Custom Image

- Exited running container
- Saved modified container state as a new Docker image
- Tagged image with Docker Hub–aligned username
- Assigned meaningful repository/image name

### Important Note
Docker image repository name must match the Docker Hub username for future push operations.

### Outcome
Custom reusable Docker image successfully created.

---

# 🔐 Skills Demonstrated

- Docker Image Management  
- Container Lifecycle Operations  
- Runtime Container Customization  
- Docker Commit Workflow  
- Image Tagging Strategy  
- Docker Hub Naming Conventions  

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

