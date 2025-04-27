# Hostel-Management-System
A complete web-based Hostel Management System designed for easy management of student accommodation.
This project includes separate portals for Admins and Students to streamline operations like room booking, student registration, and hostel maintenance.

Admin Panel
Secure admin login

Add, edit, and delete student profiles

Room allocation and room availability management

View booking history and student room requests

Post hostel notices and announcements

Student Portal
Student registration and login

Apply for hostel room allocation

View assigned room details

Receive updates and announcements

Submit maintenance requests

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript

Backend: PHP (Core PHP)

Database: MySQL

Server: Apache (XAMPP / LAMP / WAMP)

🚀 Installation & Setup
Clone this repository


Copy code
git clone[ https://github.com/your-username/hostel-management-system.git](https://github.com/ADesai2708/Hostel-Management-System.git)
Move the project folder to your server directory:

For XAMPP → C:\xampp\htdocs\

For WAMP → C:\wamp\www\

For LAMP → /var/www/html/

Create the Database:

Open phpMyAdmin.

Create a new database (e.g., hostel_management).

Import the provided .sql file (if you have one) to create tables.

Configure Database Connection:

Open the PHP project files.

Edit the database configuration (likely in a file like config.php or db.php):

php
Copy code
<?php
$conn = mysqli_connect('localhost', 'root', '', 'hostel_management');
?>
Run the project:

Start Apache and MySQL via XAMPP/WAMP/LAMP control panel.

Go to your browser and visit:
http://localhost/hostel-management-system/
