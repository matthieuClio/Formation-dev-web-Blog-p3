# Blog PHP – Web application with back office

## Project context
This project was developed as part of the **Web Developer** training program by OpenClassrooms.  
The goal was to build a dynamic blog application from scratch using PHP and MySQL, including both a public-facing interface and an administrative back-office.

The project simulates a real-world use case where a content creator needs to manage articles and comments through a secured administration panel.

## Educational objectives
- Develop a dynamic web application using PHP
- Interact with a relational database (MySQL)
- Implement CRUD operations
- Structure an application using the MVC architectural pattern
- Separate business logic, data access, and presentation layers
- Build an administration interface (back-office)

## Technologies used
- PHP (Object-Oriented Programming)
- MySQL
- HTML5 / CSS3
- MVC architecture
- Git / GitHub

## Features

### Public side
- Display blog posts
- View individual articles
- Display associated comments

### Admin / Back-office
- Create, update, and delete blog posts
- Moderate comments
- Access to administrative features via a dedicated interface

## Demo
No online demo available.  
The project runs locally using a PHP server and a MySQL database.

## Installation and setup

### Prerequisites
- Local server environment (XAMPP, MAMP, WAMP, or equivalent)
- PHP
- MySQL

### Setup steps

1. Clone the repository:
```bash
git clone https://github.com/matthieuClio/Blog-PHP.git
```

Import the database:  
Import the projet4.sql file into your MySQL server

Configure database connection:  
Open core/Bdd_connexion.php

Update the following credentials according to your local setup:  
```php
private $host = 'localhost';
private $dbname = 'projet4';
private $login = 'root';
private $password = '';
```

## Architecture
.  
├── core/  
│   └── Bdd_connexion.php  
├── public/  
├── src/  
│   ├── controller/  
│   ├── model/  
│   └── view/  
├── .gitignore  
├── .htaccess  
├── README.md  
└── projet4.sql  
