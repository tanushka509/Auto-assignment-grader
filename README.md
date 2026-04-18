📘*** Assignment AutoGrader**

A lightweight and configurable automatic grading system for programming assignments. The system evaluates student submissions against predefined test cases and generates structured results, reducing manual grading effort.

🚀Features
Automated evaluation using input/output test cases

Supports multiple programming languages (based on runtime availability)

Generates per-student grading results and summaries

Simple CLI-based workflow with configurable setup

Easily extendable for additional features


🛠️ Tech Stack
Python (core grading logic)
File-based test case and submission handling
⚙️ How It Works
Place student submissions in the submissions/ directory
Add test cases (input/output files) in the tests/ folder
Configure grading rules if required
Run the autograder script
View generated results for each submission


▶️ Usage
python autograder.py
📂 Project Structure
Assignment-AutoGrader/
│── submissions/        # Student code files
│── tests/              # Input/output test cases
│── results/            # Generated grading results
│── autograder.py       # Main grading script
📌 Note

This project is based on an open-source implementation and has been adapted for learning and extension purposes.
