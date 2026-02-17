# 🔍 Hands-On 1 – Analyzing Apache Logs with Logstash & Kibana
## ELK Observability Implementation

## 📘 Objective

To implement centralized log ingestion using Logstash, process Apache logs using Grok filters, index structured data into Elasticsearch, and visualize log insights in Kibana.

This hands-on demonstrates real-world log analysis and observability implementation using ELK Stack.

---

## 🧱 Environment Setup

- Logstash configured for file-based log ingestion  
- Elasticsearch running on localhost  
- Kibana dashboard configured  
- Sample Apache logs collected for processing  

---

## 🚀 Implementation Workflow

### 1️⃣ Log Collection

- Downloaded sample Apache log dataset  
- Copied logs into local Apache log file  
- Verified log entries before ingestion  

This ensured raw logs were ready for pipeline processing.

---

### 2️⃣ Logstash Pipeline Configuration

Created a custom Logstash configuration file inside `/etc/logstash/conf.d`.

The pipeline included:

- **Input Section**
  - File-based ingestion from Apache log file
  - Started reading from beginning
  - Disabled sincedb for repeated testing

- **Filter Section**
  - Grok filter using COMBINEDAPACHELOG pattern
  - Date filter to normalize timestamps
  - GeoIP filter to enrich logs with geographic data

- **Output Section**
  - Indexed structured logs into Elasticsearch
  - Custom index name: `petclinic-prd-1`

This converted raw Apache logs into structured searchable JSON documents.

---

### 3️⃣ Logstash Service Execution

- Started Logstash service
- Verified service status
- Confirmed data flow into Elasticsearch

---

### 4️⃣ Kibana Visualization & Analysis

Inside Kibana:

- Created new Index Pattern: `petclinic-prd-1*`
- Selected `@timestamp` as time filter
- Accessed Discover tab to view structured logs

Performed advanced searches:

- Filter by geographic field: `geoip.city_name.keyword`
- Filter by agent field
- Used KQL queries for structured filtering
- Applied time-based filters (Last 15 mins, Last 10 days)
- Added and removed dynamic filters from dashboard

---

## 📊 Observability Capabilities Achieved

- Structured Apache log parsing  
- Real-time Elasticsearch indexing  
- GeoIP enrichment for traffic analysis  
- Keyword-based filtering using KQL  
- Time-based log analysis  
- Interactive dashboard filtering  

---

## 🧠 DevOps Skills Demonstrated

- Logstash Pipeline Configuration  
- Grok Pattern Parsing  
- Timestamp Normalization  
- GeoIP Data Enrichment  
- Elasticsearch Index Management  
- Kibana Index Pattern Creation  
- KQL Log Querying  
- Time-Series Log Analysis  

---

## 📈 Business Value

This implementation enables:

- Faster root cause analysis  
- Geo-based traffic monitoring  
- Improved troubleshooting efficiency  
- Centralized visibility into application logs  
- Production-ready logging architecture  

---

## 📸 Validation & Evidence

Consolidated Execution Documentation  
Google Drive: (Documentation link will be updated)

Screenshots include:

- Logstash configuration  
- Logstash running status  
- Elasticsearch indexed data  
- Kibana index pattern creation  
- Discover view with filtered logs  

---

## 🎯 Outcome

Successfully implemented a structured Apache log ingestion pipeline using Logstash and analyzed enriched logs through Kibana dashboards.

This hands-on validates production-level centralized logging and observability implementation using ELK Stack.
