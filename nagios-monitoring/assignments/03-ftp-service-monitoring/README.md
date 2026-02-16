# 📊 Assignment 3 – FTP Service Monitoring using Nagios

---

## 📌 Project Overview

Extended the existing Nagios Master-Slave monitoring architecture to include **FTP service health monitoring**.

Configured service-level checks using Nagios configuration files to verify whether the FTP service is running and accessible on the monitored host.

This assignment demonstrates protocol-level monitoring capability beyond HTTP services.

---

## 🎯 Objective

✔ Use existing Nagios monitoring cluster  
✔ Configure FTP service monitoring  
✔ Validate FTP service availability  
✔ Detect service downtime scenarios  
✔ Confirm real-time status visibility in dashboard  

---

## ⚙️ Implementation Summary

### 1️⃣ Reusing Existing Monitoring Architecture

- Leveraged previously deployed Nagios Master-Slave setup  
- Verified host connectivity and monitoring status  
- Confirmed NRPE communication between nodes  

Ensured monitoring environment was operational before extending services.

---

### 2️⃣ FTP Service Preparation

- Installed FTP service on monitored host  
- Verified FTP daemon status  
- Confirmed port availability  

Prepared service for monitoring validation.

---

### 3️⃣ FTP Service Configuration in Nagios

- Created new service definition in Nagios configuration files  
- Configured check command for FTP protocol  
- Associated service with target host  
- Validated configuration syntax  

Integrated FTP monitoring into centralized dashboard.

---

### 4️⃣ Configuration Reload & Validation

- Restarted Nagios services  
- Verified successful configuration load  
- Confirmed FTP service status displayed as **OK**  

Simulated service stop to validate:

- Nagios correctly detected service failure  
- Service state changed to **CRITICAL**  

Monitoring behavior validated successfully.

---

## 🧠 Skills Demonstrated

- Service-Level Monitoring (FTP Protocol)  
- Nagios Configuration File Management  
- NRPE-Based Remote Monitoring  
- Linux Service Administration  
- Protocol & Port-Based Monitoring  
- Failure Simulation & Alert Validation  

---

## 🏢 Enterprise Relevance

FTP monitoring is critical in environments where:

- File transfers are business-critical  
- Backup operations depend on FTP  
- Data exchange pipelines rely on service uptime  
- Production systems require SLA compliance  

Demonstrates ability to monitor multiple service protocols in distributed systems.

---

## 📊 Outcome

✔ Successfully configured FTP service monitoring  
✔ Extended existing Nagios cluster capabilities  
✔ Validated real-time protocol health detection  
✔ Confirmed failure detection accuracy  
✔ Strengthened infrastructure observability  

FTP service monitoring successfully implemented using Nagios.

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Context

**Module – Nagios**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**

