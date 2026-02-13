# 📦 Assignment – Conditional Resource Management & NGINX Deployment using Puppet

---

## 📌 Assignment Overview

Extended the existing Puppet Master-Agent architecture by introducing an additional managed node and implementing **conditional configuration logic** to dynamically provision services based on system state.

This assignment demonstrates Puppet’s capability to enforce intelligent configuration decisions using declarative logic.

---

## 🎯 Objective

Enhance the Puppet infrastructure to:

- Scale the environment by adding a new agent node  
- Implement conditional resource execution  
- Detect Apache installation state  
- Deploy NGINX only when Apache is already present  
- Enforce differentiated configuration across nodes  

---

# 🏗 Architecture Enhancement

Expanded the Puppet setup to include:

- **1 Puppet Master (Control Node)**
- **3 Puppet Agents (Managed Nodes)**

Infrastructure now supports:

- Multi-node configuration enforcement  
- State-aware resource management  
- Conditional service provisioning  

This simulates real-world scalable infrastructure growth.

---

# 🔄 Implementation Strategy

---

## 🔹 Agent Expansion

Integrated an additional slave node into the Puppet ecosystem by:

- Installing Puppet agent  
- Registering and signing certificate  
- Validating secure Master-Agent communication  
- Ensuring configuration pull functionality  

This enabled centralized governance for the new node.

---

## 🔹 Conditional Configuration Logic

Enhanced Puppet manifest with:

- Conditional checks for Apache installation  
- Dynamic resource declaration based on system state  
- Controlled NGINX installation only when criteria matched  

This demonstrates Puppet’s declarative yet logic-driven configuration capabilities.

---

## 🔹 Service Enforcement Outcome

Final configuration state:

- Existing slaves retained Apache configuration  
- Newly added slave satisfied conditional rule  
- NGINX installed automatically on the third slave  

This validates state-based infrastructure orchestration.

---

# 🛠 Execution Highlights

✔ Scaled Puppet environment with new agent node  
✔ Implemented conditional resource logic  
✔ Automated intelligent service provisioning  
✔ Enforced differentiated node configuration  
✔ Maintained idempotent infrastructure behavior  
✔ Validated desired state enforcement  

---

# 🔐 DevOps Engineering Outcomes

✔ Enabled scalable infrastructure growth  
✔ Introduced intelligent configuration automation  
✔ Reduced manual configuration branching  
✔ Prevented configuration duplication  
✔ Strengthened infrastructure consistency  
✔ Demonstrated dynamic configuration governance  

---

# 🧠 DevOps Skills Demonstrated

- **Puppet Agent Scaling**
- **Conditional Resource Management**
- **State-Based Infrastructure Automation**
- **Declarative Logic Implementation**
- **Multi-Node Configuration Governance**
- **Infrastructure Drift Control**
- **Service Lifecycle Automation**

---

# 📊 Enterprise Relevance

Conditional automation is critical in:

- Heterogeneous infrastructure environments  
- Blue-Green deployment models  
- Gradual service migration scenarios  
- Hybrid application stacks  
- Policy-based infrastructure enforcement  

This reflects advanced configuration management patterns used in enterprise DevOps ecosystems.

---

# 📸 Validation & Evidence

📄 **Assignment Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

This assignment is part of:

**Puppet Module – DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
