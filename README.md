# ☁️ Cloud Infrastructure Automation

[![Terraform](https://img.shields.io/badge/Terraform-1.5-purple.svg)](https://www.terraform.io/)
[![AWS](https://img.shields.io/badge/AWS-Ready-orange.svg)](https://aws.amazon.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-1.27-blue.svg)](https://kubernetes.io/)

## 📋 Overview

Production-ready Infrastructure as Code (IaC) templates for automated cloud deployments. Features Terraform modules, Kubernetes manifests, and CI/CD pipelines.

## 🚀 Features

- **Terraform Modules**: Reusable AWS infrastructure components
- **Kubernetes Manifests**: Production-grade K8s configurations
- **Auto-Scaling**: Dynamic resource allocation
- **High Availability**: Multi-AZ deployments
- **Security First**: IAM roles, Security Groups, KMS encryption
- **Cost Optimization**: Spot instances, reserved capacity

## 📁 Structure

```
├── terraform/
│   ├── modules/
│   │   ├── vpc/
│   │   ├── eks/
│   │   ├── rds/
│   │   └── s3/
│   └── environments/
│       ├── dev/
│       ├── staging/
│       └── prod/
├── kubernetes/
│   ├── deployments/
│   ├── services/
│   └── configmaps/
└── scripts/
    └── deploy.sh
```

## 🛠️ Quick Start

```bash
# Initialize Terraform
cd terraform/environments/dev
terraform init

# Plan infrastructure
terraform plan

# Apply changes
terraform apply

# Deploy to Kubernetes
kubectl apply -f kubernetes/
```

## 📝 License

MIT License

---
**Built with ❤️ by Raju Kanchan**