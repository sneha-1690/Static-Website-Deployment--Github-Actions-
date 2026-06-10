# CI/CD Pipeline for Static Website Deployment using GitHub Actions and AWS S3

## Project Overview

This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a static website using GitHub Actions and Amazon S3.

The website is automatically deployed to an Amazon S3 bucket whenever changes are pushed to the GitHub repository. This eliminates manual deployment and ensures faster, reliable, and consistent website updates.

---

## Objective

The main objective of this project is to automate the deployment process of a static website using DevOps practices and AWS cloud services.

### Goals

- Host a static website using Amazon S3
- Implement Continuous Integration and Continuous Deployment (CI/CD)
- Automate website deployment using GitHub Actions
- Secure AWS credentials using GitHub Secrets
- Reduce manual deployment effort and errors
- Gain hands-on experience with cloud and DevOps tools

---

## Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
GitHub Actions Workflow
    │
    ▼
Amazon S3 Bucket
    │
    ▼
Static Website
```

---

## Technologies Used

- Amazon S3
- AWS IAM
- Git
- GitHub
- GitHub Actions
- HTML
- CSS
- JavaScript

---

## Features

- Automated deployment on every push to the main branch
- Secure credential management using GitHub Secrets
- Static website hosting using Amazon S3
- Continuous delivery of website updates
- Version control using Git and GitHub

---

## Project Workflow

### Step 1: Create GitHub Repository

- Create a repository on GitHub.
- Clone the repository locally.

### Step 2: Add Website Files

- Create a static website using HTML, CSS, and JavaScript.
- Push website files to GitHub.

### Step 3: Create S3 Bucket

- Create an Amazon S3 bucket.
- Enable Static Website Hosting.
- Configure bucket permissions.

### Step 4: Configure IAM User

- Create an IAM user with S3 access permissions.
- Generate Access Key and Secret Access Key.

### Step 5: Configure GitHub Secrets

Store AWS credentials securely in GitHub Secrets:

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY

### Step 6: Create GitHub Actions Workflow

Create a workflow file:

```text
.github/workflows/deploy.yml
```

The workflow automatically uploads website files to Amazon S3 whenever changes are pushed to the repository.

### Step 7: Deploy Website

- Make changes to website files.
- Commit and push changes.
- GitHub Actions automatically deploys the updated website to Amazon S3.

---

## Repository Structure

Static-Website-Deployment/
│
├── index.html
├── style.css
├── script.js
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── screenshots/
│   ├── website-homepage.png
│   ├── github-actions-success.png
│   ├── s3-bucket.png
│   └── website-live.png
│
└── README.md

## Learning Outcomes

Through this project, I gained practical experience in:

- AWS S3 Static Website Hosting
- IAM User Management
- Git and GitHub
- GitHub Actions
- CI/CD Pipeline Implementation
- Secure Credential Management
- Automated Deployments
- Cloud Infrastructure Fundamentals

---

## Note

This project was successfully deployed and tested using Amazon S3 Static Website Hosting and GitHub Actions. The AWS resources were later removed to avoid ongoing cloud costs.

---

## Author

Sneha Alhat

Aspiring Cloud & DevOps Engineer

Skills: AWS | Git | GitHub Actions | Linux | Docker | Terraform | CI/CD
