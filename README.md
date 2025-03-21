hi

# Online Course Registration Portal

## Introduction

Welcome to the Online Course Registration System! This web-based platform simplifies course registration for educational institutions, corporate training programs, and online learning environments. Students can enroll in courses by providing the required details, while administrators oversee the registration process and manage system functionalities.

## Project Requirements

- Language Used: PHP 8.2.12
- Database: MySQL
- User Interface Design: HTML, CSS, AJAX, jQuery, JavaScript
- Software: XAMPP/Wamp/Mamp/Lamp (anyone)

## Modules or Use Cases

### Admin

Registers students and assigns them a username, password, and unique pin code.
The pin code is required for students to enroll in courses.
Manages sessions, semesters, departments, courses, students, and student logs.
Publishes announcements for students.

  #### _Login Details for Admin_
  - Username: admin
  - Password: Test@123

![image](https://github.com/Course_Registration_Portal/assets/93445041/3ef87444-e8f1-4887-9b1f-b54c452bf332)
![image](https://github.com/Course_Registration_Portal/assets/93445041/07905ff8-71b6-4201-82a3-fe9a7982c17d)
![image](https://github.com/Course_Registration_Portal/assets/93445041/ecf2154c-cfab-4eb4-98c3-c6597f2b36dd)


### Student

Logs in using registration number and password provided by the admin.
Enrolls in available courses.
Prints a summary of registered courses.

  #### _Login Details for Student_
  - Reg No.: 10806121
  - Password: 123456
  - Student Pincode for Course Enrollment (Student): 390022



## Installation Steps

- Download the zip file and unzip the project file on your local system.
- Cut the 'sql_file' folder, and paste it into some other directory, you will need the '.sql' file located in it.
- Copy the "Course_Registration_Portal" folder and place it inside the root directory of your server. (E.g. : C:\xampp\htdocs\Course_Registration_Portal)

## Database Configuration Steps:
- Open PHPMyAdmin.
- Create a new database named "onlinecourse"
- Import the database schema from the "onlinecourse.sql" file provided in the "sql_file" folder that you saved in some other directory earlier.

## Accesing the Portal on Browser:
- Open your browser and enter the following URL: 'http://localhost/Course_Registration_Portal'
