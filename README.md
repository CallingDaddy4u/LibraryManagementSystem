# LibraryManagementSystem
**Overview**

This project is a Library Management System (LMS) developed using Python, Tkinter, and SQLite. The application provides a graphical user interface where students can log in using their student ID and manage library activities such as issuing and returning books.

The system stores issued book records in a SQLite database, allowing users to track borrowed books and manage library inventory efficiently. This project demonstrates the use of GUI development, database management, and input validation in Python.

**Features**

Student login with ID format validation

GUI built using Tkinter

Book issuing system

Book return functionality

Real-time book stock tracking

Student information input (name, email, phone)

Email and phone validation

SQLite database for storing issued books

Scrollable list of currently borrowed books

Logout and session handling

Dynamic UI with styled buttons and dropdowns

**Technologies Used**

Python

Tkinter (GUI Framework)

SQLite3 (Database)

Pillow (PIL) for background image handling

Regular Expressions (re) for input validation

**Project Structure**

Library-Management-System/
│
├── login.py          # Login page interface
├── lmsPage.py        # Main LMS interface
├── database.py       # Database operations
├── books.py          # Static book dataset
├── background.jpg    # Login page background
└── lms.db            # SQLite database (auto-created)

**How to Run the Project**

Install Python (3.8 or higher recommended)

Install required package:

pip install pillow

Run the login page:

python login.py

Enter a student ID in this format:

2025F-BDS-017
or
2025S-BDS-025
System Workflow

Student logs in using a valid Student ID.

The LMS dashboard opens.

Student enters their:

Name

Email

Phone number

Student selects a book from the dropdown list.

Book is issued and stored in the SQLite database.

Borrowed books appear in the Currently Borrowed list.

Books can be returned using the Return Selected button.

Learning Outcomes

This project helped demonstrate:

Python GUI development

Database integration

Input validation using regular expressions

Modular programming with multiple files

Real-world application design

**Author**

Taha Shaikh
BS Data Science – Sir Syed University
