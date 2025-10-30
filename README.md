# Terraform Azure VM Deployment ☁️

## 📘 Overview
This project provisions a **Linux Virtual Machine** in Microsoft Azure using **Terraform** as Infrastructure-as-Code (IaC).  
It demonstrates my practical DevOps skills in automating cloud infrastructure.

## 🧰 Tools Used
- Terraform
- Microsoft Azure
- Visual Studio Code
- Git & GitHub
- Azure CLI

## ⚙️ What This Code Does
- Creates an Azure Resource Group  
- Builds a Virtual Network & Subnet  
- Allocates a Public IP & Network Interface  
- Deploys a Linux VM (Ubuntu 22.04 LTS)

## ▶️ How to Run
```bash
terraform init
terraform plan
terraform apply
 (Use terraform destroy to remove resources.)

 Authentication

Terraform is authenticated to Azure via the Azure CLI login (az login)

Future Improvements

Add Ansible to configure software automatically

Integrate CI/CD using GitHub Actions

Containerize apps with Docker