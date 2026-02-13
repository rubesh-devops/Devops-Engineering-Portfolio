# 🏗 Case Study – Creating AWS Architecture using Terraform

---

## 📌 Business Scenario

As a DevOps Engineer in a leading software company, I was assigned to design and provision a secure, production-ready AWS infrastructure using Terraform.

The organization required:

- AWS Cloud as the infrastructure provider  
- Ubuntu-based compute instances  
- Apache2 web server installation  
- Network-isolated architecture  
- Secure and scalable infrastructure provisioning  

The solution had to be automated, reusable, and safely deployable using Infrastructure as Code principles.

---

# 🎯 Objective

Design and provision a complete AWS architecture using Terraform that includes:

✔ Custom VPC  
✔ Two Subnets  
✔ One EC2 instance in each subnet  
✔ Internet Gateway  
✔ Security Groups  
✔ Network Interfaces  
✔ Apache2 installed on Ubuntu AMI  

All infrastructure must be provisioned using Terraform templates.

---

# 🏗 Architecture Design

Infrastructure Components:

- Custom VPC
- 2 Subnets (isolated networking)
- 2 EC2 Instances (Ubuntu AMI)
- Internet Gateway
- Route Tables
- Security Groups
- Elastic Network Interfaces
- Apache2 Web Server Installation via User Data

Architecture Flow:

Terraform Apply  
⬇  
VPC Creation  
⬇  
Subnet Provisioning  
⬇  
Internet Gateway Attachment  
⬇  
Security Group Configuration  
⬇  
EC2 Deployment in Each Subnet  
⬇  
Apache2 Installation  
⬇  
Web Server Accessibility  

---

# 🔄 Implementation Executed

✔ Designed modular Terraform configuration  
✔ Created custom VPC for isolated networking  
✔ Provisioned two subnets within the VPC  
✔ Attached Internet Gateway for public access  
✔ Configured route tables for outbound traffic  
✔ Created Security Groups allowing HTTP (80) and SSH (22)  
✔ Deployed Ubuntu EC2 instance in each subnet  
✔ Attached network interfaces to instances  
✔ Automated Apache2 installation using bootstrap configuration  
✔ Verified web server access via public IP  

Result:

- Fully functional dual-subnet architecture  
- Apache2 running on Ubuntu instances  
- Secure inbound and outbound traffic rules  
- Automated and reproducible infrastructure deployment  

---

# 🔐 Security & Networking Strategy

✔ Isolated network using custom VPC  
✔ Controlled inbound traffic via Security Groups  
✔ Public access only through defined ports  
✔ Internet Gateway attached securely  
✔ Network interfaces properly configured  

This ensured controlled exposure and secure resource communication.

---

# 🛠 Execution Highlights

✔ Infrastructure provisioned using Terraform only  
✔ No manual AWS console configuration  
✔ Fully reusable Terraform template  
✔ Clean separation of networking and compute layers  
✔ Automated Apache2 installation at launch  

---

# 🧠 Skills Demonstrated

- Terraform Infrastructure as Code  
- AWS VPC Architecture Design  
- Subnet Segmentation  
- Security Group Configuration  
- EC2 Deployment Automation  
- Ubuntu Server Configuration  
- Apache2 Automated Installation  
- Internet Gateway & Route Table Setup  
- Network Interface Attachment  

---

# 📈 Enterprise Relevance

This architecture pattern is commonly used for:

- Multi-tier web applications  
- Production-ready VPC environments  
- Secure cloud networking foundations  
- Infrastructure automation in DevOps pipelines  
- Scalable and reusable cloud deployments  

---

# 📊 Outcome

Successfully built a secure, scalable AWS architecture using Terraform that:

✔ Eliminates manual provisioning  
✔ Ensures reproducible deployments  
✔ Enables safe infrastructure expansion  
✔ Implements structured cloud networking  
✔ Demonstrates real-world DevOps engineering capability  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 8 – Terraform**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
