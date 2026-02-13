# 🧪 Hands-On Lab – Ansible Master-Slave Cluster Setup on AWS

---

## 📌 Lab Overview

Executed structured setup of an **Ansible Configuration Management Environment on AWS**, implementing a Master-Slave architecture to enable automated infrastructure provisioning and remote configuration management.

This lab focuses on preparing a production-ready automation environment using secure SSH communication and centralized orchestration.

---

## 🎯 Objective

Design and configure an Ansible automation environment that enables:

- Secure communication between control node and managed nodes  
- Passwordless SSH authentication  
- Centralized configuration management  
- Scalable infrastructure automation  
- Reliable master-to-node connectivity validation  

---

# 🏗 Architecture Design

Implemented a configuration management architecture consisting of:

- **Ansible Master (Control Node)**  
- **Ansible Slave (Managed Node)**  
- AWS-based Ubuntu virtual machines  
- SSH-based secure communication  
- Inventory-based host configuration  

This design simulates real-world enterprise automation infrastructure.

---

# 🔄 Implementation Strategy

---

## 🔹 Pre-Requisite Validation

Validated system readiness by ensuring:

- Python availability on both Master and Slave nodes  
- OS-level compatibility for Ansible installation  
- Network accessibility between nodes  

Python serves as the execution engine for Ansible modules.

---

## 🔹 Secure Keyless SSH Configuration

Configured passwordless SSH authentication to enable:

- Seamless automation execution  
- Elimination of manual password entry  
- Secure remote command execution  

This included:

- Generating SSH key pair on Master  
- Configuring authorized access on Slave  
- Validating secure SSH handshake  

Keyless SSH ensures non-interactive automation workflows.

---

## 🔹 Ansible Installation & Configuration

Installed Ansible on the Master node and configured:

- Inventory file for host grouping  
- Logical naming for managed nodes  
- Host-to-group mapping  

This enabled environment-aware execution control.

---

## 🔹 Connectivity Validation

Verified Master-Slave communication by:

- Testing remote command execution  
- Confirming host reachability  
- Ensuring module execution readiness  

Successful validation confirms automation environment is fully operational.

---

# 🛠 Execution Highlights

✔ Configured AWS-based automation infrastructure  
✔ Established secure key-based SSH authentication  
✔ Installed and configured Ansible control node  
✔ Created structured inventory configuration  
✔ Validated master-to-node connectivity  
✔ Prepared environment for role-based automation  

---

# 🔐 DevOps Engineering Outcomes

✔ Enabled centralized configuration management  
✔ Eliminated manual server administration overhead  
✔ Established secure automation baseline  
✔ Prepared scalable infrastructure management model  
✔ Improved operational efficiency  

---

# 🧠 DevOps Skills Demonstrated

- **Ansible Environment Setup**
- **Master-Slave Architecture Design**
- **SSH Key-Based Authentication**
- **Inventory Configuration Strategy**
- **Remote Command Orchestration**
- **Cloud-Based Automation Deployment**
- **Infrastructure Readiness Validation**

---

# 📊 Enterprise Relevance

Ansible cluster setup is foundational in:

- Infrastructure as Code implementations  
- CI/CD environment preparation  
- Production configuration governance  
- Multi-server provisioning  
- Cloud automation strategies  

Properly configured automation environments reduce configuration drift and enable predictable deployments.

---

# 📸 Validation & Evidence

📄 **Hands-On Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

This hands-on lab is part of:

**Module 5 – Ansible**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
