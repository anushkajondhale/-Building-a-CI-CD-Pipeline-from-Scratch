CI/CD from Scratch: Flask + Jenkins + Docker

This project demonstrates how to build and deploy a Flask web application inside Docker containers using a fully automated CI/CD pipeline with Jenkins. The goal is to show how modern DevOps practices streamline software delivery, reduce errors, and improve scalability.

🚀 Project Overview

Framework: Flask (Python)

Containerization: Docker

CI/CD Tool: Jenkins

Deployment Target: AWS EC2 (Ubuntu/Debian)

Workflow:

Developer pushes code → GitHub

Jenkins triggers build

Docker image is built & pushed to registry

Container is deployed on AWS EC2 automatically

🛠️ Tech Stack

Flask – Lightweight Python web framework

Docker – Containerization for consistent runtime

Jenkins – CI/CD automation server

AWS EC2 – Cloud infrastructure for hosting

GitHub/Git – Source control & triggers
CI-CD-Flask-Jenkins-Docker/
│── app/
│   ├── app.py              # Flask application
│   ├── requirements.txt    # Python dependencies
│   └── templates/          # HTML files (if any)
│
│── Dockerfile              # Flask app container image
│── docker-compose.yml      # Optional multi-container setup
│── Jenkinsfile             # CI/CD pipeline definition
│── README.md               # Project documentation
