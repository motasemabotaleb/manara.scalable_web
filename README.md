# manara.scalable_web


This project demonstrates how to deploy a simple and scalable web application on Amazon Web Services (AWS) using EC2 instances, Application Load Balancer (ALB), and Auto Scaling Group (ASG).

---

## Project Overview

A basic static website was developed using HTML, CSS, and JavaScript. The website is hosted on EC2 instances managed by an Auto Scaling Group to ensure scalability and high availability. An Application Load Balancer distributes incoming traffic across the running instances. Basic AWS best practices were applied for security and monitoring.

---

##  Architecture Diagram

![Architecture](./Architecture%20Diagram.png)

---

##  AWS Services Used

- **Amazon EC2** – to host the static website
- **Application Load Balancer (ALB)** – to distribute incoming traffic
- **Auto Scaling Group (ASG)** – to manage instance scaling
- **Launch Template** – to define instance configuration
- **IAM** – for secure access and permissions
- **Security Groups** – to control inbound/outbound traffic
- **Amazon CloudWatch** (optional) – for monitoring and alerts

---

##  Live Website

You can access the deployed website at the following URL:

 [http://manara-alb-242843011.us-east-1.elb.amazonaws.com](http://manara-alb-242843011.us-east-1.elb.amazonaws.com)


##  Project Structure

Architecture Diagram.png
README.md
loginBtn.html
signupBtn.Html
style.css



##  Deployment Steps

1. Create a Launch Template with EC2 instance details
2. Create an Auto Scaling Group and link it to the Launch Template
3. Set up an Application Load Balancer (ALB) and Target Group
4. Connect the Auto Scaling Group to the Target Group
5. Deploy the website code to the EC2 instances
6. Access the site through the ALB DNS link



##  Demo:

A video demo is not provided, but the project is accessible through the ALB link above.


##  Developed by

**Moatasem AboTaleb**  
  

