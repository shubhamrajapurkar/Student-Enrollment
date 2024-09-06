##Student Enrollment Form
#Description
This project is a Student Enrollment Form that stores student data in the STUDENT-TABLE relation of the SCHOOL-DB database using JsonPowerDB. The form allows users to save, update, and reset student details such as Roll Number, Full Name, Class, Birth Date, Address, and Enrollment Date. The form implements CRUD operations and ensures data validation, preventing empty fields.

#Benefits of Using JsonPowerDB
Schema-free: Provides flexibility in data structure.
Serverless: Eliminates the need for server setup and configuration.
High Performance: Fast data storage and retrieval, thanks to its in-memory caching and indexing.
Low Development Time: Reduces the complexity of database handling.
Real-time Analytics: Built-in real-time analytics capability.
Easy Integration: Simple REST API makes it easy to integrate with the application.


#Table of Contents
Description
Benefits of Using JsonPowerDB
Release History
Scope of Functionalities
Examples of Use
Project Status
Sources
Scope of Functionalities
Save: Insert student data into the database.
Update: Modify existing student data in the database.
Reset: Clear the form fields for new data entry.
Validation: Ensure that no fields are empty, especially the primary key (Roll No).
#Examples of Use
A user enters a new student's Roll Number, Name, Class, Birth Date, Address, and Enrollment Date. If the Roll Number doesn’t exist, the form allows the user to save the data.
If the Roll Number already exists, the form fetches the data and enables the user to update it.
#Project Status
The project is currently in its initial release, with core features fully implemented.

#Sources
JsonPowerDB Documentation: Login2Xplore
