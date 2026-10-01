raavi-devops-project - Java Web Application CI/CD Project

Project Overview:-
raavi-devops-project is a Java-based web application used to
demonstrate an end-to-end DevOps CI/CD implementation.
The main purpose of this project is to automate the software delivery
process from source code management to application deployment using
industry-standard DevOps tools and practices.

This project provides hands-on experience with:
➢ Git & GitHub
➢ Jenkins CI/CD
➢ Maven
➢ SonarQube
➢ Docker
➢ Docker Hub
➢ Linux
➢ AWS
➢ Kubernetes


Project Purpose:-
The purpose of this project is to build and automate a complete CI/CD
pipeline for a Java web application. Instead of manually building and
deploying the application, the DevOps pipeline automates the major stages
of the software delivery lifecycle.
The workflow is:-
🛠️
Technologies Used ➖
Technology
Purpose
Java
Application development
Maven
Build and dependency management
Git
Version control
GitHub
Source code management
Jenkins
CI/CD automation
SonarQube
Code quality analysis
Docker
Application containerization
Docker Hub
Container image repository
Linux
Server environment
AWS
Cloud infrastructure
Kubernetes
Container orchestration
Project Structure
raavi-devops-project/
│
├── src/
│ └── main/
│ └── webapp/
│
├── deploymentfiles/
│
├── pom.xml
│
├── Dockerfile
│
├── Rk-mycicd-pipeline
├── target
Jenkins Pipeline Stages:-
The CI/CD pipeline can contain the following stages:
1. Checkout
↓
2. SonarQube Analysis
↓
3. Maven Build
↓
4. Docker Build
↓
5. Docker Push
↓
6. Deployment

This automation reduces manual intervention and provides a repeatable application delivery process.
How to Run the Project
Clone Repository
git clone https://github.com/raavir123/mindcircuit13.git
Enter Project Directory
cd mindcircuit13
Build Using Maven
mvn clean package
Build Docker Image
docker build -t mindcircuit13:latest .
Run Docker Container
docker run -d -p 8080:8080 raavir16:latest
Check the application:
http://localhost:8080

📊 DevOps Concepts Demonstrated
This project demonstrates practical knowledge of:
➢ Version control with Git
➢ GitHub repository management
➢ Branching and merging
➢ Jenkins CI/CD
➢ Maven automation
➢ SonarQube integration
➢ Docker containerization
➢ Docker image management
➢ Docker Hub integration
➢ Linux administration
➢ AWS cloud deployment
➢ Kubernetes deployment
➢ Infrastructure/application automation

Learning Objectives :-
The project was created to gain practical experience in designing and implementing an end-to-end DevOps workflow.
The key learning objectives are:
1. Understand Git-based development workflows.
2. Automate application builds using Jenkins.
3. Integrate SonarQube into CI pipelines.
4. Build Java applications using Maven.
5. Containerize applications using Docker.
6. Push container images to Docker Hub.
7. Deploy applications using Kubernetes.
8. Understand CI/CD automation in a cloud environment.
Disclaimer:-
This project is created for learning, practice, and DevOps interview demonstration purposes.
