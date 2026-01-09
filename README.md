# Host a Web App on AWS (EC2)

## 📌 Project Overview
This project demonstrates how to host a simple web application on Amazon Web Services (AWS) using an EC2 instance and Apache Web Server. The goal of this project is to understand cloud fundamentals, server configuration, and secure public access.

---

## 🛠️ Technologies & Services Used
- AWS EC2
- Amazon Linux 2
- Apache HTTP Server
- HTML
- AWS Security Groups
- Elastic IP (optional)

---

## 🏗️ Project Architecture
User Browser → Public IP → AWS EC2 Instance → Apache Web Server → Web Application

---

## 🚀 Deployment Steps
1. Created an AWS EC2 instance (Amazon Linux 2, t2.micro)
2. Configured Security Group to allow:
   - SSH (Port 22)
   - HTTP (Port 80)
3. Connected to EC2 using SSH / EC2 Instance Connect
4. Installed Apache Web Server
5. Started and enabled Apache service
6. Deployed website files to `/var/www/html`
7. Accessed the application using the EC2 Public IPv4 address

---

## 🧠 Key Learnings
- Hands-on experience with AWS EC2
- Linux server management
- Cloud security using security groups
- Hosting and deploying a web application on cloud infrastructure

---

## 🎤 Interview Explanation
“I hosted a web application on AWS EC2 by configuring an Amazon Linux server, installing Apache, managing security group rules for HTTP access, and deploying the application files. I verified the deployment locally and made it publicly accessible using the EC2 public IP.”

---

## 👤 Author
**Mohammad Shadik**
