Flask App CI/CD Pipeline with Jenkins, Docker & AWS

This project showcases a complete DevOps workflow for deploying a simple Python Flask web application. It uses Jenkins for automation, Docker for containerization, and AWS EC2 as the cloud hosting platform, with GitHub handling the source code.

Tech Stack
	1.AWS EC2 – Hosts the application in the cloud
	2.Jenkins – Manages the CI/CD pipeline
	3.Docker – Packages the app into containers
	4.GitHub – Stores and tracks the source code
	5.Python Flask – Lightweight framework for the web app

Project Objective
  The goal is to automate the entire deployment process. Here's how it works:

	1.You push new code to GitHub
	2.Jenkins detects the change and pulls the latest code
	3.It builds a Docker image of the app
	4.Then, Jenkins runs the app inside a Docker container
	5.Finally, it deploys the container to an AWS EC2 instance

This setup ensures that every code update goes live smoothly, reliably, and automatically.