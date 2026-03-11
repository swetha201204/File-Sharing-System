# File-Sharing-System
# 🔐 KeyLock – Secure File Sharing System

KeyLock is a secure file-sharing web application that allows users to upload and download files with enhanced security using RSA cryptography. The system ensures that only authorized users with the correct private key can access and download files.

This project was developed as a **Final Year B.Tech Information Technology project** to demonstrate secure file management, authentication, and encryption concepts in cloud-based applications.

---

## 🚀 Features

• Secure user registration and login using Spring Security
• RSA-based key generation for secure file access
• Private key displayed only once during account creation
• File upload and secure download functionality
• Role-based dashboard (Admin / Employee)
• MySQL database integration for file and user management
• Modern UI using Thymeleaf templates

---

## 🛠 Tech Stack

Backend
• Java
• Spring Boot
• Spring Security

Frontend
• HTML
• CSS
• Thymeleaf

Database
• MySQL

Tools
• Maven
• Git
• GitHub

---

## 🔐 Security Implementation

The system uses **RSA Cryptography** to generate a unique private key for each user.

• The private key is displayed only once after registration
• Users must provide the correct key to download files
• This prevents unauthorized file access even if login credentials are compromised

---

## 📂 Project Structure

src/main/java
• controller – Handles HTTP requests
• service – Business logic
• repository – Database interaction
• security – Authentication and authorization
• model – Entity classes

src/main/resources
• templates – Thymeleaf HTML pages
• static – CSS and frontend assets
• application.properties – Configuration settings

---

## 🎯 Learning Outcomes

Through this project, I gained experience in:

• Spring Boot application development
• Secure authentication with Spring Security
• RSA cryptographic key generation
• Database integration using MySQL
• Full-stack web application development

---

## 👨‍💻 Author

Swetha S
Interested in Cloud Computing, Security, and Backend Development.

---

## 📌 Future Improvements

• Cloud storage integration (AWS S3)
• File encryption before upload
• Multi-user file sharing
• Activity logging and monitoring
