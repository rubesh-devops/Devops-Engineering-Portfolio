# 🛠 Hands-On 1 – Nagios Core Installation & Master-Slave Setup

---

## 📌 Overview

Implemented complete Nagios monitoring setup including:

- Nagios Core installation on Master
- NRPE installation on Slave
- Check_NRPE plugin configuration on Master

This hands-on establishes the foundational monitoring architecture required for enterprise infrastructure observability.

---

# 🎯 Objective

✔ Install Nagios Core on Master server  
✔ Configure Apache integration for Nagios UI  
✔ Install and configure NRPE on Slave  
✔ Install Check_NRPE plugin on Master  
✔ Validate monitoring dashboard functionality  

---

# 🏗 Architecture Components

- Nagios Master Server
- Remote Slave Server
- NRPE (Nagios Remote Plugin Executor)
- Nagios Plugins
- Apache Web Server
- Monitoring Dashboard Interface

---

# ⚙️ Implementation Summary

---

## 🔹 Phase 1 – Installing Nagios Core on Master

### Environment Preparation

- Updated package index
- Installed required dependencies
- Configured build environment

Ensured system readiness for Nagios installation.

---

### User & Permission Configuration

- Created Nagios user and group
- Assigned necessary permissions
- Configured Apache user access
- Secured web interface authentication

Prepared system for secure monitoring access.

---

### Nagios Core Installation

- Downloaded Nagios Core source package
- Extracted installation archive
- Executed configuration scripts
- Compiled and installed Nagios Core
- Installed init scripts and configuration files
- Enabled command mode
- Copied event handler scripts

Successfully completed core monitoring engine setup.

---

### Apache Web Configuration

- Created Apache configuration for Nagios
- Configured authentication settings
- Enabled required modules
- Restarted Apache service

Activated Nagios web dashboard access.

---

### Nagios Plugins Installation

- Downloaded Nagios plugins
- Extracted plugin package
- Compiled and installed plugins
- Updated configuration references
- Verified plugin directory integrity

Enabled service and host monitoring capabilities.

---

### Configuration Validation & Service Start

- Updated base configuration files
- Enabled additional configuration directories
- Verified configuration integrity
- Started Nagios service
- Confirmed no configuration errors

Successfully launched Nagios Master instance.

---

## 🔹 Phase 2 – Installing NRPE on Slave

- Installed NRPE package on Slave
- Configured allowed hosts (Master IP)
- Enabled required monitoring ports
- Verified NRPE service status

Enabled secure remote execution of monitoring checks.

---

## 🔹 Phase 3 – Installing Check_NRPE Plugin on Master

- Installed Check_NRPE plugin
- Configured communication with Slave
- Validated remote check execution
- Confirmed successful host connectivity

Established Master-to-Slave monitoring communication.

---

# 🧠 Skills Demonstrated

- Nagios Core Installation from Source  
- Apache Web Server Integration  
- Linux User & Permission Management  
- NRPE Remote Monitoring Configuration  
- Plugin Compilation & Installation  
- Monitoring Architecture Setup  
- Configuration Validation & Debugging  

---

# 🏢 Enterprise Relevance

This setup mirrors real-world monitoring infrastructure:

- Centralized monitoring server  
- Distributed host monitoring  
- Secure remote plugin execution  
- Web-based observability dashboard  
- Production-grade monitoring foundation  

Forms the base layer for continuous monitoring and alerting systems.

---

# 📊 Outcome

✔ Successfully installed Nagios Core  
✔ Configured Apache-based monitoring UI  
✔ Enabled NRPE remote monitoring  
✔ Installed and validated plugins  
✔ Verified operational monitoring dashboard  

Nagios Master-Slave monitoring foundation successfully implemented.

---

# 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module – Nagios**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
