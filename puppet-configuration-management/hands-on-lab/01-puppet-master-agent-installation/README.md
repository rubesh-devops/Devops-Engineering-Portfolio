# 🧪 Hands-On Lab – Puppet Master–Agent Installation & Cluster Configuration

---

## 📌 Lab Overview

Designed and implemented a complete Puppet Master–Agent infrastructure using Ubuntu-based virtual machines.

Established secure certificate-based communication between Puppet Master and Agent nodes, enabling centralized configuration management across distributed systems.

---

## 🎯 Objective

Build a production-style Puppet environment by:

- Installing Puppet Master on Ubuntu 18.04
- Installing Puppet Agent on slave node
- Configuring secure communication
- Enabling certificate-based authentication
- Establishing a functional Puppet cluster

---

# 🏗 Infrastructure Environment

Environment Configuration:

- Ubuntu 18.04 AMI
- Instance Type: t2.micro
- Security Group: All Traffic (Lab Environment)
- Port 8140 configured for Puppet communication

Architecture:

- 1 Puppet Master
- 1 Puppet Agent (Slave)

---

# 🔄 Implementation Executed

✔ Installed Puppet Master on Ubuntu system  
✔ Installed Puppet Agent on slave node  
✔ Configured Puppet Master configuration file  
✔ Opened port 8140 for Master–Agent communication  
✔ Updated `/etc/hosts` for proper name resolution  
✔ Configured directory structure for Puppet services  
✔ Enabled Puppet Agent service to start on boot  
✔ Generated and signed certificates for secure communication  

Result:

- Master and Agent successfully authenticated  
- Puppet cluster established  
- Certificate trust model implemented  
- Ready for centralized configuration management  

---

# 🔐 Security & Configuration Highlights

✔ Enabled certificate signing workflow  
✔ Secured Master–Agent communication  
✔ Implemented hostname resolution consistency  
✔ Ensured service auto-start on reboot  
✔ Established scalable configuration foundation  

---

# 🛠 Execution Highlights

✔ Built full Puppet cluster from scratch  
✔ Implemented certificate-based trust model  
✔ Configured networking for configuration management  
✔ Validated successful agent registration  
✔ Prepared environment for manifest deployment  

---

# 🧠 Skills Demonstrated

- Puppet Master–Agent Architecture  
- Certificate Signing & Node Authentication  
- Ubuntu Server Configuration  
- Linux Networking & Port Configuration  
- Infrastructure Setup Automation  
- Configuration Management Foundations  

---

# 📊 Enterprise Relevance

This setup model is used in:

- Enterprise configuration management systems  
- Large-scale infrastructure automation  
- Multi-node server fleet management  
- Production-grade provisioning environments  
- Infrastructure standardization projects  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 4 – Puppet**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
