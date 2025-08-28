---

# 🚀 Static Website Hosting on AWS with CI/CD  
**Powered by Terraform + AWS DevOps Tools**

This project showcases how to host a blazing-fast static website 🌐 using **Amazon S3**, with a fully automated CI/CD pipeline 🔁 for seamless deployments. Infrastructure is provisioned using **Terraform**, while **AWS-native DevOps tools** like CodePipeline, CodeBuild, and CodeDeploy handle the automation magic ✨.

---

## 📌 Key Features
- 🗂️ Static website hosted on **Amazon S3**
- 🔄 Fully automated **CI/CD pipeline**
- 🛠️ Infrastructure as Code with **Terraform** (EC2, S3, IAM)
- 🧩 Pipeline built using **CodePipeline**, **CodeBuild**, and **CodeDeploy**
- 🔗 GitHub integration for auto-deployments on code push
- 🔐 Secure IAM role management for service communication

---

## 🛠️ Tools & Services Used
- 💻 **AWS EC2** – Terraform execution & infra management
- 🗃️ **AWS S3** – Static file hosting
- 📦 **Terraform** – Provisioning EC2, S3, IAM
- 🛡️ **AWS IAM** – Role-based access control
- 🔁 **AWS CodePipeline** – CI/CD orchestration
- 🧪 **AWS CodeBuild** – Build & validate static files
- 🚚 **AWS CodeDeploy** – Deploy files to S3
- 🐙 **GitHub** – Source code repository

---

## ⚙️ CI/CD Workflow Overview

### 🏗️ Infrastructure Setup
- Launch EC2 🖥️
- Provision S3 bucket 🪣 & IAM roles 🔐 using Terraform

### 🔄 Pipeline Configuration
- Set up **CodePipeline** via AWS Console
- Source: GitHub 🐙
- Build: CodeBuild 🧪
- Deploy: CodeDeploy 🚚 to S3

### 🚀 Build & Deploy
- On code push ➡️ Pipeline triggers
- CodeBuild validates files ✅
- CodeDeploy updates S3 bucket 🔄

### 🌍 Hosting
- S3 bucket serves static files 📁
- Public URL available for access 🔗

---

## 🚀 How to Deploy

1. 🖥️ Launch EC2 instance & SSH into it  
2. ⚙️ Install Terraform & AWS CLI  
3. 📥 Clone repo & navigate to Terraform config  
4. 🧱 Run `terraform init` & `terraform apply`  
5. 🛠️ Create CodePipeline in AWS Console  
   - Source: GitHub  
   - Build: CodeBuild  
   - Deploy: CodeDeploy to S3  
6. 📤 Push code to GitHub — Pipeline auto-triggers & deploys site 🌐

---
