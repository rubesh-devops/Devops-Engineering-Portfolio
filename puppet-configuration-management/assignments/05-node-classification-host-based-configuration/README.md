# 📦 Assignment – Node Classification & Host-Based Configuration using Puppet

---

## 📌 Assignment Overview

Enhanced the existing Puppet deployment by implementing **node-specific configuration management** using hostname-based targeting.

This assignment demonstrates Puppet’s ability to differentiate infrastructure behavior based on node identity and enforce host-level configuration policies.

---

## 🎯 Objective

Strengthen infrastructure governance by:

- Defining consistent hostnames across managed nodes  
- Implementing node-level configuration targeting  
- Creating host-specific file resources  
- Enforcing differentiated configuration policies  
- Maintaining idempotent infrastructure behavior  

---

# 🏗 Infrastructure Context

Using the previously configured Puppet architecture:

- **1 Puppet Master**
- **3 Puppet Agents**
  - slave1  
  - slave2  
  - slave3  

This assignment focuses on identity-driven configuration management.

---

# 🔄 Implementation Strategy

---

## 🔹 Hostname Standardization

Defined and enforced consistent hostnames:

- slave1  
- slave2  
- slave3  

This enables predictable infrastructure classification and targeted configuration logic.

---

## 🔹 Node-Specific Resource Enforcement

Implemented conditional Puppet manifests to:

- Identify node based on hostname  
- Create unique file resource per node  
- Populate file content specific to each slave  

Configuration behavior:

- On slave1 → File created with content “this is slave1”  
- On slave2 → File created with content “this is slave2”  
- On slave3 → File created with content “this is slave3”  

This ensures clear node-level configuration differentiation.

---

## 🔹 Idempotent State Validation

Ensured that:

- Files are created only if absent  
- Content remains consistent across Puppet runs  
- Manual modification is automatically corrected  
- Configuration drift is prevented  

---

# 🛠 Execution Highlights

✔ Defined consistent hostnames across agents  
✔ Implemented node classification logic  
✔ Created host-specific file resources  
✔ Enforced differentiated configuration per node  
✔ Maintained idempotent execution  
✔ Validated automatic configuration correction  

---

# 🔐 DevOps Engineering Outcomes

✔ Enabled identity-based configuration governance  
✔ Improved infrastructure clarity  
✔ Strengthened node-level policy enforcement  
✔ Reduced configuration ambiguity  
✔ Enhanced automation precision  
✔ Prevented configuration drift  

---

# 🧠 DevOps Skills Demonstrated

- **Puppet Node Classification**
- **Hostname-Based Targeting**
- **Conditional Resource Logic**
- **File Resource Management**
- **Declarative Infrastructure Enforcement**
- **Idempotent Automation Design**
- **Multi-Node Governance Modeling**

---

# 📊 Enterprise Relevance

Node-based configuration management is essential in:

- Role-based server environments  
- Multi-tier application stacks  
- Clustered infrastructure deployments  
- Compliance-driven infrastructure segregation  
- Environment-specific policy enforcement  

This reflects enterprise-level infrastructure governance practices.

---

# 📸 Validation & Evidence

📄 **Assignment Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

This assignment is part of:

**Puppet Module – DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
