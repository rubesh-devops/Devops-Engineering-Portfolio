# ⚙️ Ansible – Role-Based File Deployment & Targeted Configuration

---

## 📌 Implementation Overview

Extended the existing Ansible automation cluster to implement **role-based file management**, targeting only the node running NGINX.

Configured the role’s `files` directory to replace the default `index.html` file on the specific managed host, demonstrating precise and controlled configuration deployment using structured automation.

This reflects real-world Infrastructure as Code practices for controlled environment customization.

---

## 🎯 Objective

To implement targeted file deployment using Ansible Roles, ensuring that configuration changes are applied only to designated hosts based on service role.

---

## 🗂 Implementation Summary

- Reused the previously configured Ansible cluster
- Enhanced the NGINX role to include a `files` directory
- Added a custom `index.html` file for deployment
- Configured the Playbook to replace the default NGINX web page
- Restricted execution to only the NGINX-managed slave node
- Validated successful content replacement without affecting other nodes

This implementation demonstrates granular control over infrastructure changes.

---

## 🔁 Automation Architecture

- Role-based file deployment strategy
- Inventory-driven host targeting
- Service-specific configuration enforcement
- Controlled and idempotent execution
- Isolation of configuration changes to designated nodes

This model ensures safe and scalable infrastructure updates.

---

## 📈 Key Outcomes

- Achieved targeted configuration management
- Prevented unintended changes on unrelated nodes
- Strengthened modular automation architecture
- Demonstrated role-based deployment discipline
- Enhanced infrastructure customization capabilities

---

## 🏆 Real-World Relevance

This approach is widely used in:

- Web server customization
- Production environment configuration management
- Multi-service infrastructure environments
- CI/CD deployment workflows
- Enterprise DevOps automation frameworks

Organizations rely on targeted automation to maintain stability and precision in large environments.

---

## 🛠 Skills Demonstrated

- Ansible Role enhancement
- Target-specific file deployment
- Service-based configuration control
- Idempotent file management
- Modular Infrastructure as Code practices

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(https://drive.google.com/file/d/1eBOl2K-DsftY0tbqDoKTRM0CpBvK0ibz/view?usp=drive_link)*

---

## 📚 Course Context

This assignment is part of:

**Module 5 – Ansible**  
**DevOps Course**  
**DevOps Architect Master’s Program – Intellipaat**

---
