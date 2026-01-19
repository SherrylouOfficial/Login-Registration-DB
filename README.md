# Login-Registration-DB

A simple **login and registration web application** demonstrating **front-end and back-end interaction** using **PHP, MySQL, CSS, and JavaScript**.  
This project focuses on understanding how user authentication works through data insertion and retrieval within a **local development environment (XAMPP)**.

---

## Project Overview

This project simulates a basic authentication workflow, allowing users to register and log in using credentials stored in a local MySQL database. The primary objective is to demonstrate how front-end forms interact with server-side logic and how user data is processed, stored, and validated during authentication.

While the interface is intentionally minimal, the project emphasizes **application flow**, **database connectivity**, and **request handling** rather than advanced UI interactivity or animations.

---

## Features
- User registration with database insertion
- User login with credential verification
- Server-side form handling using PHP
- MySQL database integration via XAMPP
- Basic access control logic
- Simple protection against direct access to restricted pages  
  (unauthorized access to `admin_page.php` redirects users to `index.php`)

---

## Technologies Used
- HTML5
- CSS3
- JavaScript
- PHP
- MySQL
- XAMPP (local development environment)

---

## How It Works
- User credentials are submitted through HTML forms
- PHP processes form data and communicates with the MySQL database
- Registered users can log in using stored credentials
- Direct access attempts to restricted pages are checked and redirected
- The project runs locally and is not deployed to production

---

## How to Run the Project (Local Setup)
1. Install and start **XAMPP**
2. Place the project folder inside the `htdocs` directory
3. Import the provided SQL file into **phpMyAdmin**
4. Start Apache and MySQL services
5. Create a Database name 'user_register_db', table name 'users', and lastly column name 'id (auto increment), name, last_name (NULL), email, password, role (enum('student','teacher','parent/guardian','admin'))'
6. Open the project in a browser by typing this:
http://localhost/Login-Registration-DB/index.php
