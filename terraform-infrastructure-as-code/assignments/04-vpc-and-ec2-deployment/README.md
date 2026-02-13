# 🌐 Terraform – VPC Creation & EC2 Deployment

---

## 📌 Overview

Implemented full network infrastructure provisioning using Terraform by destroying previous deployments and creating a custom VPC architecture from scratch.

Deployed an EC2 instance inside the newly created VPC to validate end-to-end infrastructure automation.

This assignment demonstrates practical Infrastructure as Code (IaC) implementation for networking and compute provisioning in AWS.

---

## 🎯 Objective

Automate complete infrastructure setup including:

- Destroying previous Terraform deployments
- Creating a custom VPC
- Configuring required networking components
- Deploying an EC2 instance inside the VPC
- Validating connectivity and provisioning

---

# 🏗 Infrastructure Architecture

Provisioned Resources:

✔ Custom VPC  
✔ Public Subnet  
✔ Internet Gateway  
✔ Route Table  
✔ Route Table Association  
✔ Security Group  
✔ EC2 Instance inside VPC  

Architecture Flow:

Terraform Destroy  
⬇  
VPC Creation  
⬇  
Subnet Configuration  
⬇  
Internet Gateway Attachment  
⬇  
Route Table Configuration  
⬇  
Security Group Setup  
⬇  
EC2 Deployment inside VPC  

---

# 🔄 Implementation Executed

✔ Executed terraform destroy to remove previous resources  
✔ Defined custom VPC CIDR block  
✔ Created public subnet inside the VPC  
✔ Attached Internet Gateway to VPC  
✔ Configured route table for internet access  
✔ Associated route table with subnet  
✔ Created Security Group allowing required inbound access  
✔ Deployed EC2 instance within the created subnet  
✔ Executed terraform apply  
✔ Verified infrastructure in AWS Console  
✔ Validated EC2 public connectivity  

Result:

- Custom VPC successfully provisioned  
- Network components correctly configured  
- EC2 instance deployed within isolated VPC  
- End-to-end provisioning completed via Terraform  

---

# 🛠 Execution Highlights

✔ Full network infrastructure automated  
✔ Dependency-based resource provisioning  
✔ Modular Terraform configuration  
✔ Secure networking architecture  
✔ Reproducible infrastructure deployment  

---

# 🔐 Engineering Outcomes

✔ Strengthened Infrastructure as Code expertise  
✔ Implemented real-world VPC architecture  
✔ Enabled secure instance-level deployment  
✔ Demonstrated scalable network provisioning  
✔ Reduced manual AWS networking configuration  

---

# 🧠 Skills Demonstrated

- Terraform VPC Automation  
- AWS Networking Architecture  
- Subnet & Route Table Configuration  
- Internet Gateway Setup  
- Security Group Configuration  
- EC2 Deployment inside Custom VPC  
- Infrastructure Lifecycle Management  

---

# 📊 Enterprise Relevance

This architecture pattern is widely used in:

- Production-grade AWS environments  
- Secure enterprise network design  
- Multi-tier application deployments  
- Isolated environment provisioning  
- Infrastructure automation pipelines  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 8 – Terraform**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
