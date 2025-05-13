# 🐳 azure-k8s-cli

A lightweight Docker image with the essential CLI tools for working with Azure and Kubernetes.

## 🔧 Tools Included:

- Azure CLI (az) – Interact with Azure services
- kubectl – Manage Kubernetes clusters
- kubelogin – Azure AD authentication for kubectl (used with AKS)
- Helm - Package Management for Kubernetes

## 📦 Base Image:

debian:stable-slim

## ✅ Use Cases:

- Azure Kubernetes Service (AKS) management
- CI/CD pipelines
- Local dev environments
- Cloud automation scripts

## 🚀 Quick Start:
```bash
docker pull ghcr.io/adilansari488/azure-k8s-cli:latest
docker run -it ghcr.io/adilansari/azure-k8s-cli
```
