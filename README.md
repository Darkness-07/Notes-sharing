📚 Overview
The Notes Sharing System is a web-based application designed to facilitate the sharing and management of academic notes among students. It allows users to upload, download, and organize notes efficiently, providing a collaborative platform for academic resources.

🚀 Features
User Authentication: Secure login and registration system.

Admin Dashboard: Manage users and notes.

Note Upload & Download: Share and access notes in various formats.

User Management: Admin can update or delete user accounts.

Responsive Design: Optimized for desktop and mobile views.

🛠️ Technologies Used
Frontend: HTML5, CSS3, Bootstrap

Backend: PHP

Database: MySQL

Server: Apache (via XAMPP)

🧰 Setup Instructions
Prerequisites
XAMPP: Ensure XAMPP is installed and running.

MySQL: Database management through phpMyAdmin.

Installation Steps
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/Darkness-07/Notes-sharing.git
cd Notes-sharing
Set Up the Database:

Access phpMyAdmin via http://localhost/phpmyadmin.

Create a new database named notes_sharing.

Import the provided SQL file to set up the necessary tables.

Configure Database Connection:

Open db.php.

Update the database connection parameters to match your local setup.

Start the Server:

Launch Apache and MySQL through XAMPP.

Navigate to http://localhost/Notes-sharing in your browser.

🔐 Admin Access
Username: admin

Password: admin

Use these credentials to access the admin dashboard for managing users and notes.

📄 File Structure
index.html: Homepage of the application.

login.php: User login page.

register.php: User registration page.

dashboard.php: Admin dashboard for managing content.

upload.php: Page for uploading notes.

delete_note.php: Script to delete notes.

delete_user.php: Script to delete user accounts.

update_user.php: Script to update user information.

db.php: Database connection file.

styles.css: Custom styles for the application.

dashboard.css: Styles specific to the admin dashboard.

📌 Notes
Ensure all files are placed within the htdocs directory of your XAMPP installation.

Regularly back up your database to prevent data loss.

For any issues or contributions, please refer to the Issues section.
