# 🐳 Docker Assignment 5 – Custom Web Page Deployment inside Container

---

## 📌 Assignment Overview

This assignment focuses on **customizing a containerized Apache web server** by replacing the default web page with a custom HTML file.

The primary objective was to demonstrate how **application content can be embedded directly into a Docker image**, ensuring consistent deployment across environments.

This reflects a **real DevOps container build workflow**, where application code and runtime environment are packaged together.

---

## 🎯 Objective

To understand and implement:

- **Custom web content creation**
- **Dockerfile-based image customization**
- **Automated application deployment inside containers**
- **Rebuilding and redeploying container images**
- **Validation of updated containerized services**

---

## 🗂 Task Breakdown / Implementation Overview

### 📄 Custom Web Page Creation

- Created a **sample HTML file**
- Designed it to replace the default Apache page
- Prepared it for integration into the Docker image

This demonstrates how **application-level changes** are introduced into containerized environments.

---

### 🧱 Dockerfile-Based Integration

- Reused the previously created **Dockerfile**
- Modified it to copy the custom HTML file into the Apache web directory
- Ensured Apache continues to start automatically

This step highlights **Infrastructure as Code principles for container builds**.

---

### 🔄 Image Rebuild & Deployment

- Rebuilt the Docker image with updated content
- Launched a container from the new image
- Verified successful replacement of the default Apache page

This shows how **containers can be versioned and redeployed consistently**.

---

### 🌐 Service Validation

- Accessed the application via browser
- Confirmed the custom HTML page loads successfully
- Validated proper container-to-host networking

This ensures **end-to-end container deployment verification**.

---

## 🔁 Workflow Demonstrated

- Application file creation  
- Dockerfile modification  
- Image rebuild process  
- Container redeployment  
- Browser-level validation  

This workflow mirrors **real-world CI/CD container build pipelines**.

---

## 📈 Key Learning Outcomes

- Understanding how **application files integrate into container images**
- Applying **Dockerfile automation**
- Rebuilding images with updated application code
- Ensuring **deployment consistency**
- Strengthening containerization fundamentals

---

## 🏆 Real-World Relevance

This workflow is commonly used in:

- **Microservices-based architectures**
- **CI/CD image build pipelines**
- **Cloud-native application deployments**
- **Container-based web hosting**
- **Environment replication (Dev, QA, Prod)**

Embedding code into images ensures **environment consistency and deployment reliability**.

---

## 🛠 Skills Demonstrated

- **Docker image customization**
- **Application packaging inside containers**
- **Image rebuild and versioning**
- **Web server configuration awareness**
- **DevOps automation practices**

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(https://drive.google.com/file/d/1jPvB0hBXGerPKHnZqpOZCVl0ABKfP1nI/view?usp=drive_link)*

---

## 📚 Course Context

This assignment is part of:

**Module – Docker**  
**DevOps Course**  
**DevOps Architect Master’s Program – Intellipaat**

---

⭐ *This assignment demonstrates the ability to integrate application code into container images and redeploy them consistently — a core DevOps engineering capability.*
