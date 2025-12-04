# Terraform Task – Multi-Region EC2 with NGINX

## 📌 Objective
Provision **two EC2 instances** in **two different AWS regions** using a single Terraform configuration.  
Each instance should automatically install and start **NGINX** using `user_data`.

## 🛠 Tech Stack
- Terraform
- AWS EC2
- AWS CLI
- Amazon Linux 2

## 🌍 Regions Used
- **ap-south-1 (Mumbai)** – Primary EC2
- **us-east-1 (N. Virginia)** – Secondary EC2

## 📦 Files Included
- `main.tf` → Terraform configuration file  
- Screenshots → Proof of EC2 creation & NGINX installation  
- `README.md` → This documentation  

## 🚀 Commands Used

### Initialize Terraform
terraform init

### Check Plan
terraform plan

### Apply Infrastructure
terraform apply

### Destroy Infrastructure
terraform destroy

## 📸 Output Screenshots
1. EC2 instance (Mumbai) running  
2. EC2 instance (N. Virginia) running  
3. NGINX default page (Mumbai)  
4. NGINX default page (N. Virginia)  
5. Terraform apply output  

## ✔ Result
Both EC2 instances were successfully created in two regions with NGINX installed automatically.
