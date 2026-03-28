# 🚀 DevOps Production Project

## 📌 Overview
This project demonstrates a complete end-to-end DevOps pipeline using modern tools and best practices. It automates infrastructure provisioning, configuration, deployment, and monitoring.

---

## 🧱 Architecture

- Terraform → Infrastructure provisioning (EC2, ECR, IAM, Security Groups)
- Ansible → Server configuration & deployment automation
- Docker → Containerization
- AWS ECR → Image registry
- GitHub Actions → CI/CD pipeline
- Prometheus & Grafana → Monitoring

---

## 🔄 Pipeline Flow

1. Code pushed to GitHub
2. GitHub Actions triggers deployment
3. Ansible connects to EC2 via SSH
4. Application is cloned from GitHub
5. Docker image is built
6. Image is pushed to AWS ECR
7. Container is deployed on EC2
8. Monitoring enabled using Prometheus & Grafana

---

## 🌐 Access

Application:
http://18.61.166.102:5000

Grafana:
http://18.61.166.102:3000

Prometheus:
http://18.61.166.102:9090

---

## 📸 Screenshots

### Application Running on EC2
![App](docs/screenshots/screenshots_app_ec2.png)

### CI/CD Pipeline (GitHub Actions)
![CI/CD](docs/screenshots/screenshots_github_actions.png)

### Grafana Dashboard
![Grafana](docs/screenshots/screenshots_grafana.png)

### Prometheus Metrics
![Prometheus](docs/screenshots/screenshots_prometheus.png)

---

## 🧠 Key Learnings

- Infrastructure as Code using Terraform
- Configuration management using Ansible
- Containerization with Docker
- CI/CD automation using GitHub Actions
- Monitoring with Prometheus & Grafana
- Debugging real-world DevOps issues

---

## 🎯 Outcome

Built a production-style DevOps pipeline capable of:
- Automated deployment
- Infrastructure recreation
- Monitoring and observability

