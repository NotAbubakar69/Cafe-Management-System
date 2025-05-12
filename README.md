# Cafe Management System - C++ Project

## Overview

This is a console-based Cafe Management System built in C++ using object-oriented programming principles. The system allows users of different roles (Admin, Staff, Student, Faculty, Non-Faculty) to perform role-specific actions including managing menu items, placing orders, viewing order histories, and handling notifications. It features registration, login authentication, and data storage via file handling.

---

## Features

### User Authentication

* Registration and login functionality.
* Role-based access: Admin, Staff, Student, Faculty, and Non-Faculty.

### Admin Panel

* View Menu
* Add / Remove Menu Items
* Manage Inventory and Discounts
* View Order History, User Data, and Payment Info from files
* Manage Notifications
* Rate Menu Items
* Calculate Monthly Earnings

### Staff Panel

* View Menu
* Process Orders
* Add / Remove Menu Items

### Student / Faculty / Non-Faculty Panel

* View Menu
* Place Orders
* View Order History

### Notifications

* Admins can update and view notifications with timestamp functionality

---

## File Structure


.
├── main.cpp           // Entry point containing the main menu logic
├── project.h          // Class and function declarations
├── *.cpp              // Class implementations (e.g., User, Admin, Staff, etc.)
├── data/              // Directory for saved data files (orders, users, payments, etc.)


---

## Dependencies

* Standard C++ libraries (<iostream>, <fstream>, <string>, <ctime>, etc.)
* Windows-only headers like <conio.h> and system("cls") (make it platform-dependent for portability)

---

## How to Run

1. Open the project in a C++ IDE (e.g., Code::Blocks, Visual Studio) or compile using g++.
2. Make sure all source files (.cpp and .h) are in the same directory.
3. Compile and run the main.cpp file.

---

## Future Enhancements

* Migrate to cross-platform support (replace conio.h and system("cls"))
* Use a database for persistent storage
* Add a GUI using frameworks like Qt or GTK
* Add billing and transaction system

---

## Author

Developed by Muhammad Abubakar Nadeem

---
