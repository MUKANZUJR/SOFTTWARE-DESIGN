# Student Management System

## Overview
This Student Management System allows educational institutions to manage student data, including adding, updating, deleting, and viewing student information.

## Features
- Add new students
- Update existing student information
- Delete students
- View all students

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/yourusername/student-management-system.git
    ```
2. Navigate to the project directory:
    ```
    cd student-management-system
    ```
3. Run the system:
    ```
    python main.py
    ```

## Code Structure
- `student.py`: Contains the `Student` class, which represents the student entity.
- `student_service.py`: Contains the `StudentService` class, which handles the business logic for managing students.
- `student_database.py`: Contains the `StudentDatabase` class, which mimics database operations for storing students.
- `main.py`: Contains the `MenuSystem` class, which provides a simple menu for interacting with the system.

## Changes Made
- Refactored code to follow SOLID principles.
- Removed redundant code (DRY).
- Simplified the design (KISS).
- Implemented a user-friendly menu system.

