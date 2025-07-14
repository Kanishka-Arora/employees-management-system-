# employees-management-system-
Purpose of the Program: This program is designed to manage employee records such as ID, Position, Date of Joining, and Salary using arrays. It provides a menu-driven interface that allows the user to:  Add a new employee  Delete an existing employee by ID  Update employee details by ID  Display all employee records  Exit the program
# 👥 Employee Management System in C++

## 📌 Overview
This is a **C++ console-based application** that allows basic **employee record management** using **arrays**. Users can **add**, **delete**, **update**, and **display** employee records via a **menu-driven interface**.

---

## 🧾 Features
- Add new employee records (ID, Position, Date of Joining, Salary)
- Delete an employee by ID
- Update existing employee details
- View the list of all employees
- Exit option to terminate the program
- Stores data for up to 100 employees

---

## 📋 Data Structure Used
The program uses the following arrays:
- `int id[100]` → to store employee IDs
- `char position[100][30]` → to store job positions
- `char doj[100][30]` → to store date of joining
- `float salary[100]` → to store employee salary
- `int count` → to keep track of the total number of employees

---

## 🧠 How It Works

1. **Start the Program**
   - Displays a menu with options to manage employee records.

2. **Add Employee**
   - Prompts the user to input ID, Position, Date of Joining, and Salary.
   - Adds data to the arrays and increments the count.

3. **Delete Employee**
   - Asks for the employee ID.
   - Searches for the ID and removes the record by shifting elements.

4. **Update Employee**
   - Prompts for the ID and updates Position, DOJ, and Salary if found.

5. **Display Employees**
   - Shows all current employee records in a formatted list.

6. **Exit**
   - Ends the loop and exits the program.

---

## 💻 Sample Output
------ Employee Management System ------

Add Employee

Delete Employee

Update Employee

Display All Employees

Exit
Enter your choice: 1

Enter ID: 101
Enter Position: Manager
Enter Date of Joining: 01-01-2022
Enter Salary: 50000
Employee added.
