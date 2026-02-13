# 🚀 Jenkins – Controlled Chained CI/CD Pipeline (Test → Production)

---

## 📌 Overview

Designed and implemented a chained CI/CD pipeline in Jenkins that enforces structured deployment flow across environments.

The pipeline is triggered automatically on push to the **develop branch**, deploys to the **Test environment**, and only proceeds to **Production** upon successful completion of the test stage.

This implementation ensures controlled promotion of code and production-safe release management.

---

## 🎯 Objective

Implement a deployment pipeline that:

- Triggers automatically on push to `develop` branch
- Executes Test job first
- Promotes build to Production only if Test succeeds
- Copies Git repository files to respective nodes
- Prevents unstable code from reaching Production

---

# 🏗 Architecture Implemented

Infrastructure Components:

- Jenkins Master
- Jenkins Test Node
- Jenkins Production Node
- Git Repository

Pipeline Flow:

Push to `develop`  
⬇  
Trigger Jenkins Pipeline  
⬇  
Execute Test Job  
⬇  
If Success → Trigger Production Job  
⬇  
Deploy to Production Node  

---

# 🔄 Implementation Executed

✔ Created Jenkins Pipeline job  
✔ Configured Git webhook for develop branch trigger  
✔ Defined Test stage to copy files to Test node  
✔ Configured conditional logic for build promotion  
✔ Implemented Production stage execution only after Test success  
✔ Automated file synchronization to Production node  
✔ Validated end-to-end deployment workflow  

Result:

- Push to develop → Test job triggered automatically  
- Successful Test → Production job triggered  
- Failed Test → Production deployment blocked  
- Controlled and safe deployment pipeline established  

---

# 🛠 Execution Highlights

✔ Sequential stage-based deployment  
✔ Conditional pipeline logic  
✔ Automated promotion workflow  
✔ Branch-triggered CI/CD  
✔ Environment isolation maintained  
✔ Reduced production risk  

---

# 🔐 Engineering Outcomes

✔ Enforced gated production deployment  
✔ Implemented CI → CD workflow model  
✔ Strengthened DevOps governance  
✔ Reduced release risk  
✔ Improved deployment reliability  
✔ Achieved production-grade pipeline control  

---

# 🧠 Skills Demonstrated

- Jenkins Pipeline Design  
- Multi-Stage CI/CD Implementation  
- Conditional Build Triggers  
- Git Webhook Integration  
- Test-to-Production Promotion Strategy  
- Environment-Specific Deployment  
- DevOps Release Automation  

---

# 📊 Enterprise Relevance

This deployment model is widely used in:

- Production-grade CI/CD systems  
- Regulated software release environments  
- Agile DevOps workflows  
- Continuous Delivery pipelines  
- Enterprise software engineering teams  

---

# 📸 Validation & Evidence

📄 Consolidated Execution Documentation  
👉 Google Drive: *(Documentation link will be updated)*  

---

# 🎓 Course Context

**Module 6 – Jenkins**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
