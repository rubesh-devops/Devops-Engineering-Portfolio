# 🌐 Hands-On 3 – Creating a Monitoring Service (Apache HTTP Monitoring)

---

## 📌 Overview

Extended the Nagios Master-Slave monitoring architecture by configuring an **HTTP service monitoring check** for a remote client.

Implemented web server monitoring to validate Apache availability and service health in real-time via Nagios Dashboard.

This hands-on demonstrates service-level monitoring beyond basic host availability checks.

---

# 🎯 Objective

✔ Install Apache on Slave (Client)  
✔ Verify Apache service availability  
✔ Configure HTTP service check in Nagios Master  
✔ Validate service monitoring via Nagios dashboard  

---

# 🏗 Architecture Context

- Nagios Master Server  
- Remote Linux Client (Slave)  
- NRPE Enabled  
- Apache Web Server  
- HTTP Service Monitoring Configuration  

This activity builds on the previously established Nagios Master-Slave setup.

---

# ⚙️ Implementation Summary

---

## 🔹 Phase 1 – Apache Installation on Client

- Installed Apache HTTP server on Slave machine  
- Verified service installation  
- Started and enabled Apache service  
- Confirmed web server availability via browser  

Validated that the web application service was running successfully before configuring monitoring.

---

## 🔹 Phase 2 – User & Access Configuration

- Completed required authentication setup  
- Verified web server response  
- Confirmed successful HTTP access from browser  

Ensured service accessibility prior to integrating with Nagios.

---

## 🔹 Phase 3 – Service Definition on Nagios Master

- Opened host configuration file on Master  
- Added new service definition for HTTP check  
- Linked service to the remote host  
- Defined appropriate check command  

Enabled Master to monitor Apache HTTP service on the client machine.

---

## 🔹 Phase 4 – Configuration Validation

- Verified Nagios configuration integrity  
- Restarted Nagios service  
- Ensured no syntax errors in configuration files  

Confirmed stable service monitoring configuration.

---

## 🔹 Phase 5 – Dashboard Verification

- Accessed Nagios Web Interface  
- Navigated to Services section  
- Verified new HTTP service entry  
- Confirmed status as **OK**  
- Observed alongside existing PING service  

Successfully validated real-time web server monitoring.

---

# 🧠 Skills Demonstrated

- Service-Level Monitoring Configuration  
- Apache HTTP Server Management  
- Nagios Service Definition Setup  
- Configuration Validation & Restart  
- Monitoring Dashboard Interpretation  
- Linux Service Administration  

---

# 🏢 Enterprise Relevance

Monitoring application services is critical in production environments:

- Website uptime validation  
- Early detection of web service failures  
- SLA compliance monitoring  
- Reduced downtime risk  
- Business continuity assurance  

Service-level monitoring is a core DevOps operational responsibility.

---

# 📊 Outcome

✔ Apache installed and verified on client  
✔ HTTP monitoring service configured on Master  
✔ Service successfully integrated into Nagios dashboard  
✔ Real-time web server monitoring achieved  
✔ Extended monitoring from host-level to service-level  

Nagios-based Web Server Monitoring successfully implemented.

---

# 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module – Nagios**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
