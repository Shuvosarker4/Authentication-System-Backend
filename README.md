# Django User Authentication API with Email-Based Login

This project is a Django-based backend API with a custom email-based authentication system, user registration with email activation, Djoser integration for user management, and Swagger documentation.

---

## Features

- Custom User Model using Email as the unique identifier  
- Email-based user registration and account activation  
- Integrated with Djoser for authentication workflows  
- Custom serializers for better control of user data  
- SMTP-based email sending for activation  
- Swagger UI for API documentation and testing  

---

## Project Setup Overview

1. Setup the Django project
2. Create a `users` app
3. Modify `models.py` to implement an email-based authentication system
4. Create a custom user manager in `managers.py` and connect it to the user model

---

## Djoser Integration

- Install Djoser for RESTful authentication endpoints  
- Configure the necessary settings in `settings.py`  
- Implement custom serializers for user creation and management  

---

## Email Activation

- Configure email credentials in `settings.py` for sending activation links  
- On user creation, trigger an activation email  
- Implement activation via token-based URLs  

---

## API Documentation

- Install and configure Swagger (drf-yasg)  
- Use Swagger UI to explore and test available API endpoints  

---

## Summary

This project lays the foundation for a secure and scalable user authentication system with customizable features and full API documentation. Ideal for projects needing user registration, login, email verification, and token-based authentication.
