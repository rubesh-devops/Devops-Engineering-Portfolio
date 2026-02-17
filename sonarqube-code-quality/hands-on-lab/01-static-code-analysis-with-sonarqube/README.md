# 🔎 Hands-On – Static Code Analysis using SonarQube  

## 📌 Module: SonarQube  
**DevOps Course – DevOps Architect Master’s Program – Intellipaat**

---

## 🎯 Objective

To implement **static code analysis** using SonarQube by:

- Cloning a Java-based application from GitHub  
- Installing required build dependencies (Java & Maven)  
- Configuring SonarQube project properties  
- Running code quality analysis  
- Reviewing results in SonarQube Dashboard  

---

## 🏗️ Environment Setup

### ✔ Installed & Configured

- Git  
- Java 1.8 (OpenJDK)  
- Apache Maven  
- SonarQube Server  
- Sample Java Application (PetClinic project)  

---

## 🚀 Execution Summary

### 1️⃣ Project Acquisition

- Installed Git on the analysis server  
- Cloned the PetClinic Java project from GitHub  
- Navigated into the project directory  
- Created and configured `sonar-project.properties` file with:
  - Project key  
  - Project name  
  - Version  
  - Source directory  
  - Language (Java)  
  - UTF-8 encoding  

📌 This enabled SonarQube to correctly identify and analyze project metadata.

---

### 2️⃣ Build Toolchain Setup

To prepare the environment for compilation:

- Installed Java Development Kit (JDK 1.8)  
- Installed Apache Maven  
- Verified Maven installation  
- Configured system PATH for Maven access  

---

### 3️⃣ Project Compilation

- Compiled the PetClinic Java application using Maven  
- Ensured successful build before initiating analysis  

📌 This validates that the codebase is syntactically correct before quality scanning.

---

### 4️⃣ SonarQube Analysis Execution

- Retrieved Sonar analysis command from SonarQube UI  
- Executed analysis from project root directory  
- Maven integrated with SonarQube plugin  
- Code quality metrics sent to SonarQube server  

---

### 5️⃣ Dashboard Verification

- Accessed SonarQube Web Interface  
- Verified:
  - Code smells  
  - Bugs  
  - Vulnerabilities  
  - Coverage  
  - Maintainability rating  
  - Security hotspots  

📊 Successfully visualized real-time quality metrics.

---

## 🧠 Concepts Demonstrated

- Static Code Analysis  
- Code Quality Gates  
- Maven-Sonar Integration  
- Java Project Compilation  
- DevSecOps Foundation  
- Continuous Code Inspection  

---

## 🏢 Enterprise Relevance

This hands-on simulates:

✔ Pre-production code validation  
✔ Quality checks before CI/CD promotion  
✔ Automated vulnerability detection  
✔ DevOps quality governance  
✔ Integration of build tools with code scanning platforms  

---

## 📸 Validation & Evidence

📄 **Execution Documentation & Screenshots**  
👉 Google Drive: *(Documentation link will be updated)*  

Includes:
- Maven build success  
- Sonar analysis execution logs  
- SonarQube dashboard results  
- Quality gate status  

---

## 🏆 Outcome

Successfully implemented:

- End-to-end static code analysis workflow  
- Maven-based Java project integration with SonarQube  
- Quality visibility through centralized dashboard  

This hands-on strengthens:

🔹 DevSecOps integration capability  
🔹 CI/CD pipeline readiness  
🔹 Production-level code governance practices  
