# ProjectMngtSystemwithDatabase
Description
===========
This project speaks to Project Management for a small structural firm to keep track of 
the many projects they work on by storing all the information on the Database..  

How it works
============
For each project the following information is required:
1. Project number.
2. Project name.
3. Building Type - e.g House, Store, Apartment etc...
4. Physical address of the project.
5. ERF number.
6. Total fee charged for the project.
7. Total amount paid to date.
8. Deadline for the project.
9. The name, telephone number, email address and physical address of the architect for the project.
10. The name, telephone number, email address and physical address of the Structural engineer for the project.
11. The name, telephone number, email address and physical address of the customer for the project.
12. The name, telephone number, email address and physical address of the Project manager for the project.
	
Classes are used to run this project. The Project class and Person class stores data which 
is required for the project to execute. The Main class, is responsible for the execution.
Within the main class, there are two methods named getProject() and getPerson().
These two methods are of class Project and Person.
The getProject() using the Scanner class allows a user to capture data required to for a project.
Within the getProject(), the Person class objects are also created, which are: architect, engineer, customer
and project manager. 
The Project class object is created when the getProject() is invoked.
The project uses a menu that gives the user options on what they would like to do. They are given an option of:
1. Adding a project.
2. Update Customer.
3. Update Project Manager.
4. Update Architect.
5. Update Structural Enginner.
6. Finalise a Project.
7. Incomplete Projects.
8. Projects that are past due date.
9. Find a Project.
10. Exit.

It allows to update the project,due date, update the amount paid to date, update Structural engineer's contact details, and updating the Architect's contact details.
The program allows for the finalization of the project by generating an invoice for the customer that calculates the amount that the customer still owes.
That amount is calculated by subtracting the total amount paid to date from the total fee for the project.
The program also allows one to get all projects that are incomplete and past the due date.
All this information is gathered from the database storing the data. We are using a MySQL database, and a function
is created to connect to the database.
