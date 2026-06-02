# Dockerized Web Application on AWS EC2
hay i am Ravi and This is my first Docker project.


In this project, I created a simple static website using HTML and deployed it on an AWS EC2 instance using Docker and Nginx.

## Technologies Used

* AWS EC2 (Amazon Linux 2023)
* Docker
* Nginx
* HTML
* Git & GitHub

## Project Files

* `index.html` – Website page
* `Dockerfile` – Docker image configuration

## Build Docker Image
Run Docker Container
docker run -d -p 80:80 --name mywebsite "ravi-web-app"

what i learned

Docker installation on AWS EC2
Creating a Dockerfile
Building Docker images
Running containers
Port mapping in Docker
Uploading code to GitHub

I am very happy that I completed my first project successfully.
# Docker Web App Project

🚀 This project is a containerized web application deployed on AWS EC2 using Docker.

## Features:
- Docker containerization
- Nginx-based web server
- Deployed on AWS EC2 instance
- Exposed on port 80
- Accessible via public IP

## Commands Used:
docker build -t ravi-web-app .
docker run -d -p 80:80 ravi-web-app

## Docker Hub:
Image pushed to Docker Hub:
ravi1819/ravi-web-app:v1

## AWS Deployment:
Running on EC2 instance with public IP access
