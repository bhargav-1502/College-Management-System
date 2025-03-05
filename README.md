# College-Management-System

# Overview
This College Management System is a simple console-based application built using Python and Object-Oriented Programming (OOP) principles. It allows users to manage colleges, teachers, and students efficiently while integrating email-based OTP verification for security.

# Features
- Create and manage multiple colleges
- Add and manage teachers (Name, Email, Subject)
- Add and manage students (Name, Email, Branch)
- Email-based OTP verificatio for adding teachers & students
- Display teacher and student details
- User-friendly menu-driven interface

# Technologies Used
- **Python** (Object-Oriented Programming)
- **SMTP (Simple Mail Transfer Protocol)** for email verification
- **Console-based user interaction**

# Installation & Usage
# 1️⃣ Clone the Repository:
```bash
git clone https://github.com/yourusername/College-Management-System.git
cd College-Management-System
```
# 2️⃣ Install Dependencies (if any):
This script uses Python's built-in `smtplib`, `random`, and `email` modules, so no external dependencies are required.

#3️⃣ Run the Application:
```bash
python CMS.py
```

# How It Works
1. Create a college by entering a unique college ID and name.
2. Add teachers with name, email, and subject. The system sends an OTP for verification before registration.
3. Add students with name, email, and branch, following the same OTP verification process.
4. Display teacher and student details** associated with a college.
5. Secure email authentication ensures only verified users are added.





