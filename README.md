# 🌐 AWS Cloud Web Application Project

## 📌 Project Overview
This project demonstrates the design and implementation of a full cloud-based web system using AWS services. The system includes compute resources, storage, deployment, monitoring, and security considerations.

---

### ☁️ 1. Infrastructure as a Service (IaaS) – EC2
Amazon EC2 was used to create a virtual server in the cloud.

Implementation Steps:
- Create an EC2 instance using Ubuntu
- Open HTTP Port 80
- Install Apache Web Server
- Upload index.html file

Outcome:  
A web application is successfully running using the server’s Public IP.

---

### 🗄️ 2. Storage – S3
Amazon S3 was used to store project files.

Steps:
- Create an S3 Bucket
- Upload project files
- Use S3 as a backup

---

### 🚀 3. Application Deployment
The application was deployed on EC2 using Apache.

Access Link:  
http://<EC2-Public-IP>

---

### 🔄 4. Auto Scaling
Auto Scaling was configured to ensure system availability.

Settings:
- Minimum Instances: 1
- Maximum Instances: 2
- Automatic scaling based on demand

---

### 📊 5. Monitoring (CloudWatch Metrics)
CloudWatch was used to monitor system performance.

Metrics Monitored:
- CPU Utilization
- Network Usage

Features:
- Ability to create alerts when load increases

---

### 📜 6. Service Level Agreement (SLA)
The system guarantees a high service level:

- Availability: 99%
- Downtime Recovery: Within 1 hour
- Monitoring: Continuous via CloudWatch

---

### 🌍 7. Deployment Model
Used Deployment: ✅ Public Cloud

Reason:  
AWS provides online services that are generally accessible, easy to use, and flexible.

---

### 🔐 8. Security Risk Analysis
Risks:
- Unauthorized Access
- DDoS Attacks
- Weak Passwords

Solutions:
- Use Security Groups
- Keep system updated regularly
- Use HTTPS
- Manage user permissions

---

### 🎥 9. Project Demo Video
A short video was recorded showing:
- EC2 setup
- Project upload
- Website running
- Usage of AWS services

---

# ✅ Conclusion
This project successfully demonstrates how to deploy and manage a cloud-based web application using AWS services, including EC2, S3, Auto Scaling, and CloudWatch.

---

## 👨‍💻 Author
### Student Name: Mayar Waleed Nawas  
### Course: Cloud Computing  
### Instructor: Dr. Sameh Abu Hasira