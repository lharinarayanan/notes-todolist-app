# Spider-task-2
## Done with PHP Version 7.2.5 and code for accessing and manipulating database has been written in mysql procedural format.
## Task Objective(s) Fulfilled so far 
### Basic Mode
1. Users should be able to sign in and sign up, make sure you read up on encrypting your
passwords and storing them safely for this. Also check for possible ways someone can
use the application without the login and make sure it is not possible to do so. ( Hint:
Look up on cookies and session )
2. Users should be able to create to-do lists and check out items they have completed, and
uncheck them too.
3. Create Notes with a title for each note
### Advanced Task
1. Record time of creation and last edit time of these notes and lists.(time displayed shows the latest editted time and if there is  no edit,it shows the time of creation).
2. Provide sorting features based on time(shown here),level of importance of the note (get as creative
as possible here, think like a user and see what can enhance its usefulness)
//3.Additional feature of user editting his own personal details is added
### General Instructions To run this task
1. Install XAMPP (X- any OS A-Apache M-MySql P-PHP P-Pearl) on your laptop/pc (works on all operating systems).After installation start     the apache and mysql componemts in the xampp control pannel.
2. Extract the above php and html files to the demo folder in the htdocs folder within the xampp folder in your respective localdisk eg.    C:\xampp\htdocs\demo
3.  Create database hari_db in http://localhost/phpmyadmin/index.php by clicking on the new icon on the left of the page.
4.  Within the database create the following tables in XAMPP PHPMYADMIN SQL control pannel within the database.
5.   CREATE TABLE user (
       id INT(9) AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(255),
       email VARCHAR(255),
       telephone bigint(10),
        password VARCHAR(255)
       );
6.   CREATE TABLE notes (
       id INT(9) AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(255),
       title VARCHAR(255),
       time datetime, // # don't provide any default length  
        note VARCHAR(255)
       );

7.   CREATE TABLE todo (
       id INT(9) AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(255),
       todotitle VARCHAR(255),
       tdate datetime, // # don't provide any default length  
       task VARCHAR(255)
       );
8. Place the above link in your browser http://localhost/demo/sp_login.php
 ## Thus the user can signup/login if his account exists and can add edit remove notes and can check in or check out his todo lists which he can add/remove/edit.
 ### P.S
1. Not much of emphasis has been given to styling of the webpage.
2. The apache and mysql component in the XAMPP control pannel need to be started only once but it sholud be done after you log into your    system.   
