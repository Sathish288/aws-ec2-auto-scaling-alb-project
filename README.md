# Scalable Web Application using EC2, Auto Scaling & Load Balancer

📌 Project Overview
Designed and implemented a highly available and scalable web application architecture on AWS to handle dynamic traffic loads during peak business events (e.g., e-commerce sales).

🔧 AWS Services Used
- Amazon EC2
- Auto Scaling Group
- Application Load Balancer (ALB)
- CloudWatch
- IAM

🎯 Real-World Scenario
During peak sale periods, website traffic increases significantly. The infrastructure automatically scales EC2 instances based on CPU utilization to maintain performance and availability.

---

 🏗 Architecture
- EC2 instances deployed across multiple Availability Zones
- Auto Scaling Group configured for automatic scale-in and scale-out
- Application Load Balancer distributes incoming traffic
- CloudWatch alarms trigger scaling policies
- IAM roles configured for secure access

---

## 🚀 Implementation Steps

1. Launched EC2 instance with Apache/Nginx installed.
2. Configured web server and created a custom AMI.
3. Created Launch Template using the AMI.
4. Configured Auto Scaling Group across multiple AZs.
5. Attached Application Load Balancer to ASG.
6. Created CloudWatch alarms based on CPU utilization.
7. Tested scale-out and scale-in functionality.

---

 ✅ Key Features
- High Availability across multiple AZs
- Automatic scaling based on CPU usage
- Fault tolerance with Load Balancer
- Cost optimization during low traffic
- Secure IAM role-based access

---

 📊 Outcome
- Successfully handled simulated high traffic loads.
- Verified automatic scaling functionality.
- Achieved improved availability and reliability.

---

 📷 Screenshots
(Add screenshots of EC2, ASG, ALB, and CloudWatch here)

---
