# 📊 Assignment 4 – FTP Service Health Validation using Nagios

---

## 📌 Project Overview

Extended the existing Nagios Master-Slave monitoring cluster to validate and monitor the **FTP service availability** using configuration-driven service definitions.

This assignment reinforces service-level monitoring capabilities and validates monitoring accuracy using structured Nagios configuration files.

---

## 🎯 Objective

✔ Reuse existing Nagios monitoring cluster  
✔ Configure FTP service monitoring via configuration files  
✔ Validate FTP service availability  
✔ Detect downtime scenarios  
✔ Confirm monitoring accuracy through dashboard  

---

## ⚙️ Implementation Summary

### 1️⃣ Existing Monitoring Cluster Validation

- Verified Nagios Master status  
- Confirmed communication with monitored hosts  
- Validated NRPE service execution  

Ensured monitoring environment was operational before adding additional service checks.

---

### 2️⃣ FTP Service Preparation

- Verified FTP service installation on monitored host  
- Confirmed FTP daemon running state  
- Checked default FTP port availability  

Prepared service for monitoring integration.

---

### 3️⃣ Service Configuration in Nagios

- Updated service configuration files  
- Defined FTP service check command  
- Associated FTP service with target host  
- Validated configuration integrity  

Integrated FTP service monitoring into centralized dashboard.

---

### 4️⃣ Monitoring & Failure Simulation

- Restarted Nagios service  
- Verified FTP service displayed as **OK**  
- Simulated FTP service stop  
- Confirmed Nagios detected state change to **CRITICAL**  

Successfully validated monitoring responsiveness and accuracy.

---

## 🧠 Skills Demonstrated

- Nagios Service Configuration Management  
- FTP Protocol Monitoring  
- NRPE-Based Remote Monitoring  
- Linux Service Administration  
- Real-Time Monitoring Validation  
- Failure Simulation & Detection  

---

## 🏢 Enterprise Relevance

FTP monitoring is critical in enterprise environments for:

- Secure file transfers  
- Backup and archival systems  
- Data integration pipelines  
- Business-critical data exchange  
- SLA monitoring & compliance  

This assignment demonstrates capability to monitor application-layer services in distributed environments.

---

## 📊 Outcome

✔ Successfully configured FTP monitoring  
✔ Validated real-time service detection  
✔ Confirmed failure notification capability  
✔ Strengthened monitoring architecture  
✔ Demonstrated configuration-driven observability  

FTP service monitoring successfully implemented and validated.

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Context

**Module – Nagios**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
