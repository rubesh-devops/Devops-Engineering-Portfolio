# 🌍 Terraform – Infrastructure Lifecycle Management & EC2 with Elastic IP

---

## 📌 Overview

Implemented infrastructure lifecycle management using Terraform by safely destroying previous cloud resources and provisioning a new EC2 instance with a publicly accessible Elastic IP.

This assignment demonstrates resource destruction, recreation, and dynamic public IP allocation using Infrastructure as Code principles.

---

## 🎯 Objective

Enhance Terraform automation by:

- Destroying previously deployed EC2 infrastructure
- Re-provisioning EC2 instance using updated configuration
- Allocating and associating Elastic IP
- Managing infrastructure lifecycle declaratively
- Maintaining clean and consistent Terraform state

---

# 🏗 Infrastructure Architecture

Provisioned Resources:

- 1 EC2 Instance
- Region: Ohio (us-east-2)
- Elastic IP (EIP) attached to instance
- Default VPC & Subnet

Lifecycle Flow:

Terraform Destroy  
⬇  
Infrastructure Cleanup  
⬇  
Terraform Apply  
⬇  
EC2 Provisioned  
⬇  
Elastic IP Allocated & Associated  

---

# 🔄 Implementation Executed

✔ Executed terraform destroy to remove previous deployment  
✔ Updated Terraform configuration to include Elastic IP resource  
✔ Defined EIP association with EC2 instance  
✔ Re-initialized Terraform workspace  
✔ Applied new configuration  
✔ Verified Elastic IP attachment in AWS Console  
✔ Validated updated Terraform state file  

Result:

- Previous EC2 safely destroyed  
- New EC2 instance provisioned  
- Elastic IP successfully allocated and attached  
- Infrastructure fully managed via Terraform  

---

# 🛠 Execution Highlights

✔ Infrastructure teardown automation  
✔ Elastic IP allocation via code  
✔ Dynamic resource association  
✔ Clean state management  
✔ Lifecycle-driven infrastructure control  

---

# 🔐 Engineering Outcomes

✔ Demonstrated full resource lifecycle control  
✔ Improved public accessibility management  
✔ Reduced risk of orphaned cloud resources  
✔ Strengthened infrastructure consistency  
✔ Achieved production-style IaC deployment  

---

# 🧠 Skills Demonstrated

- Terraform Destroy & Apply Lifecycle  
- AWS EC2 Provisioning  
- Elastic IP Automation  
- Infrastructure as Code (IaC)  
- Resource Dependency Management  
- Terraform State Synchronization  

---

# 📊 Enterprise Relevance

This lifecycle approach is widely used in:

- Environment rebuild automation  
- Blue-Green deployments  
- Dynamic public endpoint management  
- Infrastructure refactoring  
- Production infrastructure control  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 8 – Terraform**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
