# ☁️ AWS EC2 Resume Hosting Project

## 📌 Project Description
This project demonstrates hosting a **personal resume** on an **Amazon EC2 instance** using **Nginx** and **Amazon Linux 2023**.  
It focuses on EC2 setup, Linux server administration, and deploying static HTML content on AWS.

## ☁️ AWS Services Used
- Amazon EC2
- Amazon VPC
- Security Groups
- Amazon Linux 2023

## 🛠️ Tools & Technologies
- Linux (Amazon Linux 2023)
- Nginx Web Server
- SSH
- HTML
- Git & GitHub

## 🚀 Project Implementation

### **1️⃣ Launch EC2 Instance**
- Created an EC2 instance using Amazon Linux 2023
- Configured a key pair for secure SSH access
- Allowed inbound traffic on **22 (SSH)** and **80 (HTTP)**

### **2️⃣ Connect to EC2 via SSH**
- bash
- ssh -i "yash_key.pem" ec2-user@<EC2-Public-IP>

### **3️⃣ Update System Packages
- sudo dnf update -y

### 4️⃣ Install and Start Nginx
- sudo dnf install nginx -y
- sudo systemctl start nginx
- sudo systemctl enable nginx

### 5️⃣ Host Resume on EC2
- sudo nano /usr/share/nginx/html/index.html
- sudo systemctl restart nginx

### 🌐 Output

-Resume successfully hosted on Amazon EC2
-Accessible via browser using:

-http://<EC2-Public-IP>
