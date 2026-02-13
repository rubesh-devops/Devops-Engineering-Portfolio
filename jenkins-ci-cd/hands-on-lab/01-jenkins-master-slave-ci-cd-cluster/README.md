# 🧪 Hands-On Lab – Jenkins Master-Slave Cluster & Webhook-Driven CI/CD on AWS

---

## 📌 Lab Overview

Designed and implemented a full Jenkins Master–Slave CI/CD cluster on AWS EC2 with automated Docker-based deployment triggered via GitHub Webhooks.

This hands-on demonstrates production-style DevOps orchestration including distributed builds, containerized deployments, branch-based promotion, and webhook-triggered automation.

---

## 🎯 Objective

Implement a scalable CI/CD architecture that:

- Deploys Jenkins Master and multiple Agents on AWS EC2
- Establishes Master–Slave cluster communication
- Executes builds on distributed nodes
- Containerizes application using Docker
- Deploys web application via Apache
- Automates job execution using GitHub Webhooks
- Implements chained Test → Production pipeline

---

# 🏗 Infrastructure Architecture

Environment:

- EC2 Instance 1 → Jenkins Master
- EC2 Instance 2 → Slave-1 (Test Node)
- EC2 Instance 3 → Slave-2 (Production Node)

Toolchain:

- Jenkins
- GitHub
- Docker
- Apache
- AWS EC2
- Git Webhooks

---

# 🔄 Implementation Executed

## ✔ Jenkins Cluster Setup

- Installed Jenkins on Master
- Configured inbound rules (Port 8080)
- Set up Master–Agent cluster using Java Web Start
- Transferred `agent.jar` securely to slave nodes
- Installed OpenJDK on slaves
- Established active agent connections
- Verified node status in Jenkins dashboard

Result:
Distributed Jenkins cluster successfully established.

---

## ✔ CI/CD Job Configuration (Test Environment)

- Created Freestyle project for Test job
- Restricted job execution to Slave-1
- Integrated Git repository
- Cloned repository automatically during build
- Executed Docker-based deployment
- Published website on Port 82
- Verified deployment via browser

Result:
Push to repository → Build triggered → Docker container deployed on Test node.

---

## ✔ Production Job Setup

- Created separate Production job
- Restricted execution to Slave-2
- Configured Docker-based deployment
- Verified website availability on Production node

Result:
Production environment isolated and independently deployable.

---

## ✔ Chained Test → Production Pipeline

- Configured Post-Build Action in Test job
- Triggered Production job upon Test success
- Installed Build Pipeline Plugin
- Created visual pipeline view
- Verified sequential execution

Result:
Controlled environment promotion implemented.

---

## ✔ GitHub Webhook Integration

- Enabled GitHub hook trigger in Jenkins
- Configured Webhook in GitHub repository
- Validated automatic build trigger on push
- Modified application code
- Executed git add → commit → push
- Verified automatic deployment updates

Result:
Fully automated CI/CD lifecycle established.

---

# 🛠 Execution Highlights

✔ Distributed Jenkins Master–Agent architecture  
✔ Docker-based containerized deployment  
✔ Branch-driven build automation  
✔ Environment segregation (Test & Prod)  
✔ Webhook-triggered pipeline execution  
✔ Automated website publishing  
✔ Production-safe promotion workflow  

---

# 🔐 Engineering Outcomes

✔ Achieved scalable CI/CD infrastructure  
✔ Eliminated manual deployment steps  
✔ Enabled distributed build execution  
✔ Improved deployment reliability  
✔ Reduced release cycle time  
✔ Established production-grade DevOps workflow  

---

# 🧠 Skills Demonstrated

- Jenkins Master–Agent Configuration  
- Distributed CI/CD Architecture  
- GitHub Webhook Integration  
- Docker Container Deployment  
- Apache Web Hosting  
- AWS EC2 Infrastructure Setup  
- Branch-Based Deployment Logic  
- Pipeline Orchestration  
- DevOps Lifecycle Automation  

---

# 📊 Enterprise Relevance

This architecture mirrors real-world DevOps environments used in:

- Product-based software companies  
- Scalable cloud-native deployments  
- Distributed CI/CD ecosystems  
- Microservices container pipelines  
- Enterprise automation frameworks  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 6 – Jenkins**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
