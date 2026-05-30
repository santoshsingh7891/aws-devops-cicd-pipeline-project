# 🚀 AWS DevOps CI/CD Pipeline Project

## 📌 Project Overview

This project demonstrates an end-to-end DevOps CI/CD pipeline implementation on AWS using Docker, Jenkins, Kubernetes (K3s), Terraform, and Ansible.

The objective of this project is to automate application deployment from source code commit to production deployment on Kubernetes.

---

## 🏗 Architecture Diagram

![Architecture](architecture/architecture-diagram.png)

---

## ⚙️ Technology Stack

| Category                 | Technology       |
| ------------------------ | ---------------- |
| Cloud Platform           | AWS EC2          |
| Source Control           | Git, GitHub      |
| CI/CD                    | Jenkins          |
| Containerization         | Docker           |
| Container Registry       | DockerHub        |
| Orchestration            | Kubernetes (K3s) |
| Infrastructure as Code   | Terraform        |
| Configuration Management | Ansible          |
| Operating System         | Ubuntu 22.04     |

---

## 🔄 CI/CD Workflow

1. Developer pushes code to GitHub.
2. Jenkins pipeline is triggered.
3. Docker image is built.
4. Application is tested on Port 85.
5. Docker image is pushed to DockerHub.
6. Kubernetes pulls the latest image.
7. Application is deployed using Kubernetes Deployment.
8. NodePort Service exposes the application.
9. End users access the application.

---

## 🐳 Docker Implementation

* Created custom Docker image.
* Containerized web application.
* Exposed application through NGINX.
* Automated image build process.

---

## ☸ Kubernetes Deployment

* Created Kubernetes Deployment.
* Configured multiple replicas.
* Exposed application through NodePort Service.
* Verified pod and service health.

---

## 🏗 Terraform Implementation

* Provisioned AWS infrastructure using Infrastructure as Code.
* Automated EC2 resource deployment.
* Maintained reusable infrastructure templates.

---

## ⚙️ Ansible Implementation

* Automated Java installation.
* Used inventory-based configuration management.
* Standardized server configuration.

---

## 📂 Repository Structure

```text
aws-devops-cicd-pipeline-project
│
├── ansible
├── architecture
├── docker
├── jenkins
├── kubernetes
├── terraform
├── screenshots
└── README.md
```

---

## 🎯 Key Achievements

* End-to-End CI/CD Automation
* Dockerized Application Deployment
* Kubernetes Orchestration
* Infrastructure as Code using Terraform
* Configuration Management using Ansible
* AWS Cloud Deployment
* Automated Application Testing

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
* Blue/Green Deployments

---

## 👨‍💻 Author

**Santosh Singh**

AWS | DevOps | Cloud Engineer

GitHub: https://github.com/santoshsingh7891

```
```
