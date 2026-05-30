# 🚀 AWS DevOps CI/CD Pipeline Project

## 📌 Project Overview

This project demonstrates an end-to-end DevOps CI/CD pipeline implementation on AWS using:

* AWS EC2
* Git & GitHub
* Docker
* Jenkins
* Kubernetes (K3s)
* DockerHub
* Terraform
* Ansible

The objective was to automate application deployment from source code commit to Kubernetes production deployment.

---

## 🏗 Architecture

```text
Developer
    |
    v
 GitHub Repository
    |
    v
 Jenkins Pipeline
    |
    v
 Docker Build
    |
    v
 DockerHub
    |
    v
 Kubernetes (K3s)
    |
    v
 NodePort Service
    |
    v
 End Users

Terraform --> Infrastructure Provisioning
Ansible --> Configuration Management
```

---

## ⚙️ Technology Stack

| Category                 | Tools            |
| ------------------------ | ---------------- |
| Cloud                    | AWS EC2          |
| SCM                      | Git, GitHub      |
| CI/CD                    | Jenkins          |
| Containerization         | Docker           |
| Orchestration            | Kubernetes (K3s) |
| Registry                 | DockerHub        |
| IaC                      | Terraform        |
| Configuration Management | Ansible          |
| OS                       | Ubuntu Linux     |

---

## 🔄 CI/CD Workflow

1. Developer pushes code to GitHub.
2. Jenkins detects changes.
3. Jenkins builds Docker image.
4. Jenkins runs application validation on Port 85.
5. Jenkins pushes image to DockerHub.
6. Kubernetes pulls latest image.
7. Application is deployed as NodePort Service.
8. End users access application.

---

## 🐳 Docker Implementation

* Created custom Docker image.
* Containerized web application.
* Exposed application on Port 85.
* Validated deployment using curl testing.

---

## ☸ Kubernetes Deployment

* Deployed application using Kubernetes Deployment.
* Created NodePort Service.
* Configured multiple replicas.
* Verified pod health and service availability.

---

## 🏗 Terraform Implementation

* Infrastructure provisioning on AWS.
* Automated EC2 resource deployment.
* Infrastructure managed as code.

---

## ⚙️ Ansible Implementation

* Automated Java installation.
* Configuration management using playbooks.
* Standardized server configuration.

---

## 📊 Project Outcome

✔ Automated CI/CD Pipeline

✔ Dockerized Application

✔ Kubernetes Deployment

✔ Infrastructure as Code

✔ Configuration Management Automation

✔ Production-style DevOps Workflow

---

## 🚀 Future Enhancements

* Amazon EKS
* Helm Charts
* ArgoCD
* GitOps
* Prometheus
* Grafana
* SonarQube
* Trivy Security Scanning
* AWS ECR
* Blue/Green Deployment

```
```

