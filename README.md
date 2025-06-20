# 🚀 Dockerized 2-Tier Web App with GitHub CI/CD

This is a Capstone Project for **Group 6** under the Cloud Infrastructure and Automation track. The project involves building and deploying a two-tier web application (frontend + backend) using Docker, GitHub, and Azure.

---

## 📦 Project Structure

docker-2tier-app

 HEAD
## Screenshots
Include your deployment screenshots here.
# Triggered deployment update

├── backend/
│ ├── Dockerfile
│ ├── server.js
│ └── package.json
├── frontend/
│ ├── Dockerfile
│ └── index.html
├── docker-compose.yml
└── README.md

## 🔧 Technologies Used

- **Docker** – Containerization of both frontend and backend
- **Docker Compose** – Multi-container orchestration
- **GitHub** – Version control and project source hosting
- **Azure VM (Linux)** – Hosting the Dockerized application
- **Node.js + Express** – Backend server
- **Nginx** – Serving static frontend page
- **GitHub Actions** *(Optional)* – CI/CD Automation

---

## ⚙️ Setup Instructions (Local)

> You must have Docker Desktop and Git installed.

```bash
Clone the repository
git clone https://github.com/Ghostnoble/docker-2tier-app.git
cd docker-2tier-app

Run the app locally
docker-compose up --build
Frontend available at: http://localhost

Backend at: http://localhost:5000

🌐 Deployment Steps (Azure VM)
Create a Linux VM on Azure

Install Docker & Docker Compose

Clone the GitHub repo to the VM:

bash
git clone https://github.com/Ghostnoble/docker-2tier-app.git
cd docker-2tier-app
Run the app:

bash
docker-compose up -d
Allow port 80 in the Azure VM networking to expose frontend.

Visit:
🔗 http://172.174.62.5 — Live frontend page

🐳 Docker Hub Links
Frontend Image:
ghostnoble/frontend-app:v1

Backend Image:
ghostnoble/backend-app:v1

🧪 Screenshots (Saved Separately)
Azure VM Dashboard

Inbound Rules for port 80 / 5000

Docker containers running (docker ps)

Frontend and backend accessible in browser

Docker Hub + GitHub repo views

🔁 Optional GitHub Actions CI/CD (Bonus)
You can automate:

Building Docker images

Pushing to Docker Hub

SSH into VM and redeploy

Let me know if you want this added and I’ll help you configure it step-by-step.

👨‍💻 Author
Elijah Ogunsanya (Ghostnoble)
Email: elijahogunsanya86@gmail.com
GitHub: @Ghostnoble
 4d0bed0c2f5d1d3456f406787a31a4fb5ff0a6ca
