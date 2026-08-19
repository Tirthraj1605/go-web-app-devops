# End-to-End Kubernetes CI/CD Pipeline with GitOps

A complete production-ready CI/CD pipeline for a Go web application using **GitHub Actions**, **Docker**, **Kubernetes (AKS)**, **Helm**, and **Argo CD** (GitOps).

![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-4C4C4C?logo=argo&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoft-azure&logoColor=white)

---

## Overview

This project showcases a modern **End-to-End DevOps workflow** that automatically builds, containers, and deploys a Go web application to **Azure Kubernetes Service (AKS)** using GitOps principles.

---

## Features

- Fully automated CI/CD using GitHub Actions
- Multi-stage Docker builds with distroless image
- GitOps deployment with Argo CD
- Automatic Helm chart updates on code change
- Zero-downtime deployment demonstration

---

## Tech Stack

- **Language**: Go
- **CI/CD**: GitHub Actions
- **Containerization**: Docker (Multi-stage + Distroless)
- **Orchestration**: Kubernetes (AKS)
- **Package Manager**: Helm
- **GitOps Tool**: Argo CD
- **Cloud**: Microsoft Azure
- **Ingress**: NGINX Ingress Controller

---

## Pipeline Workflow

1. Developer pushes code to `main` branch
2. GitHub Actions builds & tests the application
3. Docker image is built and pushed to Docker Hub
4. Helm values.yaml is automatically updated with new image tag
5. Argo CD detects the change and syncs the application to AKS
6. New version is live with zero manual deployment

---

## Key Highlights

- Production-optimized Docker images
- Self-healing GitOps deployment
- Clear demonstration of automation power


