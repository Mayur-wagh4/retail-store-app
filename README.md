# 🚀 Retail Store Sample App - GitOps with Amazon EKS Auto Mode
---

## 📌 Overview

This is a **sample retail store microservices application** designed to demonstrate modern cloud-native concepts on AWS.

It includes:
- Product Catalog Service
- Shopping Cart Service
- Orders Service
- Checkout Service
- UI Frontend Service

The application showcases:
- Microservices architecture
- Kubernetes (Amazon EKS)
- GitOps deployment model
- Infrastructure as Code (Terraform)
- CI/CD automation

---

## 🏗️ Architecture

![Architecture](./docs/images/architecture.png)

| Component | Language | Description |
|-----------|----------|-------------|
| UI | Java | Frontend application |
| Catalog | Go | Product catalog API |
| Cart | Java | Shopping cart API |
| Orders | Java | Order management API |
| Checkout | Node.js | Checkout orchestration API |

---

## ☁️ Infrastructure Architecture

- Amazon EKS (Auto Mode)
- VPC with public/private subnets
- ArgoCD for GitOps
- NGINX Ingress Controller
- Cert Manager for SSL
- Terraform for Infrastructure as Code

---

## 🚀 Quick Start

### Prerequisites
- AWS CLI (v2+)
- Terraform (1.0+)
- kubectl
- Docker
- Helm
- Git

---

## 🔧 Setup & Deployment

### 1️⃣ Clone Repository

```bash
git clone https://github.com/<your-username>/retail-store-sample-app.git
cd retail-store-sample-app
