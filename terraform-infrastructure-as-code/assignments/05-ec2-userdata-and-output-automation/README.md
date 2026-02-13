# ⚙️ Terraform – EC2 Provisioning with User Data & Output Automation

---

## 📌 Overview

Automated complete infrastructure lifecycle using Terraform by destroying previous deployments and provisioning a new EC2 instance with Apache2 installation via script execution.

Additionally, captured and exported the instance Public IP to a local file automatically after deployment.

This assignment demonstrates Infrastructure as Code automation, configuration bootstrapping, and output handling using Terraform.

---

## 🎯 Objective

Automate the following using Terraform:

- Destroy previous infrastructure deployments
- Create a startup script to install Apache2
- Provision a new EC2 instance
- Execute installation script during instance launch
- Capture and store the instance Public IP locally

---

# 🏗 Infrastructure Architecture

Provisioned Resources:

✔ EC2 Instance  
✔ Security Group (HTTP & SSH enabled)  
✔ User Data Script for Apache Installation  
✔ Terraform Output Configuration  
✔ Local File Output for Public IP  

Architecture Flow:

Terraform Destroy  
⬇  
EC2 Provisioning  
⬇  
User Data Script Execution  
⬇  
Apache2 Installation  
⬇  
Public IP Extraction  
⬇  
Local File Output Generation  

---

# 🔄 Implementation Executed

✔ Executed terraform destroy to clean previous infrastructure  
✔ Created Apache2 installation script  
✔ Integrated script using EC2 user_data  
✔ Defined Security Group allowing HTTP (80) and SSH (22)  
✔ Provisioned new EC2 instance  
✔ Executed terraform apply  
✔ Apache2 installed automatically during boot  
✔ Configured Terraform output block  
✔ Stored instance Public IP in a local file  
✔ Verified Apache webpage accessibility  

Result:

- EC2 instance deployed successfully  
- Apache2 installed automatically  
- Web server accessible via browser  
- Public IP captured and saved locally  
- Fully automated infrastructure provisioning  

---

# 🛠 Execution Highlights

✔ Automated software installation during instance launch  
✔ Eliminated manual configuration steps  
✔ Integrated Terraform outputs for automation tracking  
✔ Implemented Infrastructure + Configuration in single workflow  
✔ Enabled reproducible provisioning  

---

# 🔐 Engineering Outcomes

✔ Combined Infrastructure as Code with configuration bootstrapping  
✔ Reduced operational overhead  
✔ Achieved zero-touch deployment  
✔ Automated post-deployment output handling  
✔ Strengthened DevOps provisioning pipeline  

---

# 🧠 Skills Demonstrated

- Terraform EC2 Provisioning  
- User Data Script Automation  
- Apache2 Automated Installation  
- Security Group Configuration  
- Terraform Output Variables  
- Local File Output Generation  
- Infrastructure Lifecycle Management  

---

# 📊 Enterprise Relevance

This pattern is widely used for:

- Automated web server provisioning  
- CI/CD pipeline infrastructure builds  
- Immutable infrastructure deployment  
- Cloud-native bootstrapping  
- Production environment automation  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 8 – Terraform**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
