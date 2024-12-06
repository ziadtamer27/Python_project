# Employee Management System
## Description
The Employee Management System is a Python-based command-line application that allows users to manage employee records. This system supports various operations like adding, updating, deleting, searching, and listing employees. The employee data is stored in a CSV file for persistence.

## Features:
Add a new employee.
Update existing employee details.
Delete an employee by their ID.
Search for an employee using their ID.
List all employees.

## Table of Contents
1. Usage
2. Methods
4. Validation
5. Example
6. License

## Usage

###  Main Menu: After running the script, you will see the main menu options. You can choose an option by entering the corresponding number:


    --- Employee Management System ---
    1. Add Employee
    2. Update Employee
    3. Delete Employee
    4. Search Employee
    5. List All Employees
    6. Exit
## Methods
    EmployeeManager.add_employee()
 #### - Prompts the user to enter employee details (name, ID, email, position, salary).
 #### - Validates the ID, email, and salary.
 #### - Adds the new employee to the employees.csv file if the ID is unique.
    EmployeeManager.update_employee()
 #### - Prompts the user for an employee ID to update.
 #### - Allows the user to update the name, email, position, or salary.
 #### - Validates input values and updates the employee in the employees.csv file.
    EmployeeManager.delete_employee()
 #### - Prompts the user for an employee ID to delete.
 #### - Deletes the employee record from the employees.csv file.
    EmployeeManager.search_employee()
 #### - Prompts the user for an employee ID to search.
 #### - Displays employee details if the ID is found, otherwise prints an error message.
    EmployeeManager.list_employees()
 #### - Displays a list of all employees in the employees.csv file.

## Validation
  ### The system ensures that the following fields are properly validated before accepting input:

  1. ID: Ensures that the employee ID is a numeric value.
  2. Email: Checks that the email follows a valid format (e.g., user@example.com).
  3. Salary: Ensures that the salary is a positive numeric value.
     
  If any of these validations fail, the user will be prompted to re-enter the information until it's valid.
## Example
### Sample Interaction:
    --- Employee Management System ---
    1. Add Employee
    2. Update Employee
    3. Delete Employee
    4. Search Employee
    5. List All Employees
    6. Exit
    Enter your choice: 1

    --- Add New Employee ---
    Enter Name: Ziad Tamer
    Enter ID: 123
    Enter Email: ziad@gmail.com
    Enter Position: Data scientest
    Enter Salary: 50000
    Employee is added successfully!

    --- Employee Management System ---
    1. Add Employee
    2. Update Employee
    3. Delete Employee
    4. Search Employee
    5. List All Employees
    6. Exit
    Enter your choice: 5

    --- List All Employees ---
    Name: Ziad Tamer, ID: 123, Email: ziad@gmail.com, Position: Data scientest, Salary: 50000

