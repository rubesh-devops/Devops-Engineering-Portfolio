# 🐳 Assignment 2 – Docker Volume Implementation with Commands

---

## 📌 Project Overview

Implemented persistent storage for an Apache2 container using Docker Volumes and documented the execution commands in structured order.

This assignment demonstrates production-ready container deployment with volume-based data persistence.

---

## 🎯 Objectives

✔ Launch previously created Apache2 container  
✔ Create a Docker Volume  
✔ Mount volume to `/var/www/html`  
✔ Ensure data persistence  
✔ Document commands used in execution  

---

## ⚙️ Execution Commands (In Order)

### 1️⃣ Create Docker Volume

```bash
docker volume create apache_volume
```

---

### 2️⃣ Launch Apache2 Container with Volume Mount

```bash
docker run -dit \
-p 80:80 \
-v apache_volume:/var/www/html \
--name apache_container \
<your-apache-image-name>
```

---

### 3️⃣ Verify Running Container

```bash
docker ps
```

---

### 4️⃣ Verify Volume Mount Inside Container

```bash
docker exec -it apache_container bash
cd /var/www/html
```

---

### 5️⃣ Test Persistence (Optional Verification)

Create or modify a file:

```bash
echo "Docker Volume Working" > /var/www/html/test.html
```

Restart container:

```bash
docker restart apache_container
```

Verify content persists via browser or inside container.

---

## 🏗 Architecture Concept

- Apache2 running inside Docker container  
- Named Docker volume attached to container  
- Volume mapped to `/var/www/html`  
- Persistent data layer independent of container lifecycle  

---

## 🔐 Why This Matters in Production

Docker volumes enable:

- Persistent web content storage  
- Safe container upgrades  
- Zero data loss on restart  
- Separation of compute and storage layers  

---

## 📈 Skills Demonstrated

- Docker Volume Creation  
- Container Volume Mounting  
- Linux File Path Mapping  
- Apache Container Management  
- Data Persistence Strategy  

---

## 📊 Outcome

Successfully implemented Docker volume persistence ensuring:

- Data durability  
- Production-aligned container configuration  
- Clean separation of application and storage  

---

## 📸 Validation & Evidence

📄 **Consolidated Execution Documentation**  
👉 Google Drive: *(Documentation link will be updated)*  

---

## 🎓 Course Context

**Module – Docker II**  
**DevOps Course**  
**Part of DevOps Architect Master’s Program – Intellipaat**
