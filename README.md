Project on Student Management System 


Project Description: The Student Management System is a simple console-based application written in Java. It allows users to perform basic CRUD (Create, Read, Update, Delete) operations on student records. This system can be particularly useful for educational institutions or any environment where student information needs to be managed.
Features of the Project:
1.	Add Student:
•	Users can add new student records by providing the student's ID, name, and age.
2.	View Students:
•	Users can view the list of all student records. The system displays the ID, name, and age of each student in a formatted manner.
3.	Delete Student:
•	Users can delete a student record by providing the student's ID. The system confirms if the deletion was successful.
4.	Update Student:
•	Users can update the details of an existing student by providing the new ID, name, and age. The system confirms if the update was successful.
5.	Exit:
•	Users can exit the application gracefully.
Code Overview:
1.	Main Class:
•	Runs the application and presents the menu to the user.
•	Handles user input to navigate through different functionalities like adding, viewing, deleting, and updating students.
2.	StudentService Class:
•	Contains methods to add, list, delete, and update student records.
•	Manages an ArrayList of Student objects to store the student data.
3.	Student Class:
•	Represents the student entity with properties: ID, name, and age.
•	Includes getter and setter methods for encapsulating the student's properties.
