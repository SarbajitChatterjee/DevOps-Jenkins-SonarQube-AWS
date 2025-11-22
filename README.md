# 🚀 Jenkins CI/CD Pipeline – SonarQube · Docker · GitHub Webhooks on AWS 🎉

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge&logo=jenkins&logoColor=white)](https://www.youtube.com/watch?v=361bfIvXMBI)  
[![Code Quality](https://img.shields.io/badge/sonarqube-quality-brightgreen?style=for-the-badge&logo=sonarqube&logoColor=white)]()  
[![Docker](https://img.shields.io/badge/docker-deployed-blue?style=for-the-badge&logo=docker&logoColor=white)]()  
[![AWS](https://img.shields.io/badge/aws-cloud-orange?style=for-the-badge&logo=amazon-aws&logoColor=white)]()

---

## 🎯 What this project does  
- Push code to GitHub → it **automatically triggers** a build  
- Runs **SonarQube** to check code quality  
- Builds a **Docker** container and deploys it on AWS  
- Website/app is live at `http://<YOUR‑EC2‑IP>:8085`

---

## 🧱 What’s in the repo  
- `index.html` → sample website  
- `Dockerfile` → builds the site into a Docker image  
- `README.md` → this file  

---

## 🔧 Quick Start  
1. Clone this repo.  
2. Set up a Jenkins server on AWS and connect GitHub webhook.  
3. Install SonarQube and link it to Jenkins.  
4. Set up a Docker host on AWS: allow port 8085.  
5. Push a change → check `http://<HOST_IP>:8085` → see your update live.

---

## 🎓 Why this belongs on your resume  
- Shows you know CI/CD end‑to‑end  
- Shows you can use Docker + AWS in real‑world scenario  
- Shows you know code quality tools like SonarQube  

---

## 🔮 What you could do next  
- Add tests & automate them  
- Deploy to Kubernetes instead of single EC2  
- Set up full monitoring & rollback pipeline  

