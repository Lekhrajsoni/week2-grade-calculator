Student Grade Calculator
Description

The Student Grade Calculator is a Python program that allows teachers or students to calculate and track student grades easily. It collects marks for multiple subjects, calculates averages, assigns grades and comments, and provides class statistics such as highest, lowest, and average scores.

This project is perfect for beginners learning Python, input validation, loops, functions, and basic data management.

Features

Enter the number of students dynamically.

Input student names and marks for three subjects (Physics, Chemistry, Biology).

Automatic validation of marks (0–100) and student names (non-empty).

Calculates average marks for each student.

Assigns grades and comments based on average:

A: Excellent (95–100)

B: Very Good (85–94)

C: Good (75–84)

D: Passing (65–74)

F: Failed (Below 65)

Displays a summary of all students with averages, grades, and comments.

Provides class statistics:

Class average

Highest average and student

Lowest average and student

How to Use

Run the Python script grade_calculator.py.

Enter the number of students.

Input each student’s name.

Enter marks for Physics, Chemistry, and Biology.

The program will display:

Each student’s average, grade, and comment.

Class statistics.

Example Output
=== STUDENT 1 ===
Student name: Alice
Enter marks (0-100):
Phy: 90
Chem: 85
Bio: 92

Results Summary:
Name                 |  Avg |Grade | Comment
------------------------------------------------------------
Alice                |  89.0 |  B  | Very Good

Class Statistics:
Total Students: 1
Class Average: 89.0
Highest Average: 89.0 (Alice)
Lowest Average: 89.0 (Alice)

Requirements

Python 3.x

No external libraries required

How It Works

The program asks for the number of students.

For each student:

Name and marks are entered.

Average is calculated.

Grade and comment are assigned.

After all students are processed:

A results summary is displayed.

Class statistics are calculated and shown.

Future Enhancements

Support more subjects dynamically.

Save results to a CSV or text file.

Include graphical visualization of class performance.

Add functionality to handle multiple classes.
