# Apex-Task2

This is a simple blog application built with PHP and MySQL, designed to run on XAMPP. It allows users to:

✔ Register and log in
✔ Create, edit, and delete blog posts
✔ View all posts in a table format

The application automatically creates the required database and tables if they do not already exist.

🛠 Technologies Used

PHP (with mysqli extension)

MySQL (via XAMPP’s MySQL server)

HTML forms for user interaction

Bootstrap (optional) for styling (not included but can be added)

✅ Features

User Authentication

Register with a username and password

Passwords are securely hashed

Login functionality with session handling

Logout option

Blog Management

Create new posts with a title and content

Edit and update existing posts

Delete posts

Display all posts in reverse chronological order

Database Auto Setup

Creates blog database if missing

Creates users and posts tables if missing

🚀 Setup Instructions
Step 1 – Install XAMPP

Download and install XAMPP from https://www.apachefriends.org/
.

Start Apache and MySQL from the XAMPP Control Panel.

Step 2 – Enable PHP extensions

Open php.ini by clicking Config → PHP (php.ini) in the XAMPP Control Panel.

Uncomment the following lines by removing the semicolon (;):

extension=mysqli
extension=pdo_mysql


Save the file and restart Apache.

Step 3 – Place the PHP file

Save the provided blog.php file in the folder:
C:\xampp\htdocs\

Access it in your browser by visiting:
http://localhost/blog.php

Step 4 – Register and use the blog

Click Register here to create a new user account.

Fill in your username and password and register.

After registration, log in.

Create, edit, or delete posts as needed.

Outputs:
![WhatsApp Image 2025-09-07 at 12 52 56_45a51025](https://github.com/user-attachments/assets/7bc94240-ce17-4c56-a4b7-deeaa6c91725)

<img width="1918" height="969" alt="Screenshot 2025-09-07 125120" src="https://github.com/user-attachments/assets/9c6c3ab3-ecc8-429a-b064-8c095d6f0a1d" />

<img width="1909" height="978" alt="Screenshot 2025-09-07 125101" src="https://github.com/user-attachments/assets/5f83736d-8189-4cee-bf48-5aed247c0945" />


