# Title: Course Registration System 
Objective:
The objective of this web application is to provide a streamlined and user-friendly platform for students to register for courses offered by their institution. The system should allow students to search for courses, view course details, add courses to their schedule, and view their current course schedule.
Functionality:
1.	Students can create a new account or log in to their existing account.
2.	Once logged in, students can search for courses by course code, course name, or instructor name.
3.	Students can view course details, including the course description, prerequisites, schedule, and available spots.
4.	Students can add courses to their schedule, subject to availability, any applicable prerequisites, and the avoidance of clash with other registered courses. 
5.	Students can view their current course schedule, including the courses they have registered for, their schedule by day and time.
6.	The system should provide notifications and reminders for important deadlines, such as course registration deadlines and drop/add deadlines.
7.	The system should be able to generate reports and analytics on course enrollment, course popularity, and other relevant data.
8.	Display only courses that student has completed their prerequisites.

Architecture:
•	The system should be built using the Model-View-Controller (MVC) architecture pattern.
•	The Model layer will handle the interaction with the database, including storing and retrieving data for users, courses, and schedules in addition to the logic of the application.
•	The View layer will define the HTML templates that render the web pages for the user interface.
•	The Controller layer will handle processing user input, retrieving data from the Model layer, and passing data to the View layer.


Database:
•	The database will include tables for students, courses, courseSchedules, and studentsRegs.
•	Each student will have a unique id, name, email address, and password.
•	Each course will have a unique course code, course name, description, instructor name, schedule, prerequisites, and capacity.
•	Each courseSchedule will have a unique schedule ID, days, startTime, endTime, and roomNo.
•	Each studentsRegs will have unique Id, studentId, coursed
Security:
•	The system should implement proper security measures to prevent unauthorized access and protect user data.
•	Passwords should be encrypted before storing them in the database.
•	User sessions should be managed securely to prevent session hijacking.
•	Access to certain pages and features should be restricted based on user roles (i.e. student or administrator).

Testing:
•	The system should undergo thorough testing to ensure its functionality and usability.

Deployment:
•	The system should be deployed on a secure and reliable web server (Bonus).


Overall, this project aims to provide students with a convenient and efficient way to register for courses and manage their schedules. By leveraging the capabilities of Web2py, it is possible to build a scalable and robust web application that meets the needs of students and institutions alike.
