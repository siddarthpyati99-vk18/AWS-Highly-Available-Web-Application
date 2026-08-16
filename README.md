# AWS Highly Available Web Application

A highly available web application deployed on AWS using Amazon VPC, EC2, and an Application Load Balancer across multiple Availability Zones.

## 🚀 Project Overview

This project demonstrates how to design and deploy a highly available web application using AWS networking and compute services.

Two Amazon EC2 web servers are deployed in separate Availability Zones and placed behind an Application Load Balancer. The ALB performs health checks and automatically routes traffic to healthy instances.

## 🏗️ Architecture

![AWS Highly Available Web Application Architecture](architecture-diagram.png)

The application is deployed across two Availability Zones using Amazon EC2 and an Application Load Balancer. The ALB performs health checks and routes incoming traffic to healthy EC2 instances.

## ☁️ AWS Services Used

- Amazon VPC
- Amazon EC2
- Application Load Balancer
- Target Groups
- Internet Gateway
- Route Tables
- Security Groups
- Availability Zones

## 📸 Project Screenshots

### 1. VPC Configuration

![VPC Configuration](screenshots/01-vpc.png)

### 2. Subnets Across Availability Zones

![Subnets](screenshots/02-subnets.png)

### 3. Internet Gateway

![Internet Gateway](screenshots/03-internet-gateway.png)

### 4. Route Table

![Route Table](screenshots/04-route-table.png)

### 5. ALB Security Group

![ALB Security Group](screenshots/05-alb-security-group.png)

### 6. EC2 Security Group

![EC2 Security Group](screenshots/06-ec2-security-group.png)

### 7. EC2 Instances

![EC2 Instances](screenshots/07-ec2-instances.png)

### 8. Target Group

![Target Group](screenshots/08-target-group.png)

### 9. Application Load Balancer

![Application Load Balancer](screenshots/09-load-balancer.png)

### 10. ALB Website

![ALB Website](screenshots/10-alb-website.png)

### 11. High Availability — Unhealthy Target

![Unhealthy Target](screenshots/11-ha-test-unhealthy.png)

### 12. High Availability — Website Continues Working

![High Availability Test](screenshots/12-ha-test-website.png)

### 13. Restored Targets

![Restored Targets](screenshots/13-restored-targets.png)