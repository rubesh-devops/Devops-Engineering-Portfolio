# 🧪 Hands-On Lab – Enterprise Ansible Playbook & Role-Based Architecture Implementation

---

## 📌 Lab Overview

Designed and implemented a structured **Ansible automation architecture** using:

- Multi-play Playbooks  
- Modular Role-based configuration  
- Task segregation (Install, Configure, Service)  
- Handler-driven service management  
- Role integration within top-level Playbooks  

This lab demonstrates production-grade configuration management practices aligned with enterprise DevOps standards.

---

## 🎯 Objective

Build a scalable automation framework capable of:

- Executing multiple tasks across different hosts  
- Structuring automation into reusable roles  
- Separating installation, configuration, and service layers  
- Triggering handlers based on configuration changes  
- Integrating roles seamlessly within Playbooks  

---

# 🏗 Automation Architecture Design

Implemented a layered Ansible model consisting of:

- **Master Node (Control Node)**
- **Managed Hosts (Host1 & Host2)**
- Inventory-based grouping
- Multi-play execution structure
- Role-driven modular automation

The automation workflow was divided into three segments:

A. Playbook Creation  
B. Role Creation  
C. Role Integration within Playbook  

---

# 🔄 Implementation Strategy

---

## 🔹 Segment A – Multi-Play Playbook Design

Developed a structured Playbook containing:

- Play 1: Command execution & script deployment on Host1  
- Play 2: Script execution & NGINX installation on Host2  

Validated idempotent execution ensuring:

- Repeated runs do not cause configuration drift  
- Only necessary changes are applied  

This simulates real-world production automation scenarios.

---

## 🔹 Segment B – Modular Role-Based Automation

Designed and structured Ansible Roles with enterprise-grade separation:

### Role Structure Implemented

- tasks/
  - install.yml
  - configure.yml
  - service.yml
- handlers/
- files/
- meta/

### Task Segmentation Strategy

✔ Installation tasks separated  
✔ Configuration tasks modularized  
✔ Service management isolated  
✔ Execution order controlled via main.yml  

This modular approach improves maintainability and reusability.

---

## 🔹 File Deployment & Service Management

Implemented configuration deployment by:

- Pushing configuration files to managed nodes  
- Deploying custom HTML validation page  
- Restarting services using handlers  
- Ensuring notify-handler relationship alignment  

This ensures controlled and predictable service lifecycle management.

---

## 🔹 Role Metadata & Documentation

Enhanced role professionalism by including:

- Author details  
- Description  
- Company metadata  
- Role-level documentation  

Aligns with enterprise DevOps role governance standards.

---

## 🔹 Segment C – Role Integration with Playbook

Integrated Ansible roles into higher-level Playbooks using:

- Role imports  
- Role inclusion logic  
- Pre and post debug validations  
- Host-based role targeting  

Successfully executed combined automation workflow including:

- Pre-validation tasks  
- Role execution  
- Post-validation confirmation  

---

# 🛠 Execution Highlights

✔ Designed multi-play Ansible Playbook  
✔ Created fully modular Ansible Role architecture  
✔ Segmented install/configure/service layers  
✔ Implemented handler-based restart mechanism  
✔ Structured role metadata professionally  
✔ Integrated roles into top-level Playbook  
✔ Ensured idempotent configuration enforcement  
✔ Validated syntax before execution  
✔ Achieved clean and repeatable automation workflow  

---

# 🔐 DevOps Engineering Outcomes

✔ Reduced complexity via modular automation  
✔ Eliminated repetitive manual configuration  
✔ Enabled scalable infrastructure management  
✔ Prevented configuration drift  
✔ Implemented structured service lifecycle governance  
✔ Established reusable automation patterns  

---

# 🧠 DevOps Skills Demonstrated

- **Advanced Ansible Playbook Architecture**
- **Role-Based Configuration Management**
- **Task Layer Segmentation Strategy**
- **Handler-Driven Service Orchestration**
- **Inventory-Based Host Targeting**
- **Idempotent Infrastructure Execution**
- **Enterprise Automation Governance**
- **Infrastructure Modularity Design**

---

# 📊 Enterprise Relevance

This implementation mirrors real-world enterprise practices used in:

- Production configuration management  
- Multi-environment automation  
- CI/CD infrastructure orchestration  
- Web server lifecycle management  
- DevOps infrastructure standardization  

Role-based automation is foundational for scalable Infrastructure as Code environments.

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
