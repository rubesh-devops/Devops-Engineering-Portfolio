# 📦 Assignment – Conditional Content Management based on Service State using Puppet

---

## 📌 Assignment Overview

Extended the existing Puppet deployment to implement **conditional file content management** based on installed web server type.

This assignment demonstrates Puppet’s ability to dynamically enforce configuration changes depending on service presence across managed nodes.

---

## 🎯 Objective

Enhance the infrastructure to:

- Detect installed web server (Apache or NGINX)  
- Modify application content conditionally  
- Enforce different index.html content per node  
- Maintain idempotent configuration behavior  
- Ensure consistent service-based content alignment  

---

# 🏗 Infrastructure Context

Using the previously configured Puppet environment:

- **1 Puppet Master**
- **3 Puppet Agents**
  - Apache installed on specific nodes  
  - NGINX installed on designated node  

Architecture supports differentiated configuration enforcement.

---

# 🔄 Implementation Strategy

---

## 🔹 Service State Detection

Enhanced Puppet manifests to:

- Identify whether Apache service is installed  
- Identify whether NGINX service is installed  
- Apply conditional logic based on detected state  

This enables service-aware configuration modeling.

---

## 🔹 Conditional File Management

Implemented file resource logic to:

- Modify `index.html` to display  
  - “apache is installed” when Apache present  
  - “nginx is installed” when NGINX present  
- Enforce file content consistency  
- Ensure automatic correction if content is altered manually  

This validates Puppet’s declarative desired-state enforcement.

---

## 🔹 Idempotent Execution Validation

Ensured:

- Repeated Puppet runs do not cause unnecessary changes  
- File content remains consistent with defined state  
- Configuration drift is automatically corrected  

---

# 🛠 Execution Highlights

✔ Reused existing Puppet deployment  
✔ Implemented service-aware conditional logic  
✔ Enforced dynamic content modification  
✔ Maintained idempotent behavior  
✔ Achieved differentiated node configuration  
✔ Validated automatic configuration correction  

---

# 🔐 DevOps Engineering Outcomes

✔ Enabled intelligent configuration enforcement  
✔ Prevented service-content mismatch  
✔ Strengthened infrastructure state consistency  
✔ Demonstrated advanced declarative automation  
✔ Reduced manual content management overhead  

---

# 🧠 DevOps Skills Demonstrated

- **Conditional Manifest Logic**
- **Service-Based Configuration Modeling**
- **File Resource Management**
- **Dynamic Infrastructure Enforcement**
- **Idempotent Automation**
- **Multi-Service Environment Governance**
- **Configuration Drift Mitigation**

---

# 📊 Enterprise Relevance

Service-aware configuration management is critical in:

- Multi-application infrastructure  
- Hybrid web server environments  
- Canary and Blue-Green deployment strategies  
- Infrastructure standardization efforts  
- Automated compliance enforcement  

This reflects production-grade configuration management practices.

---

# 📸 Validation & Evidence

📄 **Assignment Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

This assignment is part of:

**Puppet Module – DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
