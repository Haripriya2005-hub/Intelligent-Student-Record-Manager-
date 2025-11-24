# Intelligent-Student-Record-Manager-
Intelligent Student Record Manager is a Java console app with MySQL integration that performs CRUD operations on student data. It allows adding, viewing, updating, and deleting student records for easy academic record management.

# Features
* Add new students with details like name, college, city, percentage

* Display all student records

* Search students by roll number

* Update student information

* Delete student records

# Installation and Setup
* Create MySQL database and table using database.sql script or:

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# sql:
CREATE DATABASE student_db;
USE student_db;

CREATE TABLE student_details (
    rollnum INT PRIMARY KEY AUTO_INCREMENT,
    sname VARCHAR(100) NOT NULL,
    clgname VARCHAR(10),
    city VARCHAR(50),
    percentage DOUBLE(5,2)
);

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Clone the repo and open in your Java IDE (e.g., IntelliJ).

* Configure database details in DBConnection.java.

* Add MySQL Connector/J to project dependencies.

Run Client.java to start the app.
