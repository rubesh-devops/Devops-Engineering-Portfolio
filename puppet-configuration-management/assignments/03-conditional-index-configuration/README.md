# 📦 Puppet – Conditional Web Server Content Management

---

## 📌 Overview

Implemented conditional configuration management using Puppet to dynamically manage web server content based on installed services.

Extended the existing Puppet infrastructure to automatically update the `index.html` file depending on whether Apache or NGINX is installed on the target node.

---

## 🎯 Objective

Enhance infrastructure intelligence by:

- Reusing the existing Puppet master–agent deployment
- Detecting installed web server services
- Applying conditional logic within manifests
- Updating web content dynamically based on service state

---

# 🏗 Architecture Implemented

Infrastructure Environment:

- 1 Puppet Master  
- 3 Puppet Agents  
  - Apache Node  
  - NGINX Node  
  - Additional Slave  

Configuration Logic:

- If Apache is installed → Update `index.html` with message:
  **"apache is installed"**
- If NGINX is installed → Update `index.html` with message:
  **"nginx is installed"**

---

# 🔄 Implementation Executed

✔ Reused previous Puppet deployment  
✔ Applied conditional logic inside Puppet manifests  
✔ Targeted nodes based on installed packages  
✔ Updated web root content dynamically  
✔ Ensured idempotent execution across runs  
✔ Verified service-based content enforcement  

Result:

- Apache server displayed Apache-specific content  
- NGINX server displayed NGINX-specific content  
- Configuration remained consistent on repeated runs  

---

# 🛠 Execution Highlights

✔ Implemented service-aware automation  
✔ Enforced state validation before content deployment  
✔ Maintained configuration consistency  
✔ Reduced manual configuration drift  
✔ Demonstrated intelligent infrastructure automation  

---

# 🔐 Engineering Outcomes

✔ Achieved conditional configuration enforcement  
✔ Enabled dynamic content management via IaC  
✔ Improved reliability of web server deployments  
✔ Strengthened declarative infrastructure design  
✔ Demonstrated environment-aware automation  

---

# 🧠 Skills Demonstrated

- Puppet Conditional Logic  
- Service Detection & State Enforcement  
- Web Server Configuration Automation  
- Apache & NGINX Management  
- Infrastructure as Code (IaC)  
- Idempotent Configuration Design  
- Configuration Drift Prevention  

---

# 📊 Enterprise Relevance

This approach is widely used in:

- Multi-environment deployments  
- Role-based server provisioning  
- Automated content management systems  
- Configuration drift prevention  
- Scalable enterprise infrastructure  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Puppet Module – DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
