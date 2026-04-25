# aws-3tier-architecture
# AWS 3-Tier Architecture with ALB and Bastion Host

## 📌 Overview
This project demonstrates a secure and scalable AWS architecture using VPC, public and private subnets, Application Load Balancer, Bastion Host, and private EC2 instances.

---

## 🧱 Architecture
User → ALB → Private EC2  
Admin → Bastion → Private EC2  

---

## 🔐 Security
- No public access to private EC2
- SSH only via Bastion Host
- EC2 accepts traffic only from ALB
- Layered Security Groups

---

## 📸 Screenshots

### VPC Setup
![VPC](screenshots/1-vpc.png)

### Subnets
![Subnets](screenshots/2-subnets.png)

### Security Groups
![Security](screenshots/3-security-groups.png)

### ALB Working
![ALB](screenshots/4-alb-working.png)

### Target Group Healthy
![Target](screenshots/5-target-healthy.png)

---

## 🚀 Services Used
- AWS VPC
- EC2
- Application Load Balancer
- Security Groups
- NAT Gateway

---

## 🎯 Outcome
Built a production-style secure architecture where backend servers are not directly exposed to the internet.
