Kubernetes MongoDB & WebApp Deployment

This repository contains Kubernetes manifests for deploying a MongoDB database and a web application using ConfigMaps, Secrets, and Services.

🚀 Deployment Guide

1️⃣ Clone the Repository

git clone https://github.com/LauraOkafor/k8s-mongo-webapp.git

cd your-repo-name

2️⃣ Apply Kubernetes Manifests

kubectl apply -f .

3️⃣ Verify Deployments & Services

kubectl get pods
kubectl get services

4️⃣ Access the Web Application

Get the NodePort for the web app:
kubectl get svc webapp-service

Open in your browser:
http://:30100

