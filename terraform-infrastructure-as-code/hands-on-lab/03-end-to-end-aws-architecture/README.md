# 🏗 Hands-On 3 – Deploying End-to-End AWS Architecture using Terraform

---

## 📌 Overview

In this hands-on, I designed and provisioned a complete AWS network architecture using **Terraform Infrastructure as Code (IaC)**.

The deployment included:

- Custom VPC
- Public Subnet
- EC2 Instance
- Internet Gateway
- Route Table
- Security Group
- Network Interface
- Output Variable Extraction

This exercise demonstrates real-world infrastructure provisioning using Terraform in AWS.

---

# 🎯 Objective

✔ Configure AWS provider in Terraform  
✔ Create a custom VPC  
✔ Deploy subnet inside VPC  
✔ Launch EC2 instance within subnet  
✔ Configure Internet Gateway and Route Table  
✔ Apply Security Group rules  
✔ Attach Network Interface  
✔ Deploy infrastructure using Terraform lifecycle  

---

# ⚙️ Infrastructure Components Provisioned

---

## 🔹 1️⃣ Provider Configuration

- Configured AWS provider
- Defined target region (us-west-2)
- Authenticated using access key & secret key
- Initialized Terraform environment using `terraform init`

This establishes Terraform’s communication with AWS.

---

## 🔹 2️⃣ Virtual Private Cloud (VPC)

Created a custom VPC with:

- Custom CIDR block
- DNS support enabled
- DNS hostname support enabled
- Custom Name tagging

This provides an isolated virtual network environment for the infrastructure.

---

## 🔹 3️⃣ Subnet Deployment

- Created subnet inside the VPC
- Associated subnet with VPC ID reference
- Defined CIDR range for subnet

This ensures controlled network segmentation within the VPC.

---

## 🔹 4️⃣ EC2 Instance Deployment

- Launched Ubuntu-based EC2 instance
- Selected appropriate instance type
- Associated key pair for SSH access
- Deployed instance inside created subnet

This provisions the compute layer inside the custom network.

---

## 🔹 5️⃣ Internet Gateway Configuration

- Created Internet Gateway
- Attached it to VPC
- Enabled external internet communication

This allows public traffic to reach resources in the VPC.

---

## 🔹 6️⃣ Route Table Configuration

- Created route table
- Defined route to Internet Gateway
- Associated route table with subnet

This enables outbound and inbound internet connectivity.

---

## 🔹 7️⃣ Security Group Implementation

Configured Security Group with:

- Ingress rules (incoming traffic)
- Port-based access control
- Optional default rule inheritance

Security Groups were applied at the instance level for controlled traffic filtering.

---

## 🔹 8️⃣ Network Interface Attachment

- Created custom network interface
- Attached network interface to EC2 instance
- Managed network configuration explicitly

This provides flexibility in networking design.

---

## 🔹 9️⃣ Terraform Lifecycle Execution

Executed complete Terraform workflow:

- terraform init → Initialize provider
- terraform plan → Preview infrastructure changes
- terraform apply → Deploy infrastructure
- terraform output → Extract deployment values

Deployment confirmed successfully via AWS Management Console.

---

# 🧠 Skills Demonstrated

- Infrastructure as Code (IaC)
- Terraform AWS Provider
- VPC Architecture Design
- Subnet & Route Table Configuration
- Internet Gateway Setup
- Security Group Hardening
- EC2 Deployment Automation
- Network Interface Configuration
- Terraform State & Output Management
- Cloud Infrastructure Planning

---

# 📈 Enterprise Relevance

This architecture mirrors real-world production setups used in:

- Cloud-native application hosting
- Multi-tier infrastructure environments
- Secure network segmentation
- Automated DevOps deployments
- Reproducible cloud provisioning

Terraform enables repeatable, scalable, and version-controlled infrastructure deployment.

---

# 📊 Outcome

✔ Successfully deployed full AWS network architecture  
✔ Verified VPC creation in AWS Console  
✔ Confirmed EC2 instance deployment inside subnet  
✔ Validated Internet connectivity via IGW & Route Table  
✔ Applied controlled Security Group rules  
✔ Managed infrastructure using Terraform lifecycle  

End-to-End AWS architecture deployed successfully using Infrastructure as Code.

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 8 – Terraform**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
