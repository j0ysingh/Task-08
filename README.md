# 🐳 My Cloud App on AWS ECS

This project demonstrates deploying a Dockerized Flask application on AWS Elastic Container Service (ECS) using Fargate and an Application Load Balancer.

---

## 🚀 Project Overview

The app is packaged into a Docker container and hosted on AWS ECS.  
It runs through an Application Load Balancer, making it accessible publicly over HTTP.

---

## 🧩 Files in This Repository

- `Dockerfile` — Defines how the container image is built.  
- `app.py` — Simple Flask web app that runs inside the container.  
- `shortnote.txt` — Brief description of what the container does.  
- Screenshots folder — Contains images of deployed AWS setup.

---

## 🖼️ Required Screenshots

1. ECS Service page showing your running service.  
2. ECS Task showing **RUNNING** status.  
3. EC2 Load Balancer page with DNS name visible.  
4. Browser screenshot showing the running app with the URL visible.

---

## 🌐 Live Test URL

Once deployed, open your app in the browser using your Load Balancer DNS:
http://mycloudapp-lb-1543468163.ap-south-1.elb.amazonaws.com
