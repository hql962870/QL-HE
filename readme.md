83921"}
Student Grade Manager

A simple Python-based student grade management system that allows users to add, view, search, and delete student records with weighted scores.

Features

- Add student with scores (EAP, Math, Physics, Programming)
- Automatically calculate weighted total score
- Display all student records
- Search student by name
- Delete student record
- Simple command-line interface

Grading System

Weighted score is calculated as:

Total = EAP × 0.25 + Math × 0.15 + Physics × 0.15 + Programming × 0.15


How to Run

1. Make sure you have Python installed

2. Run the program:

bash python your_file_name.py 

Example Menu

====== Student Grade Manager ====== 1. Add Student 2. Display Students 3. Search Student 4. Delete Student 5. Exit

Data Structure

Student data is stored in a dictionary:

students = {     "Alice": {         "EAP": 85,         "Math": 90,         "Physics": 88,         "Programming": 92,         "Total": 87.5     } }

Future Improvements

- Save data to file (JSON)
- Add score validation (0–100)
- Sort students by total score
- Add update/edit function
- Build GUI version

License

M