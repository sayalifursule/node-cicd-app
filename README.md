# 🚀 Node.js CI/CD Deployment on AWS EC2

## 📌 Project Overview
This project demonstrates deployment of a Node.js application on an AWS EC2 instance. The application is hosted on a Linux server and managed using PM2 to ensure continuous uptime. The project also showcases a basic CI/CD workflow using Git and GitHub.

---

## 🏗️ Architecture
GitHub → AWS EC2 → Node.js Application → PM2 Process Manager

---

## ⚙️ Tech Stack
- Node.js
- AWS EC2 (Amazon Linux)
- Git & GitHub
- PM2 (Process Manager)
- Linux (CLI-based deployment)

---

## 🚀 Features
- Node.js server deployed on AWS EC2
- Application running continuously using PM2
- GitHub repository integration
- Manual CI/CD workflow using Git (pull-based deployment)
- Real-time deployment on cloud server

---

## 📂 Project Structure
node-cicd-app/
├── app.js
├── package.json
├── package-lock.json
└── README.md

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository
git clone https://github.com/your-username/node-cicd-app.git
cd node-cicd-app

---

### 2️⃣ Install Dependencies
npm install

---

### 3️⃣ Run Application Locally
node app.js

---

### 4️⃣ Deploy on AWS EC2

SSH into EC2:
ssh ec2-user@your-ec2-ip

Navigate to project:
cd /home/ec2-user/app

Install dependencies:
npm install

Start application using PM2:
pm2 start app.js --name myapp
pm2 save

---

## 🌐 Application Screenshots

### 🖥️ EC2 Server Running Application
<img width="1920" height="1080" alt="EC2 Screenshot" src="https://github.com/user-attachments/assets/0fd03c5c-beb5-40eb-968b-e3dbcebbfd88" />

---

### 🌍 Application Running in Browser
<img width="1920" height="1020" alt="Browser Screenshot" src="https://github.com/user-attachments/assets/af281d53-3762-4d8b-bb58-a7fedb0584f7" />

---

## 🔄 CI/CD Workflow
Code Changes → Git Commit → Git Push → EC2 Pull → PM2 Restart

---

## 📌 Useful PM2 Commands
pm2 start app.js --name myapp
pm2 list
pm2 restart myapp
pm2 stop myapp
pm2 save

---

## 🎯 Learning Outcomes
- AWS EC2 deployment
- Linux server management
- Process management using PM2
- Git & GitHub workflow
- Basic CI/CD understanding

---

