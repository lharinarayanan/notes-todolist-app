# spider-task-2
# Done with PHP Version 7.2.5 and code for accessing and manipulating database has been written in mysql procedural format.
Task Objective(s) Fulfilled so far
# Basic Mode
1. Users should be able to sign in and sign up, make sure you read up on encrypting your
passwords and storing them safely for this. Also check for possible ways someone can
use the application without the login and make sure it is not possible to do so. ( Hint:
Look up on cookies and session )
2. Users should be able to create to-do lists and check out items they have completed, and
uncheck them too.
3. Create Notes with a title for each note
# Advanced Task
1. Record time of creation and last edit time of these notes and lists.
2. Provide sorting features based on time(shown here),level of importance of the note (get as creative
as possible here, think like a user and see what can enhance its usefulness)
# GENERAL INSTRUCTIONS To run this task
1. Install XAMPP (X- any OS A-Apache M-MySql P-PHP P-Pearl) on your laptop/pc (works on all operating systems).
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
       time datetime(), // # don't provide any default length  
        note VARCHAR(255)
       );

7.   CREATE TABLE todo (
       id INT(9) AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(255),
       todotitle VARCHAR(255),
       tdate datetime(), // # don't provide any default length  
       task VARCHAR(255)
       );
       
