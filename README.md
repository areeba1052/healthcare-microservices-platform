# 🏥 Healthcare Microservices Platform

A **containerized microservices system** built with **Flask**, **React**, **Docker**, and **Kubernetes**, showcasing modern **CI/CD automation** using **GitHub Actions** and **DockerHub**.

---

## ⚙️ Overview

This project simulates a scalable healthcare platform with the following services:

- 🩺 **Appointments Service** – Handles patient appointment scheduling  
- 👨‍⚕️ **Doctors Service** – Manages doctor information and availability  
- 💻 **Frontend Service** – React-based interface connecting users to APIs  
- 🗄️ **MongoDB** – Central database for persistent data  

All services are containerized and deployed via automated CI/CD pipelines.

---

## 🧩 Tech Stack

| Category | Technology |
|-----------|-------------|
| Backend | Flask (Python) |
| Frontend | React |
| Database | MongoDB |
| CI/CD | GitHub Actions + DockerHub |
| Deployment | Docker Compose, Kubernetes |
| Infrastructure | ConfigMaps, Secrets, Deployments, Services |

---

## 🧱 Project Structure

.github/workflows/
│ ├── appointments-cicd.yml
│ ├── doctors-cicd.yml
│ └── frontend.yml
appointments/
│ ├── app.py
│ ├── Dockerfile
│ └── k8s/app.yaml
doctors/
│ ├── app.py
│ ├── Dockerfile
│ └── k8s/app.yaml
frontend/
│ ├── app.js
│ ├── Dockerfile
│ └── k8s/app.yaml
docker-compose.yml
requirements.txt
---

## 🚀 Features

- 🔹 **Microservices architecture** for modular scalability  
- 🔹 **CI/CD pipelines** for auto-build and deployment  
- 🔹 **Kubernetes manifests** for orchestration  
- 🔹 **Dockerized services** with versioned tags  
- 🔹 **Secure configuration** via ConfigMaps and Secrets  

---

## 🧠 Notes

Each microservice has:
- Its own **Dockerfile** and **Kubernetes manifest**  
- A **GitHub Actions workflow** to build, push, and version Docker images automatically  

---

## 👩‍💻 Author

**Areeba Asif**  

---

> 🎓 *Developed as part of MLOps/DevOps coursework and evolved into a complete microservices showcase.*
