# 🚀 Jenkins – Multi-Node Branch-Based Deployment Automation

---

## 📌 Overview

Designed and implemented a multi-node Jenkins CI/CD architecture enabling branch-based deployment to separate environments.

Configured Jenkins Master with two additional nodes and created automated deployment pipelines for **test** and **production** environments based on Git branch activity.

This assignment demonstrates scalable CI/CD orchestration with environment segregation.

---

## 🎯 Objective

Build a deployment pipeline that:

- Expands Jenkins infrastructure with additional nodes
- Creates dedicated jobs for test and production
- Deploys code automatically based on branch activity
- Segregates test and production environments
- Eliminates manual deployment intervention

---

# 🏗 Architecture Implemented

Infrastructure Components:

- Jenkins Master
- Jenkins Node 1 (Test Environment)
- Jenkins Node 2 (Production Environment)
- Git Repository

Branch-Based Workflow:

Push to `test` branch  
⬇  
Trigger Test Job  
⬇  
Deploy code to Test Server  

Push to `master` branch  
⬇  
Trigger Production Job  
⬇  
Deploy code to Production Server  

---

# 🔄 Implementation Executed

✔ Added two agent nodes to Jenkins Master  
✔ Configured secure Master–Agent communication  
✔ Created dedicated pipeline job for Test deployment  
✔ Created dedicated pipeline job for Production deployment  
✔ Configured branch-based trigger logic  
✔ Implemented automated file transfer to respective servers  
✔ Verified deployment isolation between environments  

Result:

- Push to test branch → Code deployed to Test server  
- Push to master branch → Code deployed to Production server  
- Environment isolation successfully maintained  
- Deployment automation achieved  

---

# 🛠 Execution Highlights

✔ Multi-node Jenkins setup  
✔ Branch-based job triggering  
✔ Environment-specific deployment pipelines  
✔ Automated file synchronization  
✔ Reduced human deployment errors  
✔ Scalable CI/CD architecture  

---

# 🔐 Engineering Outcomes

✔ Achieved environment segregation in CI/CD  
✔ Strengthened deployment governance  
✔ Enabled safe testing before production release  
✔ Improved DevOps automation maturity  
✔ Established production-ready Jenkins architecture  

---

# 🧠 Skills Demonstrated

- Jenkins Master–Agent Architecture  
- Multi-Node CI/CD Setup  
- Branch-Based Deployment Automation  
- Git Integration with Jenkins  
- Environment-Specific Job Configuration  
- CI/CD Pipeline Design  

---

# 📊 Enterprise Relevance

This architecture pattern is widely used in:

- Enterprise CI/CD pipelines  
- Staging & Production deployment workflows  
- Agile DevOps environments  
- Continuous Delivery frameworks  
- Scalable DevOps infrastructure design  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 6 – Jenkins**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
