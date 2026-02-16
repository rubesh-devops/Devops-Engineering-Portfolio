# 📊 Case Study – Continuous Monitoring using Nagios

---

## 📌 Business Scenario

Joined a startup as a DevOps Engineer where no monitoring system was implemented for production applications.

The company’s website was business-critical and required continuous uptime monitoring, CPU performance tracking, and rapid failure detection.

Designed and implemented a complete monitoring architecture using **Nagios Core** to ensure application reliability and infrastructure visibility.

---

## 🎯 Objective

✔ Deploy centralized monitoring architecture  
✔ Monitor production web application availability  
✔ Track CPU usage of production host  
✔ Reduce monitoring check interval to 1 minute  
✔ Ensure real-time failure detection  

---

## 🏗 Architecture Design

Infrastructure Components:

- AWS EC2 Instance (Nagios Server)
- AWS EC2 Instance (Production Server)
- Dockerized Web Application (hshar/webapp)
- NRPE for Remote Monitoring
- Service & Host Configuration Files

Architecture Flow:

Production Server  
⬇  
Web Application (Docker Container)  
⬇  
Nagios Master Monitoring  
⬇  
CPU & Service Health Checks  
⬇  
Dashboard & Alerts  

---

## ⚙️ Implementation Summary

### 1️⃣ Infrastructure Deployment

- Deployed two AWS EC2 servers  
  - Nagios Monitoring Server  
  - Production Application Server  
- Installed Nagios Core on Monitoring Server  
- Installed Docker on Production Server  
- Deployed hshar/webapp container  

Validated that web application was accessible via browser.

---

### 2️⃣ Application Monitoring Configuration

- Created service definition for website monitoring  
- Configured HTTP health checks  
- Associated service with production host  
- Reduced `check_interval` to 1 minute  

Enabled high-frequency monitoring for critical business application.

---

### 3️⃣ CPU Monitoring Configuration

- Installed monitoring plugins on production server  
- Configured CPU usage checks using NRPE  
- Defined warning and critical thresholds  
- Integrated CPU monitoring into Nagios dashboard  

Enabled proactive performance tracking.

---

### 4️⃣ Monitoring Validation

- Restarted Nagios service  
- Verified application status displayed as **OK**  
- Simulated container stop to test failure detection  
- Confirmed status changed to **CRITICAL** within 1 minute  
- Simulated high CPU usage and validated alert detection  

Continuous monitoring behavior successfully validated.

---

## 🧠 Skills Demonstrated

- Continuous Monitoring Architecture  
- Nagios Core Deployment  
- Dockerized Application Monitoring  
- CPU Performance Monitoring  
- NRPE Configuration  
- High-Frequency Check Optimization  
- Production System Observability  
- Failure Simulation & Validation  

---

## 🏢 Enterprise Relevance

This implementation reflects real-world DevOps practices:

- Business-critical application monitoring  
- Performance tracking & SLA compliance  
- Rapid failure detection (1-minute interval)  
- Containerized workload monitoring  
- Proactive infrastructure management  

Continuous monitoring is a core pillar of DevOps reliability engineering.

---

## 📊 Outcome

✔ Successfully deployed monitoring architecture  
✔ Enabled real-time website monitoring  
✔ Configured CPU usage tracking  
✔ Reduced detection latency to 1 minute  
✔ Validated application and infrastructure health visibility  

Continuous production monitoring successfully implemented using Nagios.

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Context

**Module – Nagios**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
