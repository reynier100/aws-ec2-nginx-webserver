# AWS EC2 Nginx Web Server

This project demonstrates how to deploy a simple website using AWS EC2 and Nginx.

The goal of this project is to practice basic cloud infrastructure, Linux administration, and web server deployment.

---

## Architecture

User → Internet → AWS EC2 → Nginx Web Server

---

## Technologies Used

AWS EC2  
Amazon Linux  
Nginx  
SSH  
GitHub  

---

## Deployment Steps

1. Launch an EC2 instance in AWS.
2. Connect to the instance using SSH.
3. Update the system.
4. Install Nginx.
5. Start the web server.
6. Deploy a simple HTML page.

---

## Example Commands

Update server

sudo yum update -y

Install Nginx

sudo dnf install nginx -y

Start Nginx

sudo systemctl start nginx

Enable Nginx on boot

sudo systemctl enable nginx

---

## Result

A working website hosted on AWS EC2 using Nginx.

This project demonstrates the basics of cloud infrastructure and server deployment.

---

Cloud Engineer in training ☁️
