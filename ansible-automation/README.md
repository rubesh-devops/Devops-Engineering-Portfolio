# ⚙️ Ansible Automation – Configuration Management & Infrastructure Orchestration

---

## 📌 Overview

This module demonstrates **enterprise-grade configuration management and infrastructure automation** using Ansible.

The implementation focuses on:

- Multi-node automation
- Role-based deployment
- Environment segmentation (Test & Production)
- Targeted configuration updates
- Infrastructure as Code practices

All tasks are executed using structured Playbooks and Roles to ensure scalable, repeatable, and consistent infrastructure management.

---

## 🏗 Architecture Approach

- Centralized **Ansible Control Node**
- Multiple Managed Nodes
- Inventory-based host grouping
- Role-driven configuration separation
- Idempotent automation execution

This structure enables scalable server provisioning and controlled service deployment.

---

# 🧩 Assignments Implemented

---

## 🔹 01 – Multi-Node Automation Setup

Implemented a 3-node Ansible architecture and automated service provisioning:

- Installed Java on one node
- Installed MySQL on another
- Centralized execution via Playbooks

📁 Folder: `01-ansible-multinode-automation`

---

## 🔹 02 – Multi-Host Script Orchestration

Automated execution of a custom script across all managed hosts:

- Centralized script deployment
- Infrastructure-wide configuration modification
- Parallel execution using inventory targeting

📁 Folder: `02-ansible-multihost-script`

---

## 🔹 03 – Role-Based Service Deployment

Implemented structured Ansible Roles to provision:

- Apache on one node
- NGINX on another

Demonstrated modular automation and reusable role design.

📁 Folder: `03-ansible-role-based-deployment`

---

## 🔹 04 – Targeted File Deployment via Roles

Enhanced role architecture to:

- Replace default NGINX index file
- Restrict deployment only to designated host
- Maintain environment isolation

📁 Folder: `04-ansible-role-file-deployment`

---

## 🔹 05 – Environment-Based Deployment (Test & Prod Segmentation)

Provisioned 5-node infrastructure segmented into:

- Test Environment (Java installation)
- Production Environment (MySQL installation)

Implemented environment-based grouping using inventory segmentation.

📁 Folder: `05-ansible-env-based-deployment`

---

## 🔐 Core DevOps Capabilities Demonstrated

- Configuration Management at scale
- Multi-node automation
- Role-based infrastructure provisioning
- Inventory-driven host segmentation
- Environment isolation (Test vs Production)
- Idempotent infrastructure enforcement
- Infrastructure as Code discipline

---

## 🎯 Enterprise Relevance

Ansible automation is widely used in:

- Cloud VM provisioning
- CI/CD environment setup
- Production configuration management
- Infrastructure standardization
- DevOps automation frameworks

This module reflects real-world infrastructure automation practices used in startups and enterprise environments.

---

## 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*

---

## 📚 Course Context

Module 5 – Ansible  
DevOps Course  
Part of DevOps Architect Master’s Program – Intellipaat

