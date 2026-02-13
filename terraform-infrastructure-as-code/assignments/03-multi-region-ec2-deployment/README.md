# 🌍 Terraform – Multi-Region EC2 Deployment (Ohio & N. Virginia)

---

## 📌 Overview

Implemented multi-region infrastructure provisioning using Terraform by destroying previous resources and deploying EC2 instances across two AWS regions.

This assignment demonstrates region-based provider configuration, multi-instance provisioning, and resource tagging using Infrastructure as Code (IaC).

---

## 🎯 Objective

Automate multi-region cloud provisioning by:

- Destroying previous infrastructure safely
- Configuring multiple AWS providers
- Deploying EC2 instances in:
  - Ohio (us-east-2)
  - N. Virginia (us-east-1)
- Applying meaningful instance naming via tags
- Maintaining clean Terraform state management

---

# 🏗 Infrastructure Architecture

Provisioned Resources:

- EC2 Instance 1
  - Region: Ohio (us-east-2)
  - Name Tag: hello-ohio

- EC2 Instance 2
  - Region: N. Virginia (us-east-1)
  - Name Tag: hello-virginia

Deployment Flow:

Terraform Destroy  
⬇  
Provider Configuration (Multi-Region)  
⬇  
Terraform Apply  
⬇  
Multi-Region Instance Provisioning  

---

# 🔄 Implementation Executed

✔ Executed terraform destroy to clean previous deployment  
✔ Configured AWS provider for Ohio region  
✔ Configured secondary provider for N. Virginia region  
✔ Defined separate EC2 resource blocks per region  
✔ Applied meaningful Name tags to instances  
✔ Executed terraform apply  
✔ Verified both instances in respective AWS regions  
✔ Validated Terraform state synchronization  

Result:

- EC2 instance successfully deployed in Ohio  
- EC2 instance successfully deployed in N. Virginia  
- Correct naming applied:
  - hello-ohio
  - hello-virginia  
- Infrastructure managed declaratively  

---

# 🛠 Execution Highlights

✔ Multi-region Terraform configuration  
✔ Provider alias implementation  
✔ Cross-region infrastructure automation  
✔ Clean infrastructure lifecycle control  
✔ Automated tagging strategy  

---

# 🔐 Engineering Outcomes

✔ Demonstrated global infrastructure provisioning  
✔ Enabled region-based scalability  
✔ Strengthened multi-environment architecture skills  
✔ Reduced manual cross-region deployment effort  
✔ Improved infrastructure consistency  

---

# 🧠 Skills Demonstrated

- Terraform Multi-Provider Configuration  
- AWS Multi-Region Deployment  
- EC2 Automation  
- Resource Tagging & Naming Standards  
- Infrastructure as Code (IaC)  
- State-Based Infrastructure Management  

---

# 📊 Enterprise Relevance

Multi-region infrastructure provisioning is widely used in:

- High availability architectures  
- Disaster recovery planning  
- Global SaaS deployments  
- Enterprise cloud expansion strategies  
- Scalable distributed systems  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 8 – Terraform**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
