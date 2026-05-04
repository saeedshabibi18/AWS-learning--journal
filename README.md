# ☁️ AWS & DevOps Hands-On Journal — Saeed Shabibi

A structured, self-maintained documentation of real AWS and DevOps implementations. Every entry in this journal is hands-on — not just theory.

> Built while learning. Documented while doing. This is my DevOps journey.

---

## 📁 Project Index

| # | Project | Tools Used |
|---|---------|------------|
| 01 | [Flask Web App on AWS EC2](#01-flask-web-app-on-aws-ec2) | EC2, Amazon Linux, Flask, Python |
| 02 | [Flask App on AWS using Docker](#02-flask-app-on-aws-using-docker) | EC2, Docker, Flask |
| 03 | [Docker Swarm Two-Node Cluster](#03-docker-swarm-two-node-cluster) | Docker Swarm, EC2, Linux |
| 04 | [EC2 Auto Scaling & Monitoring](#04-ec2-auto-scaling--monitoring) | EC2, CloudWatch, Auto Scaling Groups |
| 05 | [EC2 Website Boot at Launch](#05-ec2-website-boot-at-launch) | EC2, User Data Scripts, Bash |
| 06 | [Docker Compose on AWS](#06-docker-compose-on-aws) | Docker Compose, EC2 |
| 07 | [Troubleshooting Examples](#07-troubleshooting-examples) | Linux, Docker, AWS |

---

## 01 — Flask Web App on AWS EC2

**What I did:**
Deployed a Python Flask web application on an AWS EC2 instance running Amazon Linux. Configured security groups, installed dependencies, and ran the app as a live web server.

**Key concepts covered:**
- EC2 instance launch and SSH access
- Security group configuration (inbound rules for HTTP/SSH)
- Installing Python, pip, Flask on Amazon Linux
- Running Flask app and exposing it to the internet

📂 [`01-flask-ec2-deployment/`](./01-flask-ec2-deployment/)

---

## 02 — Flask App on AWS using Docker

**What I did:**
Containerized a Flask application using Docker and deployed the container on an AWS EC2 instance. Combined cloud and containerization in a single workflow.

**Key concepts covered:**
- Writing a Dockerfile for a Python Flask app
- Building and running Docker containers on EC2
- Exposing container ports to the internet via EC2 security groups

📂 [`02-flask-docker-on-aws/`](./02-flask-docker-on-aws/)

---

## 03 — Docker Swarm Two-Node Cluster

**What I did:**
Set up a Docker Swarm cluster with two EC2 instances — one as manager and one as worker node. Deployed services across the cluster.

**Key concepts covered:**
- Docker Swarm initialization and node joining
- Manager vs worker node roles
- Deploying and scaling services across nodes
- Container orchestration basics

📂 [`03-docker-swarm-cluster/`](./03-docker-swarm-cluster/)

---

## 04 — EC2 Auto Scaling & Monitoring

**What I did:**
Configured EC2 Auto Scaling Groups with CloudWatch alarms to automatically scale instances based on CPU utilization. Set up monitoring dashboards.

**Key concepts covered:**
- Launch templates and Auto Scaling Groups
- CloudWatch metrics and alarms
- Scale-out and scale-in policies
- Monitoring EC2 performance in real time

📂 [`04-ec2-autoscaling-monitoring/`](./04-ec2-autoscaling-monitoring/)

---

## 05 — EC2 Website Boot at Launch

**What I did:**
Used EC2 User Data scripts to automatically install and launch a web server every time an instance starts — fully automated from boot.

**Key concepts covered:**
- EC2 User Data and cloud-init scripts
- Automating server setup with Bash
- Hosting a static website on EC2 automatically

📂 [`05-ec2-website-boot-at-launch/`](./05-ec2-website-boot-at-launch/)

---

## 06 — Docker Compose on AWS

**What I did:**
Ran multi-container applications using Docker Compose on an AWS EC2 instance. Managed container networking and service dependencies in a cloud environment.

**Key concepts covered:**
- Installing and using Docker Compose on EC2
- Multi-container networking on cloud infrastructure
- Managing environment variables and volumes

📂 [`06-docker-compose-on-aws/`](./06-docker-compose-on-aws/)

---

## 07 — Troubleshooting Examples

Real errors I encountered and how I fixed them. Because troubleshooting is a core DevOps skill.

📂 [`07-troubleshooting-examples/`](./07-troubleshooting-examples/)

---

## 🛠️ Tech Stack

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

## 🔖 Topics / Keywords

`aws` `ec2` `docker` `docker-swarm` `docker-compose` `flask` `python` `linux` `cloud` `devops` `autoscaling` `cloudwatch` `bash` `fresher-devops`

---

## 👨‍💻 About Me

Final-year B.Tech student specializing in **DevOps & Cloud Engineering**.
Actively seeking fresher/internship roles in DevOps and Cloud.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN-HERE)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/saeedshabibi18)
