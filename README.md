<p align="center">
  <img src="logo.png" alt="AI Resume & Cover Letter Generator" width="250"/>
</p>


# 🧠 AI Resume & Cover Letter Generator (SaaS)

An intelligent web platform that helps users **generate professional resumes and cover letters** using **AI (GPT)** — built with **Python Django**, containerized with **Docker**, and deployed on **AWS** via **CI/CD pipelines**.

---

## 🚀 Project Overview

This project demonstrates full backend and cloud development capability using a **real-world SaaS architecture**.  
It’s designed to show mastery of:
- Django REST API development  
- AI (GPT) integration  
- Cloud DevOps (Docker, GitHub Actions, AWS ECS, Terraform)  
- Scalable system design with CI/CD automation  

---

## 🧩 Core Features

✅ AI-powered Resume and Cover Letter Generator  
✅ User Authentication & Email Verification  
✅ Usage Limits & Subscription Management (Stripe Integration)  
✅ Admin Dashboard for User Management  
✅ RESTful API Backend  
✅ Cloud Pipeline with Docker + GitHub Actions + AWS  
✅ Infrastructure-as-Code using Terraform  
✅ Production Deployment on AWS ECS with Load Balancer & RDS  

---

## 🏗️ Tech Stack

| Layer | Tools / Services |
|-------|------------------|
| **Backend** | Python, Django REST Framework |
| **AI Engine** | OpenAI GPT API |
| **Database** | PostgreSQL (AWS RDS) |
| **Caching / Queue** | Redis |
| **Containerization** | Docker, Docker Compose |
| **CI/CD** | GitHub Actions |
| **Infrastructure** | Terraform |
| **Deployment** | AWS ECS Fargate, ECR, ALB |
| **Storage** | AWS S3 |
| **Frontend (optional)** | Bootstrap, HTML, JS |

---

## 🧱 Repository Structure

ai-resume-saas/
│
├── backend/ # Django project source code
├── docker/ # Dockerfile & docker-compose configuration
├── terraform/ # IaC for AWS infrastructure
├── docs/ # PDF phase guides and architecture diagrams
├── scripts/ # Utility scripts (setup, migrations, etc.)
├── tests/ # Unit & integration tests
│
├── .env.example # Example environment variables
├── .gitignore
├── requirements.txt
└── README.md


---

## 📘 Documentation

All major stages of this project are documented in the `/docs/` folder:

1. **Phase 1** → Backend System Design & GPT Integration  
2. **Phase 2** → Dockerization & Cloud Pipeline (CI/CD)  
3. **Phase 3** → AWS Deployment & Scaling  

---

## ⚙️ Local Setup (Development)

```bash
# Clone repository
git clone https://github.com/Kizito1990/ai-resume-saas.git
cd ai-resume-saas/backend

# Create virtual environment
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start development server
python manage.py runserver

cd docker
docker-compose up --build

CI/CD Pipeline

GitHub Actions automatically builds, tests, and deploys the app.

The pipeline includes:

Build Docker image and push to AWS ECR

Run tests and migrations

Deploy to ECS Fargate

Update Load Balancer and scale containers

   +------------+         +---------------+         +-------------+
   |  GitHub    |  CI/CD  |  AWS ECS      |  Auto   |  Load Balancer |
   |  Actions   |  --->   |  (Fargate)    |  --->   |  (ALB)          |
   +------------+         +---------------+         +-------------+
                                |
                                v
                       +----------------+
                       |   AWS RDS DB   |
                       +----------------+
                                |
                                v
                       +----------------+
                       |   AWS S3 (Files)|
                       +----------------+

🌟 How This Project Helps Me Get Hired

This repository demonstrates:

Backend proficiency (Django, API design, authentication, and AI integration)

DevOps readiness (Docker, CI/CD, AWS, Terraform)

Cloud deployment competence

Professional documentation & project organization



🧑‍💻 Author

Azegba Kizito Amandianeze
Backend Developer | Cloud & AI Enthusiast
🌍 Leiria, Portugal
💼 LinkedIn Profile|www.linkedin.com/in/kizitoamandi

 