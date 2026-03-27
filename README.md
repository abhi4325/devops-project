#  DevOps Project - Node.js + Docker + CI/CD

##  Project Overview
This project demonstrates a complete DevOps workflow:
- Node.js application
- Docker containerization
- CI/CD pipeline using GitHub Actions
- Deployment on Render (live application)

---

##  Architecture
User → Render → Docker Container → Node.js App

---

##  Tech Stack
- Node.js
- Docker
- GitHub Actions (CI/CD)
- DockerHub
- Render (Deployment)

---

##  CI/CD Workflow
1. Code pushed to GitHub
2. GitHub Actions triggers pipeline
3. Docker image is built
4. Image pushed to DockerHub
5. Application deployed on Render

---

##  Live Demo
 https://devops-project-m9sa.onrender.com

---

##  Docker Commands (Local Setup)

### Build image
docker build -t devops-app .

### Run container
docker run -p 3001:3000 devops-app

---

##  API Endpoints

### Home
GET /
Response:
{
  "message": "Devops project running"
}

### Health Check
GET /health  
Response: OK

### About
GET /about  
Response: DevOps Project by Abhishek

---

## Author
Abhishek Pandey

---

##  Key Features
- End-to-end DevOps pipeline
- Automated Docker build & push
- Live deployment
- Scalable container-based architecture
