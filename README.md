# Symon Practical Exam

## Story
An Client from Fremantle Australia wants to have a web application that manages employees and project assignments.

Client wants to do create, update and deactivate employee.

Client also wants to have role for user login and only admin role can update and deactivate a record.

But the client wants to prioritize the core feature of the web application.


## Requirements:
	Login/Logout Feature
	Role Authorization
	Employee Management (Crud Operations)
	Project Management (Crud Operations)

## Core feature
### Employee Management Page:
- Display list of employees
- Can create new employee and assign project
- Can update employee and project assignment (Admin only)
- Can deactivate Employee (Admin only)

### Project Management Page:
- Display list of projects
- Can create Project
- Can update Project
- Can deactivate Project
- Can View Project Detail with list employee working on it



## Instructions: 
This web app is .NET Core 3.1. You can use any CSS style framework but prefer to use bootstrap.
You can create with WebAPI and any frontend frameworks like Angular/React or Plain MVC.

- Clone this project and work in your local environment
- Create a feature branch with a name 'feature/Fremantle-AU
- Once you're done, create a Pull Request to Main
- You can use any database but I suggests that you use MSSQL.

### Employee table:
	FirstName
	LastName
	EmailAddress
	ContactNo
	PresentAddress
	JobTitle

### Project table:
	ProjectId
	ProjectTitle
	ProjectDescription

#### Hint: You might need another table for this
