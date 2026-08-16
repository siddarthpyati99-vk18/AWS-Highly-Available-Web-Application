\# AWS Highly Available Web Application



A highly available web application deployed on AWS using Amazon VPC, EC2, and an Application Load Balancer across multiple Availability Zones.



\## 🚀 Project Overview



This project demonstrates how to design and deploy a highly available web application using AWS networking and compute services.



Two Amazon EC2 web servers are deployed in separate Availability Zones and placed behind an Application Load Balancer. The ALB performs health checks and automatically routes traffic to healthy instances.



\## 🏗️ Architecture



```text

&#x20;                        Internet

&#x20;                           │

&#x20;                           ▼

&#x20;               Application Load Balancer

&#x20;                    cloud-engineer-alb

&#x20;                           │

&#x20;                    Target Group

&#x20;                     /          \\

&#x20;                    ▼            ▼

&#x20;             EC2 Web Server 1  EC2 Web Server 2

&#x20;                us-east-1a        us-east-1b

&#x20;                    │                │

&#x20;             public-subnet-1a  public-subnet-1b

&#x20;                    │                │

&#x20;                    └────── VPC ─────┘

&#x20;                        10.0.0.0/16

