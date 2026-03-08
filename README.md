# Update server
sudo yum update -y

# Install Nginx
sudo dnf install nginx -y

# Start Nginx
sudo systemctl start nginx

# Enable Nginx on boot
sudo systemctl enable nginx
