# 🚀 Blue-Green Deployment CI/CD Pipeline

A production-style DevOps project demonstrating **Blue-Green Deployment** for zero-downtime application releases using **Docker**, **Jenkins**, **Nginx**, and **Flask**.

---

## 📌 Overview
This project showcases how modern web applications can be deployed with **minimal downtime** using the **Blue-Green Deployment strategy**.  
The application is containerized with Docker, automated through Jenkins CI/CD, and served via Nginx Reverse Proxy. Two identical production environments (Blue and Green) are maintained, enabling seamless traffic switching during deployments while reducing risks.

---

## ✨ Features
- 🔵 Blue-Green Deployment Strategy  
- 🐳 Docker Containerization  
- ⚙️ Jenkins CI/CD Automation  
- 🌐 Nginx Reverse Proxy  
- 🔄 Automated Deployment Workflow  
- 🚀 Zero-Downtime Release Strategy  
- 📦 Git-based Version Control  
- 🌍 Live Deployment on Render  

---

## 🛠 Tech Stack
| Category        | Technology |
|-----------------|------------|
| Language        | Python |
| Framework       | Flask |
| Frontend        | HTML, CSS, Jinja2 |
| Containerization| Docker |
| CI/CD           | Jenkins |
| Reverse Proxy   | Nginx |
| Version Control | Git, GitHub |
| Deployment      | Render |

---

## 🏗 Architecture
--Developer → GitHub → Jenkins Pipeline → Docker Image → Green Environment → Validation → Nginx Traffic Switch → End Users

---

## 🔄 Workflow
1. Developer pushes code to GitHub.  
2. Jenkins pipeline triggers build.  
3. Docker image is created.  
4. Green environment is deployed.  
5. Application validated.  
6. Nginx switches traffic Blue → Green.  
7. Blue remains available for rollback.  

---

## 📂 Project Structure
blue-green-deployment/
├── static/
├── templates/
├── app.py
├── Dockerfile
├── nginx.conf
├── requirements.txt
└── README.md

---

## 💻 Run Locally
```bash
# Clone repo
git clone https://github.com/sravya132/blue-green-deployment.git
cd blue-green-deployment

# Install dependencies
pip install -r requirements.txt

# Run app
python app.py

---

## 🎯 Skills Demonstrated

- Docker Containerization
- Jenkins CI/CD Pipelines
- Blue-Green Deployment Strategy
- Nginx Reverse Proxy
- Git Version Control
- Linux-based Deployment
- Production Release Workflow
- Deployment Automation

---

## 📈 Future Enhancements

- Kubernetes Deployment
- Docker Compose
- AWS EC2 Deployment
- GitHub Actions CI/CD
- Prometheus Monitoring
- Grafana Dashboards


