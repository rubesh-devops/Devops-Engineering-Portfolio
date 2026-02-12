# ⚙️ Ansible – Multi-Node Configuration Automation

---

## 📌 Implementation Overview

Implemented a centralized **Ansible automation cluster** to manage configuration across multiple managed nodes.

Designed and executed Playbooks to install **Java on one target node** and **MySQL Server on another**, demonstrating targeted configuration management using inventory-based automation.

This implementation reflects real-world Infrastructure as Code (IaC) practices for scalable environment provisioning.

---

## 🎯 Objective

To automate role-based software installation across multiple servers using a single Ansible Control Node, ensuring consistent and repeatable configuration management.

---

## 🗂 Implementation Summary

- Configured a **3-node Ansible architecture** (1 Control Node + 2 Managed Nodes)
- Established secure communication between control and slave nodes
- Created structured inventory for host grouping
- Developed Playbooks for:
  - Targeted Java installation on Slave 1
  - Targeted MySQL Server installation on Slave 2
- Executed automation from centralized control node
- Validated successful service deployment on respective systems

This approach ensures clean separation of responsibilities across infrastructure components.

---

## 🔁 Automation Architecture

- Control Node → Managed Nodes communication model
- Inventory-based host targeting
- Playbook-driven service provisioning
- Role-specific configuration enforcement
- Idempotent automation execution

This architecture ensures scalable and repeatable infrastructure automation.

---

## 📈 Key Outcomes

- Automated multi-node configuration from a single control point
- Reduced manual server provisioning effort
- Achieved consistent software deployment across nodes
- Demonstrated Infrastructure as Code implementation
- Established foundation for scalable configuration management

---

## 🏆 Real-World Relevance

This automation model is commonly used in:

- Enterprise server provisioning
- Cloud VM configuration
- CI/CD environment preparation
- Microservices infrastructure setup
- DevOps production environments

Ansible-based automation is critical for maintaining consistency in distributed systems.

---

## 🛠 Skills Demonstrated

- Ansible Control Node setup
- Multi-node infrastructure automation
- Playbook development and execution
- Inventory-based host grouping
- Role-based service provisioning
- Infrastructure as Code practices

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(https://drive.google.com/file/d/1tTcaeAcFA_wVs7LqDeCO3o1xt-gEHhoY/view?usp=drive_link)*

---

## 📚 Course Context

This assignment is part of:

**Module 5 – Ansible**  
**DevOps Course**  
**DevOps Architect Master’s Program – Intellipaat**

---

