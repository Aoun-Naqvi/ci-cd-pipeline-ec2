# Flask App with GitHub Actions CI/CD to AWS EC2

## Project Overview
This project contains a simple Flask app that is automatically deployed to an AWS EC2 instance using GitHub Actions CI/CD pipeline.

## CI/CD Pipeline
- Trigger: Push to `main` branch
- Actions:
  1. Checkout code
  2. SSH to EC2
  3. Copy code to EC2
  4. Install Docker & set permissions
  5. Build and run Flask container

## Technologies Used
- Flask
- Docker
- GitHub Actions
- AWS EC2 (Ubuntu)
- SSH Agent

## Secrets
The following GitHub secrets are used:
- `EC2_SSH_KEY`: Your private key to access EC2

## Live App
> http://<....>


