# 🔍 Hands-On 2 – Analyzing CSV Logs using Logstash & Kibana

## 📌 Objective

Implemented structured log ingestion using **Logstash CSV filter**, indexed data into **Elasticsearch**, and performed advanced log analysis & filtering in **Kibana**.

This hands-on demonstrates:

- 📂 Static CSV ingestion
- 🔄 Logstash pipeline configuration
- 📊 Index creation in Elasticsearch
- 🔎 Advanced filtering in Kibana
- 💾 Query saving & reuse

---

## 🏗 Environment Setup

- ELK Stack Installed (Elasticsearch, Logstash, Kibana)
- Ubuntu Server
- CSV dataset downloaded from public repository

---

## ⚙️ Implementation Summary

### 1️⃣ Downloaded Sample CSV Dataset

- Navigated to working directory
- Downloaded `crimes_2001.csv`
- Verified file contents

---

### 2️⃣ Configured Logstash Pipeline

Created a new Logstash configuration file inside:

`/etc/logstash/conf.d/`

Configured:

- **Input Plugin** → File input
- **Filter Plugin** → CSV filter
- **Output Plugin** → Elasticsearch output

### 🔎 Logstash Configuration Highlights

- Parsed CSV columns explicitly
- Defined separator as comma
- Indexed logs under custom index: `crimes`
- Configured Elasticsearch host on port 9200

---

### 3️⃣ Restarted Logstash Service

Logstash pipeline restarted to begin ingestion process.

Verified no configuration errors.

---

### 4️⃣ Created Index Pattern in Kibana

Navigated to:

Kibana → Stack Management → Index Patterns

Created index pattern:

```
crimes*
```

Selected `@timestamp` field.

---

### 5️⃣ Log Analysis in Kibana

Navigated to:

Kibana → Discover

Performed:

- Keyword filtering
- Multi-condition filtering
- Date-based filtering
- Field-based filtering
- Combined query filtering using AND operator

### Example Filtering Scenarios

- Filter by FBI Code
- Filter by Date
- Combined filters (Example: FBI Code + Date)
- Applied time-based filters (Last 10 mins / 15 days)

---

### 6️⃣ Saved Queries for Reusability

- Saved complex filter queries
- Reopened saved searches using "Open"
- Demonstrated reusable dashboard-style analysis

---

## 🧠 Skills Demonstrated

- Logstash CSV filter configuration
- Elasticsearch index management
- Kibana query language (KQL)
- Advanced filtering logic
- Time-based log filtering
- Saved search creation
- Structured log parsing
- Production-style centralized logging

---

## 🚀 Outcome

Successfully implemented a **structured CSV log ingestion pipeline** into ELK and performed real-time searchable analytics using Kibana.

This strengthens the **Observability & Monitoring layer** of the DevOps Engineering Portfolio.

---

## 📸 Validation & Evidence

📄 **Execution Documentation & Screenshots**  
👉 Google Drive: *(Link to be updated)*  

---

### 📚 Module Reference

**Module – ELK Stack (Elasticsearch, Logstash, Kibana)**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
