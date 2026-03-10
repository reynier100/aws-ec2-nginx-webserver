# AWS EC2 Nginx Web Server Project

## Overview
This project demonstrates how to deploy a web server on AWS EC2 using Nginx.

The goal of the project is to understand basic cloud infrastructure, Linux server management, and web server deployment.

## Architecture

User → Internet → AWS EC2 Instance → Nginx Web Server → Static Website

## Technologies Used

- AWS EC2
- Amazon Linux
- Nginx
- Linux CLI
- GitHub

## Deployment Steps

### Update server
sudo yum update -y

### Install Nginx
sudo dnf install nginx -y

### Start Nginx
sudo systemctl start nginx

### Enable Nginx on boot
sudo systemctl enable nginx

## Project Files

index.html – simple webpage hosted by Nginx.

## What I Learned

- Launching EC2 instances
- Connecting to Linux using SSH
- Installing and configuring Nginx
- Hosting a static website on AWS
