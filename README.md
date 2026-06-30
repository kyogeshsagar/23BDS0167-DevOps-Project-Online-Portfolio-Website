# 🌐 Online Portfolio Website – DevOps Project

A modern, responsive personal portfolio website developed using **HTML5, CSS3, and JavaScript**. This project is part of the **IBM DevOps Assignment (Use Case 3: Online Portfolio Website)** and demonstrates the implementation of a complete DevOps pipeline using GitHub, Jenkins, Docker, Kubernetes, Nagios, Graphite, and Grafana.

---

## 📌 Project Overview

This portfolio website showcases my profile, technical skills, projects, and contact information in a clean and responsive design. The project is containerized using Docker, deployed with Kubernetes, and integrated with a complete CI/CD pipeline for automated deployment and monitoring.

---

## 🎯 Objectives

- Build a responsive portfolio website.
- Store source code in GitHub.
- Automate deployment using Jenkins.
- Containerize the application using Docker.
- Deploy the application on Kubernetes.
- Monitor website availability using Nagios.
- Collect infrastructure metrics using Graphite.
- Visualize performance metrics using Grafana.

---

## 🚀 Features

- Responsive Portfolio Website
- About Me Section
- Skills Section
- Projects Showcase
- Contact Section
- Smooth Scrolling Navigation
- Mobile Friendly Design

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### DevOps Tools
- Git & GitHub
- Jenkins
- Docker
- Kubernetes
- Nagios
- Graphite
- Grafana

---

## 📁 Project Structure

```
portfolio-website/
│
├── assets/
│   ├── css/
│   ├── js/
│   ├── img/
│
├── index.html
├── Dockerfile
├── Jenkinsfile
├── deployment.yaml
├── service.yaml
├── README.md
```

---

## ⚙️ Setup Instructions

### Clone Repository

```bash
git clone https://github.com/kyogeshsagar/23BDS0167-DevOps-Project-Online-Portfolio-Website.git
```

```bash
cd 23BDS0167-DevOps-Project-Online-Portfolio-Website
```

---

## 🌐 Run Locally

Open the project using VS Code and launch **index.html** with the **Live Server** extension.

---

## 🐳 Docker

Build Docker Image

```bash
docker build -t portfolio-website .
```

Run Docker Container

```bash
docker run -d -p 8080:80 portfolio-website
```

Open:

```
http://localhost:8080
```

---

## ☸️ Kubernetes

Deploy the application

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

Check resources

```bash
kubectl get pods
kubectl get deployments
kubectl get services
```

---

## 🔄 CI/CD Pipeline

```
Developer
      │
      ▼
GitHub Repository
      │
      ▼
Jenkins Pipeline
      │
      ▼
Docker Image
      │
      ▼
Docker Container
      │
      ▼
Kubernetes Deployment
      │
      ▼
Portfolio Website
      │
      ▼
Nagios Monitoring
      │
      ▼
Graphite Metrics
      │
      ▼
Grafana Dashboard
```

---

## 📊 Monitoring

- Website Availability Monitoring using Nagios
- Infrastructure Metrics Collection using Graphite
- Dashboard Visualization using Grafana

Metrics monitored include:

- CPU Usage
- Memory Usage
- Network Traffic
- Website Availability
- System Uptime

---

## 📷 Project Screenshots

- Portfolio Website
- Jenkins Pipeline
- Docker Container
- Kubernetes Pods
- Nagios Dashboard
- Graphite Metrics
- Grafana Dashboard

*(Screenshots will be added after implementation.)*
<img width="1600" height="803" alt="WhatsApp Image 2026-06-30 at 22 56 38" src="https://github.com/user-attachments/assets/1c77b851-74af-4bc2-8668-272763e00f99" />
<img width="1600" height="813" alt="WhatsApp Image 2026-06-30 at 22 36 54" src="https://github.com/user-attachments/assets/d7582658-349f-46b7-9406-a02d32ead86d" />
<img width="1600" height="811" alt="WhatsApp Image 2026-06-30 at 22 48 52" src="https://github.com/user-attachments/assets/0798e08c-6c59-4535-8273-e181fe14e66a" />
<img width="1600" height="809" alt="WhatsApp Image 2026-06-30 at 23 02 15" src="https://github.com/user-attachments/assets/c8ae507d-3536-4fa1-b2af-cdf2fca5d58b" />
<img width="1600" height="849" alt="WhatsApp Image 2026-06-30 at 22 59 00" src="https://github.com/user-attachments/assets/13bcb28b-3de4-45c8-b073-3f8acac25edd" />
<img width="1600" height="848" alt="WhatsApp Image 2026-06-30 at 22 59 43" src="https://github.com/user-attachments/assets/a10d1666-092b-4cd3-929b-53c321d4926d" />
<img width="1600" height="847" alt="WhatsApp Image 2026-06-30 at 22 42 07" src="https://github.com/user-attachments/assets/714ee44e-8cb8-4c30-94ce-ea4bbaa3101d" />
<img width="1917" height="973" alt="image" src="https://github.com/user-attachments/assets/7fe4a0bb-5c6f-4102-9c7b-b7a983dabcb0" />
<img width="1600" height="819" alt="image" src="https://github.com/user-attachments/assets/c72c2687-0082-43e3-b0ad-0e3e3c4ad28a" />



---

## 👨‍💻 Author

**K Yogesh Sagar**

B.Tech Computer Science and Engineering (Data Science)

VIT Vellore

📧 yogeshsagar.k2023@vitstudent.ac.in

🔗 LinkedIn: https://linkedin.com/in/k-yogesh-sagar-16427628b

💻 GitHub: https://github.com/kyogeshsagar

---

## 📄 License

This project is developed for academic purposes as part of the IBM DevOps course assignment at VIT Vellore.
