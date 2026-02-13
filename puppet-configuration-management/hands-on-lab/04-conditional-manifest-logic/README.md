# 🧪 Hands-On Lab – Conditional Logic in Puppet Manifests (onlyif & unless)

---

## 📌 Lab Overview

Implemented advanced conditional logic in Puppet manifests using **onlyif** and **unless** attributes to control configuration execution based on system state.

This lab demonstrates environment-aware automation and intelligent service deployment strategies using declarative infrastructure principles.

---

## 🎯 Objective

Enhance configuration management by:

- Implementing conditional resource execution
- Applying onlyif and unless logic controls
- Managing file and service deployment dynamically
- Preventing redundant installations
- Strengthening idempotent infrastructure behavior

---

# 🏗 Infrastructure Context

Environment:

- 1 Puppet Master
- 1 Puppet Agent
- Production manifest directory used

Automation Goals:

- Create file `/tmp/software.txt` conditionally
- Control resource execution using onlyif
- Apply inverse logic using unless
- Install NGINX only if Apache2 is not installed

---

# 🔄 Implementation Executed

### ✔ Conditional Execution using “onlyif”

- Updated Puppet manifest in production environment
- Applied onlyif logic to control resource execution
- Executed Puppet agent run
- Verified file creation at `/tmp/software.txt`

Result:
File created only when defined condition was satisfied.

---

### ✔ Conditional Execution using “unless”

- Updated manifest using unless logic
- Applied inverse condition control
- Triggered Puppet agent enforcement
- Verified `/tmp/software.txt` existence

Result:
Resource executed only when condition was NOT met.

---

### ✔ Conditional Service Installation

- Implemented logic to:
  - Install NGINX only if Apache2 is not installed
- Ensured no service conflict between Apache and NGINX
- Maintained idempotent execution behavior

Result:
Service installation occurred only when appropriate.

---

# 🛠 Execution Highlights

✔ Implemented state-aware automation  
✔ Reduced unnecessary configuration runs  
✔ Applied intelligent service detection  
✔ Prevented conflicting service installations  
✔ Maintained clean manifest structure  

---

# 🔐 Engineering Outcomes

✔ Achieved environment-driven deployment logic  
✔ Strengthened infrastructure decision-making automation  
✔ Improved system efficiency  
✔ Maintained declarative configuration integrity  
✔ Demonstrated production-ready configuration patterns  

---

# 🧠 Skills Demonstrated

- Puppet Conditional Logic  
- onlyif & unless Execution Controls  
- File Resource Automation  
- Service State Detection  
- NGINX & Apache Configuration Management  
- Idempotent Infrastructure Design  
- Advanced Manifest Structuring  

---

# 📊 Enterprise Relevance

Conditional automation is widely used in:

- Production-grade infrastructure deployments  
- Dynamic service provisioning  
- Role-based configuration management  
- Preventing service conflicts  
- Multi-environment automation pipelines  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 4 – Puppet**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
