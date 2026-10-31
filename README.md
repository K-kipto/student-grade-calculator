# Student Grade Calculator

A simple beginner project I built in Python while learning to code.
It asks for a student's name and subjects, takes a mark for each subject,
then shows the total, average and overall grade.

## Features
- Enter any number of subjects
- Checks that marks are valid numbers between 0 and 100
- Calculates total and average
- Gives a letter grade (A to E)

## Grading scale
| Average | Grade |
|---------|-------|
| 80 and above | A |
| 70 - 79 | B |
| 60 - 69 | C |
| 50 - 59 | D |
| Below 50 | E |

## How to run
1. Install [Python 3](https://www.python.org/downloads/)
2. Download `grade_calculator.py`
3. Open a terminal in the same folder and run:

```
python grade_calculator.py
```

## Example
```
Student name: Amina
Enter subjects separated by commas: Maths, Physics, English
Enter marks for Maths (0-100): 78
Enter marks for Physics (0-100): 85
Enter marks for English (0-100): 70

--- Results for Amina ---
Maths: 78.0
Physics: 85.0
English: 70.0
Total: 233.0
Average: 77.7
Grade: B
```

## What I learned
- Using functions, loops and dictionaries in Python
- Handling user input and errors with `try` and `except`

## Ideas for improvement
- Save results to a file
- Handle several students at once
- Build a web version with HTML
