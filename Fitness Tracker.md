🏋️‍♂️ C++ Fitness Tracker

A console-based fitness tracker built in C++ to log workouts, track daily steps, calories, BMI, and generate reports.

🚀 Overview

This project is a fully interactive C++ fitness tracker that allows users to:

Log daily workouts, steps, and calories

Calculate covered distance and calories burned automatically

Compute BMI (Body Mass Index) and provide health insights

Set daily goals for steps and calories

Edit or delete existing records

Generate a comprehensive report summarizing activity

The project is designed to simulate a simple personal fitness app in a console environment, demonstrating data handling, user input validation, and structured output in C++.

💡 Features

Add New Record – Input user details, workout type, weight, height, steps, and calories

View Records – Display all logged entries with calculated distance and burned calories

Edit/Delete Records – Easily update or remove any record by ID

BMI Calculation – Automatically calculates BMI and provides health feedback

Daily Goals – Set daily calorie and steps targets and track progress

Generate Report – Summarizes all user data in a neat table format

⚡ How It Works

User selects an option from the main menu.

The program collects input like ID, gender, date, time, weight, height, steps, and calories.

Distance (km) and calories burned (b_cal) are calculated automatically.

BMI is calculated from weight and height, with a health status displayed.

Users can view, edit, delete, or generate reports for all records.

Daily goals are compared against actual performance for progress tracking.

🖥 Demo Screenshot
***********************************
**WELCOME TO FITNESS TRACKER**
***********************************

Select an option:
N: Enter new record
V: View the records
E: Edit existing record
D: Delete a record
G: View daily goals
R: Generate report
Q: Quit


📌 Technical Details

Language: C++

Platform: Windows Console (uses <iostream>, <string>, sleep(), and system() commands)

Data Structure: Structs for Tracker and DailyGoals

Stores up to 50 records in memory

Simple interactive menu-driven interface
