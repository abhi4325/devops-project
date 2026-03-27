#  DevOps Project - Node.js + Docker + CI/CD

##  Project Overview

This project demonstrates a complete DevOps workflow using:

* Node.js application
* Docker containerization
* GitHub for version control
* GitHub Actions for CI/CD pipeline
* DockerHub for image storage

---

##  Tech Stack

* Node.js
* Express.js
* Docker
* GitHub
* GitHub Actions (CI/CD)
* DockerHub

---

##  Project Structure

```
devops-project/
│── app.js
│── package.json
│── Dockerfile
│── .github/
│   └── workflows/
│       └── deploy.yml
```

---

##  Features

* Simple Node.js API
* Dockerized application
* Automated CI/CD pipeline
* Docker image pushed to DockerHub on every commit

---

##  Docker Setup

### Build Docker Image

```
docker build -t devops-app .
```

### Run Container

```
docker run -p 3001:3000 devops-app
```

### Access App

```
http://localhost:3001
```

---

##  CI/CD Pipeline

This project uses GitHub Actions for automation:

* Code push triggers pipeline
* Docker image is built automatically
* Image is pushed to DockerHub

### Workflow File:

```
.github/workflows/deploy.yml
```

---

##  Environment Variables (GitHub Secrets)

The following secrets are used:

* DOCKER_USERNAME
* DOCKER_PASSWORD

---

##  DockerHub Repository

 https://hub.docker.com/r/abhi4325/devops-app

---

##  Learning Outcome

* Learned Docker containerization
* Implemented CI/CD pipeline
* Automated build and deployment process
* Understood DevOps workflow

---

##  Future Improvements

* Deploy on AWS EC2 / Render
* Add monitoring (Prometheus, Grafana)
* Add frontend UI

---

##  Author

Abhishek Pandey

---
