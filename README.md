# Task 5: Kubernetes Deployment with Minikube on AWS EC2

## 📌 Objective
Deploy and manage applications in a Kubernetes cluster running on AWS EC2 using **Minikube**.

---

## 🛠 Tools & Technologies
- **Minikube** (Kubernetes single-node cluster)
- **kubectl** (Kubernetes CLI)
- **Docker** (Container runtime)
- **AWS EC2 Ubuntu 24.04**

---

## 🚀 Steps Performed

### 1. Setup Environment
- Installed Docker, Minikube, and kubectl on AWS EC2.
- Started Minikube with Docker driver:
  ```bash
  minikube start --driver=docker --cpus=2 --memory=2200mb

