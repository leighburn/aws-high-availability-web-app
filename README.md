# AWS High Availability Web App

## 🚀 Project Overview
This project demonstrates a highly available web application architecture built on AWS. It is designed to ensure reliability, scalability, and fault tolerance by distributing traffic across multiple servers.

## 🏗️ Architecture
- VPC with public subnets
- EC2 instances deployed across multiple availability zones
- Application Load Balancer to distribute traffic
- Security Groups for controlled access

## 🔄 How it works
User → Application Load Balancer → EC2 Instances → Response

## 💡 What I learned
- AWS networking fundamentals (VPC, subnets, routing)
- Load balancing concepts and traffic distribution
- High availability design across multiple availability zones

## 🔮 Future Improvements
- Add Auto Scaling Group for dynamic scaling
- Implement HTTPS using AWS Certificate Manager (ACM)
- Automate infrastructure using Terraform
