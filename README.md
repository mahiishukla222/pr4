# pr4

watch video--


# OOP Wrapper - Employee Management System

## Project Description

The Employee Management System is a Python-based project developed using Object-Oriented Programming (OOP) concepts.

This project manages different types of people, employees, managers, and developers. It allows users to create records and display employee details through a menu-driven interface.

## Objective

The main objective of this project is to understand and implement Python OOP concepts such as classes, objects, inheritance, encapsulation, constructors, method overriding, and polymorphism.

## Features

* Create a Person
* Create an Employee
* Create a Manager
* Create a Developer
* Display Person Details
* Display Employee Details
* Display Manager Details
* Display Developer Details
* Check Inheritance using issubclass()
* Menu-driven interface
* Exit option

## Technologies Used

* Programming Language: Python
* Concepts: Object-Oriented Programming
* Platform: Python IDLE / VS Code
* Version Control: GitHub

## OOP Concepts Implemented

### 1. Class and Object

Classes are used to define Person, Employee, Manager, and Developer. Objects are created to store individual details.

### 2. Constructor

The `__init__()` method initializes object attributes.

### 3. Inheritance

Employee inherits from Person. Manager and Developer inherit from Employee.

### 4. Encapsulation

Private attributes such as `__employee_id` and `__salary` are used to protect sensitive employee information.

### 5. Getter and Setter Methods

Getter and setter methods are used to access and update private attributes.

### 6. Method Overriding

Manager and Developer classes override the display() method to show their specific information.

### 7. super() Method

The super() function is used to call parent class constructors and methods.

### 8. issubclass()

The issubclass() function checks whether Manager and Developer are subclasses of Employee.

### 9. Destructor

The `__del__()` method is defined in the Employee class.

## Project Structure

```text
OOP-Wrapper/
│
├── employee_management.py
│
└── README.md
```

## How to Run the Project

1. Install Python on your computer.
2. Download or clone this repository.
3. Open the project folder in VS Code or Python IDLE.
4. Open `employee_management.py`.
5. Run the Python program.
6. Select an option from the menu.
7. Enter the required details.

## Example Operations

```text
--- Python OOP Project: Employee Management System ---

Choose an operation:

1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Exit

Enter your choice:
```

## Sample Input

```text
Enter your choice: 2

Enter Name: Jane Smith
Enter Age: 28
Enter Employee ID: E123
Enter Salary: 50000
```

## Sample Output

```text
Employee created successfully!
```

## Conclusion

This project demonstrates the practical implementation of Object-Oriented Programming concepts in Python.

It helps in understanding inheritance, encapsulation, constructors, method overriding, and object management through a simple Employee Management System.

## Author

**Mahi Shukla**

BCA Student
