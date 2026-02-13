# 📦 Puppet – Node Classification & Host-Based Configuration Enforcement

---

## 📌 Overview

Executed host-based configuration enforcement using Puppet by implementing node identity-driven infrastructure management across multiple agents.

This task demonstrates environment-aware automation using hostname-based targeting.

---

## 🎯 Objective

Implement node classification logic to:

- Standardize hostnames across agents  
- Enforce host-specific configuration  
- Deploy differentiated file resources per node  
- Maintain idempotent state enforcement  

---

# 🏗 Architecture Implemented

Infrastructure consisted of:

- 1 Puppet Master  
- 3 Puppet Agents  
  - slave1  
  - slave2  
  - slave3  

Configuration enforcement was executed based on node identity.

---

# 🔄 Implementation Executed

✔ Defined consistent hostnames across managed nodes  
✔ Implemented conditional manifest logic based on node name  
✔ Enforced host-specific file creation inside `/tmp`  
✔ Deployed unique content per node  
✔ Maintained declarative desired-state enforcement  

Resulting configuration:

- slave1 → File containing “this is slave1”  
- slave2 → File containing “this is slave2”  
- slave3 → File containing “this is slave3”  

---

# 🛠 Execution Highlights

✔ Implemented node-level targeting logic  
✔ Applied differentiated configuration policies  
✔ Enforced file content consistency  
✔ Ensured automatic correction of manual changes  
✔ Achieved identity-driven infrastructure modeling  

---

# 🔐 Engineering Outcomes

✔ Enabled granular configuration control  
✔ Strengthened infrastructure governance  
✔ Prevented configuration drift  
✔ Improved automation precision  
✔ Demonstrated scalable node classification  

---

# 🧠 Skills Demonstrated

- Puppet Node Classification  
- Host-Based Configuration Management  
- Conditional Resource Enforcement  
- File Resource Automation  
- Idempotent Infrastructure Modeling  
- Multi-Node Governance  

---

# 📊 Enterprise Relevance

Identity-based configuration management is critical in:

- Role-based server environments  
- Multi-tier deployments  
- Policy-driven infrastructure  
- Compliance-segregated systems  
- Large-scale enterprise fleets  

---

# 📸 Validation & Evidence

📄 Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Puppet Module – DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
