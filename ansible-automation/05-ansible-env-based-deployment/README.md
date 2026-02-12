# ⚙️ Ansible – Environment-Based Role Deployment (Test & Prod Segmentation)

---

## 📌 Implementation Overview

Designed and deployed a **5-node Ansible automation cluster** implementing environment-based segmentation using inventory grouping.

Structured the infrastructure to differentiate between **Test** and **Production** environments and provisioned environment-specific services using dedicated Ansible Roles.

This implementation reflects enterprise-grade configuration management with controlled environment separation.

---

## 🎯 Objective

To implement scalable, environment-based automation using Ansible Roles and inventory grouping, ensuring controlled deployment of services across Test and Production environments.

---

## 🗂 Implementation Summary

- Provisioned a new **5-node Ansible cluster**
- Configured:
  - 2 nodes under **Test** environment
  - 2 nodes under **Production** environment
- Created structured inventory grouping for environment segmentation
- Developed role-based automation:
  - Installed **Java** on Test nodes
  - Installed **MySQL Server** on Production nodes
- Executed centralized automation via Control Node
- Validated successful environment-specific deployments

This demonstrates structured infrastructure orchestration using role-based automation.

---

## 🔁 Automation Architecture

- Control Node → 4 Managed Nodes architecture
- Inventory-based environment grouping (Test / Prod)
- Role-driven service provisioning
- Modular and scalable Playbook design
- Idempotent execution ensuring consistency

This architecture enables clean separation between environments while maintaining centralized control.

---

## 📈 Key Outcomes

- Implemented environment-level infrastructure segmentation
- Automated role-based service deployment
- Reduced risk of cross-environment configuration errors
- Strengthened modular Infrastructure as Code practices
- Achieved scalable automation across multiple nodes

---

## 🏆 Real-World Relevance

Environment segmentation is critical in:

- Enterprise production deployments
- CI/CD release pipelines
- Staging vs Production isolation
- Cloud infrastructure management
- Compliance-driven system architecture

Organizations rely on environment-based automation to prevent configuration drift and production incidents.

---

## 🛠 Skills Demonstrated

- Ansible inventory grouping
- Environment-based configuration management
- Role-driven service deployment
- Multi-node infrastructure automation
- Infrastructure as Code discipline
- DevOps environment segmentation strategy

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(https://drive.google.com/file/d/1Fm4y5P7vssyQDiXgwvbPrpS-GXpgaBiC/view?usp=drive_link)*

---

## 📚 Course Context

This assignment is part of:

**Module 5 – Ansible**  
**DevOps Course**  
**DevOps Architect Master’s Program – Intellipaat**

---
