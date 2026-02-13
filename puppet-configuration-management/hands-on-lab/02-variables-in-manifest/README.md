# 🧪 Hands-On Lab – Using Variables in Puppet Manifests

---

## 📌 Lab Overview

Implemented dynamic configuration management using variables within Puppet manifests to enhance flexibility and maintainability of infrastructure code.

This lab demonstrates how parameterization improves reusability and reduces hardcoded configurations in production environments.

---

## 🎯 Objective

Enhance Puppet automation by:

- Defining variables within Puppet manifests
- Using variables to manage service configuration
- Deploying file resources dynamically
- Enforcing consistent configuration on Puppet agents

---

# 🏗 Infrastructure Context

Environment:

- 1 Puppet Master
- 1 Puppet Agent
- Production environment directory structure used
- Manifest stored under:
  `production/manifests`

Automation Goal:

- Install required service (Apache)
- Create a file `/tmp/hello.txt`
- Use variables to control configuration logic

---

# 🔄 Implementation Executed

✔ Navigated to Puppet production manifest directory  
✔ Created manifest utilizing variables for configuration  
✔ Defined service and file resources dynamically  
✔ Triggered Puppet agent run for configuration enforcement  
✔ Verified web server deployment via browser  
✔ Confirmed file creation in `/tmp/hello.txt`  

Result:

- Apache service installed successfully  
- File resource deployed using manifest variable  
- Configuration executed idempotently  
- Infrastructure remained consistent on repeated runs  

---

# 🛠 Execution Highlights

✔ Implemented variable-driven manifest design  
✔ Reduced hardcoded configuration values  
✔ Improved readability of Puppet code  
✔ Demonstrated dynamic resource management  
✔ Validated successful Master–Agent configuration enforcement  

---

# 🔐 Engineering Outcomes

✔ Increased infrastructure flexibility  
✔ Enabled reusable configuration logic  
✔ Strengthened declarative automation model  
✔ Maintained idempotent system state  
✔ Improved maintainability of configuration code  

---

# 🧠 Skills Demonstrated

- Puppet Manifest Authoring  
- Variable Declaration & Usage  
- File Resource Management  
- Service Automation  
- Production Environment Configuration  
- Infrastructure as Code (IaC)  
- Idempotent Configuration Enforcement  

---

# 📊 Enterprise Relevance

Variable-driven configuration is widely used in:

- Multi-environment deployments  
- Parameterized infrastructure modules  
- Reusable configuration templates  
- Enterprise-scale automation systems  
- Production-grade infrastructure provisioning  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 4 – Puppet**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
