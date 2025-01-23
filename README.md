# DevOpsified Go Web App

## 🚀 Project Overview
This is a containerized Go web application deployed using Kubernetes, automated with CI/CD pipelines, and managed via ArgoCD for continuous delivery. The project demonstrates skills in cloud-native application deployment, GitHub Actions for CI/CD, and Kubernetes orchestration.

## 🛠️ Tech Stack & Tools
Go – Backend application

Docker – Containerization

Kubernetes – Orchestration

Helm – Package management

ArgoCD – GitOps-based continuous delivery

GitHub Actions – CI/CD pipeline

AWS EC2 – Hosting environment

## ⚙️ Architecture & Workflow
1. Code Changes – Any update triggers GitHub Actions.

2. Build & Push – Docker builds the image and pushes it to DockerHub.

3. Kubernetes Deployment – Helm deploys/updates the app in a cluster.

4. ArgoCD Syncs – ArgoCD monitors the Git repo and applies the latest changes.

## 🔄 CI/CD Pipeline
## GitHub Actions Workflow:
Build & Lint – Ensures code quality.

Docker Image Push – Pushes image to DockerHub.

Helm Chart Update – Updates Kubernetes manifests.

ArgoCD Sync – Ensures latest version is deployed.

## 📸 Screenshots
pod and service status 
![Screenshot 2025-01-23 133819](https://github.com/user-attachments/assets/b08af38e-1141-4df1-9e04-43545827137b)
Helm chart structure and usage
![Screenshot 2025-01-23 151653](https://github.com/user-attachments/assets/9f331a2e-412b-45f2-9445-e535bd019ef6)
CICD pipeline execution in GitHub actions
![Screenshot 2025-01-23 171428](https://github.com/user-attachments/assets/b3d9fe15-2989-4154-b063-2dc93f571f6b)
![Screenshot 2025-01-23 171837](https://github.com/user-attachments/assets/e9c857b2-23a9-43bd-bf2c-6240c017b933)
ArgoCD Dashboard 
![Screenshot 2025-01-23 174513](https://github.com/user-attachments/assets/92076187-7309-47c6-b6ed-dea44cf6dd05)

## 🎯 Key Features
✅ Fully automated CI/CD with GitOps
✅ Kubernetes deployment using Helm
✅ ArgoCD ensures continuous synchronization
✅ Dockerized and cloud-ready

## 📌 Deployment Steps (For Self-Hosting)
1. Install ArgoCD & Helm.

2. Deploy the Helm chart.

3. Configure ArgoCD to sync with this repo.

4. Monitor rollout using kubectl get pods.

## 📢 Future Enhancements
Optimize the pipeline for faster builds

Intergrate monitoring and alerting (e.g Prometheus and Grafana)

Extend the application to include more services or features






