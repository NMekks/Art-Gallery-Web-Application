# Art-Gallery-Web-Application
This web-based art gallery management system was done as a group project which uses CRUD operations. The web technologies used in this project included PHP, HTML, CSS, and JavaScript. MySQL database was used as a DBMS.

## Features
- User login, create new user, and log out
- Forgot password, create new password, and one-time-pin authentication via email
- Artist, Guest, and Employee Tables to view information of all artists, guests and employees, respectively.
- CRUD (create, read, update, delete) functions for all tables and entries.
- Search functionality for all tables.

## Project
 - `DBInitialisation` -- contains all the database and tables initialization and configuration files.
 - `authentication` -- contains the login, forgot password, updating password, verification and landing page files.
 - `CRUD` -- contains all the CRUD operation files related to the artist, guest, and employee tables.

## How To Use
This section will provide the user with details to get started with the web application and use it.

### Thigs to install before running the web application
- WAMPserver
- MySQL

### Installation

1. Download the ZIP file and extract it.
2. If using WAMP place the folder in the `www` directory.
3. Start MySQL services.

### Database Setup

There are 2 ways of making this

#### First way 
1. Start up WampServer and create a database and in MySQL by providing the proper URL in the browser’s address bar (http://localhost/ArtGallery/DBInitialisation/createDB.php).
2. Establish the rest of the tables (e.g. createArtistTable, createEmployeeTable, and createGuestTable), then add the corresponding data. 

#### Second way (The preferred way)
1. Navigate to your phpMyAdmin panel by clicking on WampServer Icon>PhpMyAdmin>PhpMyAdmin and create a database `art_gallery`.
2. Import the `art_gallery.sql` database by navigating to art_gallery database>Import>Choose File...>Import.. (This process will import all of the tables and their information)

###To Run The Project

- **Login Page**: Enter the pre-provided email and password (Email: artgallery23@outlook.com , Password: artgalleryPass) Note that you will have to delete these from the code otherwise other people will be able to log in to your project!!
- **Landing page**: Navigate to the artist table, guest table, or employee table. Note that the employee table will only be accessible to employees who have a "Manager" role appointed to them during their registry.
- **Tables**: Perform operations such as adding, viewing, editing, and deleting entires of artists, guests and employees. You can also search for entires from each table.

### Authors
-Abdulmohaimin Bashir - *Develeopment*
-Muhammad Bilal - *Developement*
-Nusaibah Mekkaoui - *Developement*




