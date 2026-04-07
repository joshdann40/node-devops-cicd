# 🚀 Node.js CI/CD Pipeline using Jenkins, Docker & AWS

## 📌 Project Overview

This project demonstrates a complete end-to-end CI/CD pipeline built using Jenkins with a distributed master-agent architecture. The pipeline automates build, test, Docker image creation, and deployment of a Node.js application.

---

## 🛠️ Tech Stack

* Jenkins (Master-Agent Architecture)
* Docker & Docker Compose
* AWS EC2
* GitHub (Webhook Integration)
* Node.js (Sample Application)

---

## ⚙️ CI/CD Pipeline Workflow

1. **Code Push to GitHub**

   * GitHub webhook triggers Jenkins automatically

2. **Clone Stage**

   * Jenkins pulls the latest code from the repository

3. **Build & Test**

   * Docker image is built
   * Application dependencies installed
   * Tests executed using Mocha

4. **Push to Docker Hub**

   * Image tagged and pushed to Docker Hub

5. **Deploy**

   * Application deployed using Docker Compose

---

## 🏗️ Architecture

GitHub → Jenkins Master → Jenkins Agent → Docker → Deployment

---

## 🔐 Key Features

* Distributed Jenkins setup (Master-Agent)
* Secure credential management using Jenkins Credentials
* Automated Docker image build and push
* Zero-manual deployment using Docker Compose
* Event-driven pipeline via GitHub webhook (no polling)

---

## 🚀 How to Run

1. Clone the repository
2. Configure Jenkins (Master + Agent)
3. Add DockerHub credentials in Jenkins
4. Trigger build manually OR push code to GitHub

---

## 📸 Optional Enhancements

* Add screenshots of Jenkins pipeline
* Add Docker container logs
* Add deployed app URL

---

## 📈 Outcome

* Fully automated CI/CD pipeline
* Production-style Jenkins setup
* Real-world DevOps implementation

---

## 👤 Author

Joshua Daniel
