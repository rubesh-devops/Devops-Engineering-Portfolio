# 📦 Puppet – Conditional Multi-Node Service Deployment

---

## 📌 Overview

Expanded the existing Puppet infrastructure by onboarding a new agent node and implementing conditional service-based deployment logic.

Designed automation logic such that if Apache is already installed on existing nodes, NGINX is deployed automatically on the newly added slave node.

This assignment demonstrates adaptive configuration management using Puppet manifests.

---

## 🎯 Objective

Enhance infrastructure automation by:

- Adding a new Puppet Agent to the cluster
- Applying conditional logic inside Puppet manifests
- Deploying different services based on current system state
- Maintaining consistent and idempotent configuration enforcement

---

# 🏗 Infrastructure Architecture

Environment:

- 1 Puppet Master  
- 3 Puppet Agents  
  - Slave 1 → Apache  
  - Slave 2 → Apache  
  - Slave 3 → NGINX (New Node)

Automation Logic:

- Detect existing Apache installations on previous slaves
- Apply conditional rule:
  - If Apache exists → Install NGINX on new slave

---

# 🔄 Implementation Executed

✔ Integrated additional slave node into Puppet Master  
✔ Updated manifests to include conditional logic  
✔ Enforced role-based service deployment  
✔ Ensured Apache remained intact on existing nodes  
✔ Installed NGINX exclusively on the new agent  
✔ Validated configuration consistency across cluster  

Result:

- Slave 1 → Apache  
- Slave 2 → Apache  
- Slave 3 → NGINX  

All nodes managed centrally via Puppet Master.

---

# 🛠 Execution Highlights

✔ Extended cluster without manual configuration  
✔ Implemented intelligent conditional logic  
✔ Demonstrated scalable configuration management  
✔ Maintained idempotent deployment model  
✔ Reduced service conflict risk  

---

# 🔐 Engineering Outcomes

✔ Achieved service-based deployment segmentation  
✔ Enabled environment-aware provisioning  
✔ Improved scalability of Puppet infrastructure  
✔ Demonstrated modular configuration approach  
✔ Strengthened infrastructure consistency  

---

# 🧠 Skills Demonstrated

- Puppet Master–Agent Architecture  
- Node Onboarding & Certificate Management  
- Conditional Manifest Logic  
- Apache & NGINX Service Automation  
- Infrastructure Scaling  
- Declarative Configuration Management  
- Idempotent Automation  

---

# 📊 Enterprise Relevance

This approach is used in:

- Multi-role server provisioning  
- Environment-based service segregation  
- Infrastructure expansion scenarios  
- Automated service dependency handling  
- Large-scale configuration management systems  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Puppet Module – DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
