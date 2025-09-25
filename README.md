# Task 3: Infrastructure as Code (IaC) with Terraform & Docker

## ✅ Objective
Provision a local Docker container (nginx) using Terraform on an AWS EC2 instance.

---

## 🔧 Tools Used
- Terraform v1.8.5
- Docker
- AWS EC2 (Amazon Linux / Ubuntu)

---

## 📦 What It Does
This project:
- Initializes the Terraform Docker provider
- Pulls the `nginx:latest` image
- Creates a Docker container exposing port 8080
- Destroys infrastructure cleanly

---

## 📁 Files
- `main.tf`: Terraform configuration file
- `output.txt`: Terminal logs of `init`, `plan`, `apply`, `state list`, and `destroy`

---

## 🚀 Usage

### 1. Clone the repo
```bash
git clone https://github.com/ShrihariMohite/-terraform-docker.git
cd terraform-docker
