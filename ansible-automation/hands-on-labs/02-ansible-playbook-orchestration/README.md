# 🧪 Hands-On Lab – Ansible Playbook Orchestration & Automated Service Deployment

---

## 📌 Lab Overview

Executed structured implementation of **Ansible Playbooks** to automate software installation and script execution across multiple managed nodes.

This lab demonstrates centralized orchestration of application deployment, service management, and remote script execution using infrastructure automation principles.

---

## 🎯 Objective

Design and execute automation workflows that:

- Install web servers across multiple AWS nodes  
- Execute conditional deployment based on host grouping  
- Run custom scripts remotely  
- Maintain environment consistency  
- Enforce idempotent configuration management  

---

# 🏗 Infrastructure Context

Automation environment consisted of:

- 1 Ansible Master (Control Node)  
- 2 Managed Slave Nodes (slave1, slave2)  
- Keyless SSH authentication configured  
- Inventory configuration maintained under `/etc/ansible/hosts`  

This setup mirrors enterprise multi-node configuration management environments.

---

# 🔄 Implementation Strategy

---

## 🔹 Playbook-Based Software Installation

Designed Ansible Playbook to:

- Install **NGINX** on one managed node  
- Install **Apache2** on another managed node  
- Use host-based targeting logic  
- Ensure service installation consistency  
- Maintain idempotent execution  

This approach eliminates manual server provisioning and reduces configuration drift.

---

## 🔹 Remote Script Execution via Playbook

Extended Playbook functionality to:

- Create custom automation script  
- Execute script remotely on selected managed node  
- Modify target file content dynamically  
- Validate script execution results  

Demonstrated ability to combine configuration management with operational scripting.

---

# 🛠 Execution Highlights

✔ Automated installation of NGINX and Apache2  
✔ Targeted deployment using inventory-based host grouping  
✔ Implemented multi-task playbook execution  
✔ Executed custom scripts on managed nodes  
✔ Verified service availability via browser validation  
✔ Ensured repeatable and consistent automation workflow  

---

# 🔐 DevOps Engineering Outcomes

✔ Reduced manual server provisioning effort  
✔ Enforced centralized configuration governance  
✔ Achieved host-specific automation targeting  
✔ Demonstrated scalable multi-node orchestration  
✔ Improved operational efficiency through automation  

---

# 🧠 DevOps Skills Demonstrated

- **Ansible Playbook Development**
- **Multi-Node Automation Strategy**
- **Conditional Host Targeting**
- **Service Installation Automation**
- **Remote Script Execution**
- **Infrastructure as Code Principles**
- **Idempotent Configuration Management**
- **Operational Validation Techniques**

---

# 📊 Enterprise Relevance

Playbook orchestration is critical in:

- Multi-environment infrastructure management  
- CI/CD environment preparation  
- Application deployment pipelines  
- Automated patching and configuration updates  
- Cloud infrastructure standardization  

This workflow reflects real-world DevOps practices for scalable infrastructure automation.

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
