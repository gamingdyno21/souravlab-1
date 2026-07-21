# Cloud Computing Lab 1

## Project Description
This repository contains:
- index.html
- Four image files
- README.md

## Linux Commands Used

### 1. Create/Edit HTML File
```bash
nano index.html
```

### 2. Update System Packages
```bash
sudo yum update -y
```

### 3. Install Apache HTTP Server
```bash
sudo yum install httpd -y
```

### 4. Start Apache Service
```bash
sudo systemctl start httpd
```

### 5. Enable Apache Service at Boot
```bash
sudo systemctl enable httpd
```

### 6. Move HTML File to Apache Web Directory
```bash
sudo mv ~/index.html /var/www/html/
```

### 7. Change Ownership of Web Directory
```bash
sudo chown -R apache:apache /var/www/html/
```

### 8. Restart Apache Service
```bash
sudo systemctl restart httpd
```
