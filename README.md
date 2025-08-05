# Student Grade Calculator & Classroom Insights

A simple, command-line Python application to calculate student marks, assign grades, and provide a summary of class performance. This project is designed for beginners to practice fundamental Python concepts.

## 📝 Description

This tool automates the process of evaluating student performance. It takes student names and their marks in three subjects as input and generates a comprehensive summary that includes:

* Total and average marks for each student.
* A letter grade based on the average score.
* The overall class average.
* The name of the top-performing student.

## ✨ Features

* **Interactive Data Entry**: Prompts the user to enter student names and marks one by one.
* **Automated Calculations**: Automatically computes totals, averages, and grades.
* **Clear Summary Reports**: Displays a clean, easy-to-read summary for each student and the class as a whole.
* **Class Topper Identification**: Highlights the highest-scoring student to celebrate achievement. 🏆
* **Simple & Lightweight**: Built with standard Python libraries, no external dependencies needed.

## 🚀 How to Use

To run this project, you need to have Python installed on your system.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/student-grade-calculator.git](https://github.com/your-username/student-grade-calculator.git)
    cd student-grade-calculator
    ```

2.  **Run the script from your terminal:**
    ```bash
    python grade_calculator.py
    ```

3.  **Follow the on-screen prompts:**
    * Enter each student's name and their marks for the three subjects.
    * When you have entered all students, type `done` at the name prompt to finish.

4.  **View the results:**
    * The script will print a detailed summary for each student and the overall class statistics.

## 🛠️ Code Overview

The script is organized into three main functions:

* `get_student_data()`: Handles the user input for student names and marks.
* `calculate_grades()`: Processes the raw data to compute the total, average, and grade for each student.
* `print_summary()`: Formats and displays the final report, including individual summaries and class-wide insights.

## 示例 (Example Usage)

Here is a sample of what the interaction looks like:
