<div align="center">

<img src="./assets/yogananda-header.gif" width="100%"/>

</div>

# 👋 About Me

Hi, I'm **Yogananda Yampalakula**.

🔐 **Aspiring DevSecOps & Cloud Security Engineer**

I’m focused on building practical security solutions using **AWS, CI/CD, containers, Linux, and security automation**.

I enjoy learning by building hands-on projects that combine **application security, cloud security, monitoring, and DevOps practices**.

---

## 🎯 What I Focus On

- 🔐 DevSecOps & Application Security
- ☁️ AWS Cloud Security
- 🔄 CI/CD & Security Automation
- 🐳 Docker & Container Security
- 🐧 Linux & System Administration
- 📊 Cloud Monitoring & Security Detection

---

## 🚀 Featured Projects

### 🔐 Secure DevSecOps Pipeline

A security-focused CI/CD pipeline designed to identify security issues before application delivery.

**Security checks include:**

- 🔎 Semgrep — SAST
- 🔑 Gitleaks — Secret Detection
- 🛡️ Trivy — Container Vulnerability Scanning
- 🧪 Automated Application Testing
- 🐳 Docker Image Building
- ⚙️ GitHub Actions Security Gates
- 📦 GitHub Container Registry (GHCR)

🔗 **Repository:**  
https://github.com/Yogananda630/secure-devsecops-pipeline

---

### ☁️ AWS Cloud Security Monitor

An event-driven AWS security monitoring system for detecting and tracking cloud activity.

**Architecture:**

```text
AWS Activity
     ↓
CloudTrail
     ↓
EventBridge
     ↓
Lambda
     ↓
┌──────────┬────────────┬─────────┐
↓          ↓            ↓
DynamoDB  CloudWatch    SNS
                         ↓
                    Email Alerts
     ↓
Security Dashboard
