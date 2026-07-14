Digital Library System

A web-based library management system that digitizes core library operations — issuing books, tracking returns, and managing users — instead of relying on manual registers.

What it does


Book catalog management (add/view/search books)
Book issue and return workflow, with tracking of who has which book and when it's due
User management (student/member records)
Backend data persistence using MySQL


Tech stack


Language: PHP
Database: MySQL
Local server environment: XAMPP
Frontend: HTML, CSS based


Key features


CRUD operations for books and users
Issue/return workflow with status tracking
Basic user authentication for library staff/members


How to run

bash# Clone the repo
git clone https://github.com/Magneto-04/Digital-Library.git

#Move into your XAMPP htdocs folder
#e.g. C:\xampp\htdocs\Digital-Library (Windows)
#or /Applications/XAMPP/htdocs/Digital-Library (Mac)

#Start XAMPP (Apache + MySQL)

#Set up the database
#1. Open phpMyAdmin
#2. Create a database (e.g. `digital_library`)
#3. Import the schema

#Visit in browser
http://localhost/Digital-Library
