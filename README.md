Staff Leave Management System (SLMS)
Overview

The Staff Leave Management System (SLMS) is a web-based application developed to simplify and automate the process of managing employee leave requests within an organization or institution. The system allows staff members to apply for leave online, while administrators can review, approve, or reject leave applications efficiently.

This project helps reduce paperwork, improve transparency, and maintain accurate leave records.

Features
Staff Features
User Registration and Login
Apply for Leave
View Leave History
Check Leave Status
Dashboard Access
Admin Features
Admin Login
View All Leave Requests
Approve or Reject Leave Applications
Manage Staff Records
Dashboard for Leave Monitoring
Technologies Used
Technology	Purpose
Python	Backend Programming
Django	Web Framework
HTML	Structure of Web Pages
CSS	Styling and Design
JavaScript	Client-side Functionality
SQLite	Database Management
Project Structure
slms_project/
│
├── accounts/                 # User authentication and account management
├── leave/                    # Leave management application
├── templates/                # HTML templates
├── db.sqlite3                # SQLite database
├── manage.py                 # Django project manager
└── slms_project/             # Main project settings
Installation and Setup
Step 1: Clone the Repository
git clone <repository-link>
cd slms_project
Step 2: Create Virtual Environment
python -m venv venv
Step 3: Activate Virtual Environment
Windows
venv\Scripts\activate
Linux / Mac
source venv/bin/activate
Step 4: Install Dependencies
pip install django
Step 5: Run Database Migrations
python manage.py migrate
Step 6: Start Development Server
python manage.py runserver
Step 7: Open in Browser
http://127.0.0.1:8000/
Modules Description
Accounts Module

Handles:

User Registration
User Login and Logout
Authentication
Leave Module

Handles:

Leave Application
Leave Approval/Rejection
Leave Tracking
Database

The project uses SQLite as the default database.

Database file:

db.sqlite3
Future Enhancements
Email Notifications
Role-based Access Control
Leave Balance Calculation
Report Generation
Mobile Responsive Design
Department-wise Leave Tracking
Advantages
Easy Leave Management
Reduces Manual Work
Faster Approval Process
Secure Authentication
Centralized Data Storage
Conclusion

The Staff Leave Management System provides an efficient solution for managing employee leave applications digitally. It improves communication between staff and administrators while reducing paperwork and maintaining accurate records.

Author

Developed by CHINMAI

License

This project is developed for educational and learning purposes.# Staff-Leave-Management-System-SLMS-
