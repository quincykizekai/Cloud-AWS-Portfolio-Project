# Cloud-AWS-Portfolio-Project

This is my personal portfolio website hosted on **AWS EC2** and served with **Nginx**.  
It demonstrates deploying a static website on the cloud and managing it with **GitHub**.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Project Structure](#project-structure)
- [How to Run Locally](#how-to-run-locally)
- [License](#license)

---

## Project Overview

This project is a static website for showcasing my work and projects.  
It is designed to be simple, lightweight, and easily deployed on a cloud server.  

- Hosted on **AWS EC2**
- Served via **Nginx**
- Version controlled with **Git & GitHub**

---

## Technologies Used

- **HTML5** – Structure of the website    
- **Nginx** – Web server  
- **AWS EC2** – Cloud hosting  
- **Git & GitHub** – Version control  

---

## Deployment

The website is deployed on an **AWS EC2 instance** using Nginx.  
Steps for deployment:

1. Launch an **EC2 instance** on AWS.
2. Install **Nginx**:
3. Copy website files to "/var/www/html"
4. Ensure proper ownership.
5. Start Nginx and enable it to run on boot.
6. Access your website via the EC2 public IP in a browser.
