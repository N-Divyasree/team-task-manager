Team Task Manager - Full Stack Assignment

Overview:
Team Task Manager is a full-stack web application where users can create projects, assign tasks, and track progress with role-based access for Admin and Member users.

Tech Stack:
Frontend: HTML, CSS, Bootstrap
Backend: Python Flask
Database: SQLite locally / PostgreSQL on Railway
Deployment: Railway

Features:
1. User signup and login
2. Role-based access control for Admin and Member
3. Admin can create projects
4. Admin can create and assign tasks to members
5. Members can view their assigned tasks
6. Admin and assigned members can update task status
7. Dashboard showing total, pending, in-progress, completed, and overdue tasks
8. Validations and database relationships

How to Run Locally:
1. Install Python 3.11 or above
2. Open terminal inside the project folder
3. Run: pip install -r requirements.txt
4. Run: python app.py
5. Open: http://127.0.0.1:5000

Demo Instructions:
1. Create an Admin account from the signup page
2. Create a Member account from the signup page
3. Login as Admin
4. Create a project
5. Create a task and assign it to the Member
6. Login as Member
7. View assigned task and update status

Railway Deployment:
The application is deployed using Railway and is accessible through the submitted live URL.

Project Structure:
app.py - Main Flask application
templates/ - HTML templates
static/style.css - CSS styling
requirements.txt - Python dependencies
Procfile - Railway start command
runtime.txt - Python version
README.txt - Project documentation

Author:
Divya Sree Nadigottu
