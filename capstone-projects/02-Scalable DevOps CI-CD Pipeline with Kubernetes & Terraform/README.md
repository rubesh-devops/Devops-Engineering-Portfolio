# 🚀 DevOps Capstone Project 2 – Cloud-Native CI/CD with Kubernetes, Terraform & Ansible

---

## 📌 Project Overview

Designed and implemented a **production-grade DevOps lifecycle** for a product-based organization transitioning from monolithic architecture to scalable, containerized cloud deployment.

This project integrates:

- Git Workflow & Release Strategy
- CI/CD Automation using Jenkins
- Docker Containerization
- Kubernetes Orchestration
- Infrastructure Provisioning using Terraform
- Configuration Management using Ansible
- AWS Cloud Deployment Architecture

The objective was to automate infrastructure creation, software installation, container deployment, scaling, and production releases — without manual intervention.

---

## 🏗 Architecture Components

- AWS EC2 Infrastructure
- Terraform (Infrastructure as Code)
- Ansible (Configuration Management)
- Jenkins (CI/CD Automation Server)
- Git & GitHub (Version Control)
- Docker (Containerization)
- Docker Hub (Image Registry)
- Kubernetes Cluster (Master + Worker Nodes)
- NodePort Service (Port 30008)

---

## 🎯 Business Requirement

The company required:

- Automated container deployment platform
- Scalable orchestration using Kubernetes
- Monthly controlled release (25th of every month)
- Automated Docker image builds on every commit
- Infrastructure provisioning via Infrastructure as Code
- High availability with 2 replicas in production

This project delivered a fully automated, scalable DevOps lifecycle architecture.

---

## 🔄 DevOps Lifecycle Implementation

### 1️⃣ Infrastructure Provisioning (Terraform)

- Provisioned AWS EC2 instances automatically
- Created reusable Infrastructure as Code templates
- Enabled consistent environment creation across nodes
- Automated multi-node production architecture setup

---

### 2️⃣ Configuration Management (Ansible)

Automated installation of required software across machines:

- Jenkins & Java
- Docker
- Kubernetes
- System dependencies

Ensured standardized and reproducible server configurations.

---

### 3️⃣ Git Workflow & Release Strategy

- Implemented structured branching strategy
- Managed version control for monolithic architecture
- Configured production releases only via master branch
- Enforced monthly release schedule

Delivered disciplined and controlled release management.

---

### 4️⃣ CI/CD Pipeline Automation (Jenkins)

Designed multi-stage automated pipeline:

- Build Stage
- Test Stage
- Production Deployment Stage

Pipeline behavior:

- Commit to master branch triggers build and production deployment
- Automated testing before release
- Docker image built on every push

Achieved complete CI/CD automation.

---

### 5️⃣ Docker Containerization

- Created custom Docker image using Dockerfile
- Automated image build on every Git push
- Pushed images to Docker Hub
- Standardized runtime environment for application

Enabled portable, consistent, and scalable deployments.

---

### 6️⃣ Kubernetes Deployment & Scaling

- Deployed containerized application to Kubernetes cluster
- Configured 2 replicas for high availability
- Created NodePort service on port 30008
- Ensured automated scaling and orchestration

Delivered production-ready container orchestration.

---

## 🔐 Security & Infrastructure Design

- Segregated Jenkins, Kubernetes Master, and Worker nodes
- Controlled inbound access using security groups
- Isolated cluster-based deployment architecture
- Centralized CI/CD governance

Ensured enterprise-grade secure deployment architecture.

---

## 📈 Key Learning Outcomes

- End-to-end DevOps lifecycle implementation
- Infrastructure as Code with Terraform
- Configuration Management using Ansible
- CI/CD Automation with Jenkins
- Docker image lifecycle management
- Kubernetes orchestration & scaling
- Release strategy & version control management
- Cloud-native DevOps architecture design

---

## 🏆 Enterprise Use Case

This architecture is suitable for:

- SaaS platforms
- Product-based startups
- High-traffic web applications
- Microservices migration environments
- Production-grade DevOps ecosystems

---

## 📊 Final Outcome

Successfully implemented:

- Automated CI/CD pipeline
- Dockerized application lifecycle
- Kubernetes-based scalable deployment
- Infrastructure provisioned via Terraform
- Configuration managed using Ansible
- Controlled production release process

Delivered a fully automated, scalable, cloud-native DevOps architecture.

---

## 🛠 Skills Demonstrated

- DevOps Architecture Design
- CI/CD Pipeline Automation
- Docker Containerization
- Kubernetes Orchestration
- Terraform Infrastructure Provisioning
- Ansible Configuration Management
- Git Workflow Implementation
- AWS Cloud Deployment
- Production Release Strategy

---

## 📸 Validation & Evidence

📄 Consolidated Capstone Execution Documentation  
👉 Google Drive: *(https://drive.google.com/file/d/1iwB0p6FFi2fCGjr1VkeBDs0xcd8nD1Cq/view?usp=drive_link)*

---

## 📚 Course Reference

This End-to-End Devops Project is part of
**Capstone Projects**
**DevOps Course**  
**DevOps Architect Master’s Program – Intellipaat**
