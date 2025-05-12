🚗 Automobile Selling Application
A simple web-based platform designed to facilitate the buying and selling of automobiles. This application allows users to view available vehicles and get in touch with sellers through a contact form.

📌 Features
Homepage: Displays available automobiles with images and brief descriptions.

Contact Form: Enables potential buyers to send inquiries to sellers.

Database Connectivity: Stores contact form submissions in a MySQL database.

Responsive Design: Ensures compatibility across various devices.

🛠️ Technologies Used
Frontend:

HTML

CSS

JavaScript

Backend:

PHP

Database:

MySQL

📁 Project Structure
pgsql
Copy
Edit
Automobile-Selling-Application/
├── index.html
├── getintouch.php
├── connect.php
├── css/
│   └── styles.css
├── js/
│   └── scripts.js
├── images/
│   └── [car images]
└── README.md

index.html: Main landing page displaying available cars.

getintouch.php: Handles form submissions from the contact page.

connect.php: Establishes a connection to the MySQL database.

css/styles.css: Contains styling rules for the application.

js/scripts.js: Includes interactive functionalities.

images/: Directory for storing automobile images.

🚀 Getting Started
Prerequisites
A web server with PHP support (e.g., XAMPP, WAMP, or LAMP).

MySQL database server.

Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/ankit29-root/Automobile-Selling-Application.git
Set Up the Database:

Create a new MySQL database (e.g., automobile_db).

Import the provided SQL file (if available) to set up necessary tables.

Configure Database Connection:

Open connect.php.

Update the following variables with your database credentials:

php
Copy
Edit
$servername = "localhost";
$username = "your_username";
$password = "your_password";
$dbname = "automobile_db";
Deploy the Application:

Place the project folder in your web server's root directory (e.g., htdocs for XAMPP).

Start the web server and navigate to http://localhost/Automobile-Selling-Application/index.html in your browser.

📝 Usage
Browse the homepage to view available automobiles.

Use the contact form to send inquiries about specific vehicles.

Submitted forms are stored in the MySQL database for seller reference.

📬 Contact
For any queries or feedback, please reach out to ankit29-root.
