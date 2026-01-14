# Description
Blog project for the "Web Developer" formation by OpenClassrooms.  
The project consisted of developing a blog and its back office.

## Link
No link  
...

## Setup
Need to import the database (projet4.sql) and configure it :  

-> Go to core/Bdd_connexion.php  

-> Change this :  
private $host = 'localhost';  
private $dbname = 'projet4';  
private $login = 'root';  
private $password = '';

## Commands
No special command to do  
...

## Architecture
The project architecture is based on MVC (model, view, controler)
- core/  
- public/  
- src/
- - controller/
  - model/
  - view/
- .gitignore  
- .htaccess  
- readme.md  
- projet4.sql  
