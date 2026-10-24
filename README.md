# 🚀 Terraform + AWS + Jenkins Infrastructure Automation

## 📌 Project Overview

This project demonstrates automated AWS infrastructure
provisioning using Terraform and Jenkins CI/CD Pipeline.

Terraform is used to create and manage AWS infrastructure
as Infrastructure as Code (IaC), while Jenkins automates
the Terraform workflow through a CI/CD pipeline.

The project helps reduce manual infrastructure setup
and makes infrastructure deployment more consistent
and repeatable.

## 🎯 Project Objectives

- Automate AWS infrastructure provisioning.
- Create AWS resources using Terraform.
- Integrate Terraform with Jenkins.
- Manage project code using Git and GitHub.
- Execute Terraform commands through Jenkins Pipeline.
- Understand real-world DevOps automation.

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| AWS        | Cloud Infrastructure |
| Terraform  | Infrastructure as Code |
| Jenkins    | CI/CD Automation |
| Git        | Version Control |
| GitHub     | Source Code Management |
| Linux      | Server Administration |

## ☁️ AWS Resources

The project configuration includes the following resources:

- AWS VPC
- Public Subnet
- Internet Gateway
- Route Table
- Route Table Association
- Security Group
- EC2 Instance

The exact resources created depend on the Terraform
configuration files in this repository.

## 🏗️ Project Architecture

Developer
    |
    v
Git / GitHub Repository
    |
    v
Jenkins Pipeline
    |
    v
Terraform Init
    |
    v
Terraform Validate
    |
    v
Terraform Plan
    |
    v
Terraform Apply
    |
    v
AWS Infrastructure
    |
    +-- VPC
    +-- Public Subnet
    +-- Internet Gateway
    +-- Route Table
    +-- Security Group
    +-- EC2 Instance

## 📂 Project Structure

```text
Terraform-aws-jenkins-infrastructure-project/
│
├── Jenkinsfile
├── provider.tf
├── variables.tf
├── vpc.tf
├── subnet.tf
├── internet-gateway.tf
├── route-table.tf
├── security-group.tf
├── jenkins-server.tf
├── outputs.tf
└── README.md
