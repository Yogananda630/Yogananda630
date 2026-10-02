<div align="center">

<img src="./assets/yogananda-header.gif" width="100%"/>

<br>

### 🔐 DevSecOps & Cloud Security | AWS | CI/CD | Cybersecurity

</div>

---

## 👋 About Me

Hi, I'm **Yogananda Yampalakula** — an aspiring **DevSecOps & Cloud Security Engineer** focused on building practical security solutions with cloud, automation, containers, and CI/CD.

🔐 **Focus:** DevSecOps, Application Security, Cloud Security  
☁️ **Cloud:** AWS  
🐳 **Containers:** Docker  
🔄 **Automation:** GitHub Actions & CI/CD  
🐧 **Systems:** Linux  
🛡️ **Security:** SAST, Secret Detection, Container Security & Cloud Monitoring

I learn by **building real projects, testing them, documenting the results, and continuously improving them.**

---

## 🛠️ Tech Stack

### 💻 Languages & Tools

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>

</p>

### ☁️ Cloud & AWS Security

<p align="center">

<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/CloudTrail-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/EventBridge-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white"/>
<img src="https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white"/>
<img src="https://img.shields.io/badge/CloudWatch-FF9900?style=for-the-badge&logo=amazoncloudwatch&logoColor=white"/>
<img src="https://img.shields.io/badge/SNS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>

</p>

### 🔐 DevSecOps & Security

<p align="center">

<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Semgrep-4B32C3?style=for-the-badge&logo=semgrep&logoColor=white"/>
<img src="https://img.shields.io/badge/Gitleaks-111111?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aquasecurity&logoColor=white"/>

</p>

### 🐳 Containers

<p align="center">

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GHCR-181717?style=for-the-badge&logo=github&logoColor=white"/>

</p>

---

# 🚀 Featured Projects

| Project | What it does | Stack | Status |
|---|---|---|---|
| 🔐 **Secure DevSecOps Pipeline** | Automated security checks for application code, secrets and container vulnerabilities before delivery. | GitHub Actions, Semgrep, Gitleaks, Trivy, Docker, GHCR | 🟢 Completed |
| ☁️ **AWS Cloud Security Monitor** | Detects AWS activity, analyzes security events and sends alerts through an event-driven architecture. | CloudTrail, EventBridge, Lambda, DynamoDB, CloudWatch, SNS, Python | 🟢 Completed |

---

## 🔐 Secure DevSecOps Pipeline

A security-focused CI/CD pipeline that integrates security checks directly into the development workflow.

### 🔎 Security Pipeline

```text
Developer
    ↓
GitHub
    ↓
GitHub Actions
    ↓
┌───────────────┬───────────────┬───────────────┐
│    Semgrep    │    Gitleaks   │     Tests     │
│     SAST      │    Secrets    │               │
└───────────────┴───────────────┴───────────────┘
                    ↓
              Docker Build
                    ↓
                 Trivy
                    ↓
             Security Gate
                    ↓
                  GHCR
