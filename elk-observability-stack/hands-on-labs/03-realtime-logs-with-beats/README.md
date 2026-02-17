# 🔴 Hands-On 3 – Real-Time Log Monitoring using Filebeat, Elasticsearch & Kibana

## 📌 Objective

Implemented real-time log ingestion using **Filebeat modules**, streamed logs into **Elasticsearch**, and built interactive visual dashboards in **Kibana**.

This hands-on demonstrates:

- ⚡ Real-time log collection using Beats
- 🔄 Module-based log configuration
- 📊 Advanced Kibana visualizations
- 🌍 Geo-based HTTP analytics
- 📈 Dashboard creation
- 🧠 Observability implementation

---

## 🏗 Environment Setup

- ELK Stack Installed (Elasticsearch, Logstash, Kibana)
- Filebeat Installed
- NGINX Web Server
- Ubuntu Environment

---

## ⚙️ Implementation Summary

### 1️⃣ Enabled Filebeat Modules

Enabled required modules:

- System logs
- NGINX logs

Configured:

- Syslog path
- Auth log path
- NGINX access logs
- NGINX error logs

Started Filebeat service to begin real-time log streaming.

---

### 2️⃣ Verified Data Ingestion

- Created `filebeat*` index pattern in Kibana
- Selected `@timestamp` field
- Confirmed real-time log ingestion from system & nginx

---

## 📊 Visualization & Analytics Implementation

---

### 📈 Line Graph Visualization – Apache HTTP Requests

Created Area Visualization:

- Y-Axis → Count aggregation
- X-Axis → Response Keyword
- Custom Label → HTTP Requests

Enhanced analysis by visualizing:

- 🌍 GeoIP Country
- 🌎 Timezone-based traffic
- 📦 Response code distribution

Saved visualization as:

```
[apache] Total Requests based on TimeZone
```

---

### 🔥 Heatmap Visualization – Crime Dataset

Created Heatmap Visualization:

- X-Axis → FBI Code
- Aggregation → Count
- Customized legend position
- Applied color schema & scale

This demonstrated:

- 🔎 Category-based log clustering
- 📊 Data density distribution
- 🔍 Hit-based analytics

---

### 🌍 Geo Coordinate Map – HTTP Request Origin

Created Coordinate Map Visualization:

- Bucket → Geo Coordinates
- Aggregation → Geohash
- Field → geoip.location

This enabled:

- 🌐 Geographic traffic distribution
- 🌎 Location-based request analysis
- 📡 Traffic origin insights

Saved as:

```
[apache] Geo IP
```

---

## 📊 Dashboard Creation

Created a consolidated dashboard:

- Added Geo IP visualization
- Added Total Requests visualization
- Resized panels for better observability

Saved Dashboard as:

```
Apache Monitoring Dashboard
```

---

## 📈 NGINX Real-Time Dashboard (Filebeat ECS)

Created index pattern:

```
filebeat*
```

Loaded pre-built NGINX dashboards:

- NGINX Overview ECS
- Real-time request monitoring
- Traffic distribution analytics
- Error rate visualization
- Status code breakdown

Validated real-time monitoring by generating web traffic and refreshing dashboards.

---

## 🧠 Advanced Observability Features Identified

- Machine Learning (Anomaly Detection)
- Automated Reporting
- Alerting & Notification Systems

(Note: These features require enterprise licensing)

---

## 💡 Skills Demonstrated

- Filebeat module configuration
- Real-time log streaming
- ELK integration
- GeoIP-based log analysis
- Kibana visualization design
- Dashboard engineering
- Log aggregation architecture
- Production-grade observability setup

---

## 🚀 Outcome

Successfully implemented a **real-time centralized logging & observability pipeline** using:

- Filebeat
- Elasticsearch
- Kibana

Built advanced dashboards for:

- Traffic analytics
- Error monitoring
- Geo-location insights
- Service visibility

This completes the **Observability Layer** in the DevOps Engineering Portfolio.

---

## 📸 Validation & Evidence

📄 **Execution Documentation & Screenshots**  
👉 Google Drive: *(Link to be updated)*  

---

### 📚 Module Reference

**Module – ELK Stack (Elasticsearch, Logstash, Kibana)**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
