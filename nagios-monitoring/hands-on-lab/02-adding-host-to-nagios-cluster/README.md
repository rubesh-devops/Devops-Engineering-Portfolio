# 🖥 Hands-On 2 – Adding a Host in Nagios (Master-Slave Integration)

---

## 📌 Overview

Extended the Nagios monitoring architecture by integrating a remote host (Slave) into the existing Nagios Master setup.

Configured NRPE-based remote monitoring, installed required plugins, and validated host availability through the Nagios dashboard.

This hands-on establishes distributed infrastructure monitoring capability.

---

# 🎯 Objective

✔ Install NRPE on Slave  
✔ Configure Master IP access on Slave  
✔ Install Check_NRPE on Master  
✔ Configure host definition in Nagios  
✔ Validate host monitoring via dashboard  

---

# 🏗 Architecture Components

- Nagios Master Server  
- Remote Linux Slave Host  
- NRPE (Remote Plugin Executor)  
- Check_NRPE Plugin  
- Nagios Host Configuration Files  

---

# ⚙️ Implementation Summary

---

## 🔹 Phase 1 – NRPE Installation on Slave

### Slave Preparation

- Installed NRPE service on Slave machine  
- Installed required Nagios monitoring plugins  
- Opened NRPE configuration file  
- Updated `allowed_hosts` parameter to include Master IP  
- Restarted NRPE service  

Enabled secure communication between Master and Slave.

---

## 🔹 Phase 2 – Installing Check_NRPE on Master

### Master Configuration

- Installed Check_NRPE dependencies  
- Downloaded Check_NRPE source package  
- Extracted and compiled plugin  
- Installed plugin binaries  
- Verified plugin functionality  

Ensured Master could execute remote checks on Slave.

---

## 🔹 Phase 3 – Host Configuration in Nagios

### Host Definition Setup

- Created new host configuration file  
- Defined Slave host details  
- Configured PING service check  
- Linked host to monitoring group  
- Included configuration file in Nagios config directory  

Integrated Slave host into centralized monitoring system.

---

## 🔹 Phase 4 – Configuration Validation

- Verified Nagios configuration integrity  
- Restarted Nagios service  
- Confirmed no syntax or dependency errors  

Ensured monitoring environment stability.

---

## 🔹 Phase 5 – Monitoring Dashboard Verification

- Accessed Nagios web interface  
- Verified Slave host status as **UP**  
- Confirmed PING service status as **OK**  
- Observed connection topology via monitoring Map  

Successfully validated Master-Slave integration.

---

# 🧠 Skills Demonstrated

- Distributed Infrastructure Monitoring  
- NRPE Remote Execution Configuration  
- Plugin Compilation & Installation  
- Host Definition Management  
- Monitoring Dashboard Validation  
- Linux Service Management  
- Network-Based Health Checks  

---

# 🏢 Enterprise Relevance

Adding remote hosts is essential in enterprise monitoring environments:

- Monitor multiple production servers  
- Centralized infrastructure visibility  
- Secure remote execution of health checks  
- Real-time availability monitoring  
- Scalable monitoring architecture  

Forms the backbone of enterprise observability systems.

---

# 📊 Outcome

✔ Successfully installed NRPE on Slave  
✔ Configured Master-Slave communication  
✔ Added remote host into Nagios dashboard  
✔ Validated host and PING monitoring  
✔ Confirmed distributed monitoring architecture  

Nagios Master-Slave host integration successfully implemented.

---

# 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module – Nagios**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
