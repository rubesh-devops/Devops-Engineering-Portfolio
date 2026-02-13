# 🧪 Hands-On Lab – Creating & Deploying Custom Puppet Modules

---

## 📌 Lab Overview

Designed and deployed a custom Puppet module to enhance code modularity, reusability, and maintainability within the Puppet infrastructure.

This lab demonstrates how to package configuration logic into reusable modules and integrate them into the production environment.

---

## 🎯 Objective

Strengthen configuration management practices by:

- Creating a custom Puppet module
- Structuring module directories correctly
- Packaging and installing the module
- Integrating module into site manifest
- Enforcing configuration changes on agent nodes

---

# 🏗 Infrastructure Context

Environment:

- 1 Puppet Master
- 1 Puppet Agent
- Production environment (`production/site.pp`)

Automation Goal:

- Create custom module named "new"
- Define logic inside `init.pp`
- Deploy configuration via module
- Create `/tmp/module_test.txt` on agent
- Validate module-based configuration enforcement

---

# 🔄 Implementation Executed

✔ Created new Puppet module using module generator  
✔ Structured module directory under `/new/new/manifests`  
✔ Defined configuration logic inside `init.pp`  
✔ Packaged module into distributable archive  
✔ Installed module on Puppet Master  
✔ Included module inside `site.pp`  
✔ Triggered Puppet agent run  
✔ Verified file creation at `/tmp/module_test.txt`  

Result:

- Custom module successfully created  
- Module integrated into production environment  
- Configuration deployed via modular architecture  
- Infrastructure maintained idempotent behavior  

---

# 🛠 Execution Highlights

✔ Implemented modular configuration management  
✔ Improved readability and maintainability of code  
✔ Separated concerns using module structure  
✔ Reduced duplication across manifests  
✔ Validated reusable automation components  

---

# 🔐 Engineering Outcomes

✔ Achieved scalable configuration architecture  
✔ Enabled reusable infrastructure components  
✔ Improved long-term maintainability  
✔ Strengthened Puppet code organization  
✔ Demonstrated production-ready module deployment  

---

# 🧠 Skills Demonstrated

- Puppet Module Creation  
- init.pp Manifest Authoring  
- Module Packaging & Installation  
- site.pp Integration  
- Reusable Infrastructure Components  
- Infrastructure as Code (IaC)  
- Modular Configuration Architecture  

---

# 📊 Enterprise Relevance

Module-based architecture is widely used in:

- Enterprise-scale configuration management  
- Large infrastructure teams  
- Multi-environment deployments  
- Reusable automation libraries  
- DevOps governance frameworks  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 4 – Puppet**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
