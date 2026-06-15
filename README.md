# 🚀 Terraform S3 Static Website Hosting

## 📌 Project Overview
This project demonstrates Infrastructure as Code (IaC) using Terraform to deploy a static website on AWS S3.  
It automates the creation and configuration of AWS resources required for hosting a static website.

---

## 🛠️ Tech Stack
- Terraform
- AWS S3
- AWS IAM
- Git & GitHub
- HTML/CSS

---

## 🏗️ Architecture
Terraform → AWS S3 Bucket → Static Website Hosting Enabled → Public Website Access

---

## 📁 Project Structure
main.tf  
provider.tf  
variables.tf  
outputs.tf  
.gitignore  
README.md  

---

## 🚀 Features
- Infrastructure as Code using Terraform  
- AWS S3 bucket creation  
- Static website hosting enabled  
- Automated deployment of infrastructure  
- Clean and reusable Terraform code  

---

## ⚙️ Prerequisites
- AWS account  
- AWS CLI configured (`aws configure`)  
- Terraform installed  
- Git installed  

---

## 🚀 Deployment Steps

### 1. Initialize Terraform
terraform init

### 2. Validate configuration
terraform validate

### 3. Plan deployment
terraform plan

### 4. Apply infrastructure
terraform apply

---

## 🌐 Output
After deployment, Terraform will provide the S3 website URL:

http://your-bucket-name.s3-website-ap-south-1.amazonaws.com

---

## ⚠️ Important Notes
- Do NOT upload `.terraform/` folder  
- Do NOT upload `*.tfstate` files  
- Keep AWS credentials secure  
- Always run `terraform plan` before apply  

---

## 📚 Key Learnings
- Infrastructure as Code (IaC)  
- AWS S3 static website hosting  
- Terraform workflow (init → plan → apply)  
- Git best practices  

---

## 👨‍💻 Author
Suyash Potdar

---

## 📜 License
This project is for learning and demonstration purposes.
