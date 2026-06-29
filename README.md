Module 10 Assignment - Dockerize and Deploy Express.js App Using Docker Compose with Nginx
Overview

This project demonstrates how to containerize an Express.js application using Docker and deploy it alongside an Nginx container using Docker Compose.

Technologies Used
Node.js
Express.js
Docker
Docker Compose
Nginx
Project Structure
.
├── Dockerfile
├── docker-compose.yml
├── .dockerignore
├── nginx
│   └── default.conf
├── package.json
├── package-lock.json
└── src
Docker Image

DockerHub Repository:

https://hub.docker.com/r/mirajhossaincse/module-3-deployment

Build the Application
docker compose build
Run the Application
docker compose up -d
Stop the Application
docker compose down
Verify Running Containers
docker ps
Access the Application

Open your browser and visit:

http://localhost:8080
Docker Compose Services
Express App
Built from Dockerfile
Runs on port 5000
Nginx
Uses the official Nginx image
Exposes the application on port 8080
Proxies requests to the Express application
Assignment Objectives Completed
Dockerized the Express.js application
Built and ran the application using Docker Compose
Ran an Nginx container
Exposed the application on port 8080
Pushed the Docker image to DockerHub
Uploaded the project to GitHub

#Screenshoot
App running:<img width="1692" height="824" alt="Assignment10_localhost" src="https://github.com/user-attachments/assets/7a33216d-356f-48e0-aa0e-776f099bb147" />
Docker Image on DockerHub: <img width="1844" height="866" alt="Assigment10_DockerHub" src="https://github.com/user-attachments/assets/afee4b53-4b38-4dc4-b252-52c5ff3180c2" />
Docker Push Success: <img width="1204" height="1173" alt="DockerPushCommand" src="https://github.com/user-attachments/assets/3d960217-2546-4265-870f-32783a777fac" />



Author

Miraj Hossain
