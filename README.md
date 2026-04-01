# Student Record Manager

A beginner-friendly Python project to manage student records using lists, dictionaries, functions, JSON file handling, and a menu-driven program.

## What this project does

This project allows you to manage student data from the terminal.  
You can:

- view all students
- search for a student
- add a new student
- update student marks
- delete a student
- store data in a JSON file
- load saved data when the program starts

## Features

- Menu-driven Python program
- Student data stored as dictionaries inside a list
- Search student by name
- Add new student
- Update marks of an existing student
- Delete a student record
- View total marks and average marks
- Find topper and highest average
- Case-insensitive name checking
- Exception handling for invalid mark input
- Data persistence using `students.json`
- Code split into multiple files:
  - `main.py`
  - `student_manager.py`

## Project Structure

```bash
student_record_manager/
│
├── main.py
├── student_manager.py
└── students.json
