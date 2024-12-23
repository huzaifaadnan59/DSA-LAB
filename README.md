# Lab Tasks: Palindrome Checker and Parentheses Balancer

## Overview
This repository contains two Python scripts: `labtask1.py` and `labtask2.py`. These scripts were developed as part of programming lab tasks to practice fundamental programming concepts such as string manipulation, stack operations, and control flow. Below are the details of each script.

---

## Lab Task 1: Palindrome Checker (`labtask1.py`)
### Description
This script checks whether a given string is a palindrome. A palindrome is a word, phrase, or sequence that reads the same backward as forward (e.g., "madam", "racecar").

### Features
- Reverses the input string using slicing.
- Uses a stack to demonstrate how letters can be pushed and popped.
- Compares the original string with its reverse to determine if it is a palindrome.

### How to Run
1. Clone the repository or download the `labtask1.py` file.
2. Run the script in a Python environment:
   ```bash
   python labtask1.py
   ```
3. Enter a string when prompted.
4. The script will display whether the input is a palindrome or not.

### Sample Output
```
Enter text: madam
['m', 'a', 'd', 'a', 'm']
Palindrome
```

---

## Lab Task 2: Parentheses Balancer (`labtask2.py`)
### Description
This script checks if a given equation or string has balanced parentheses. It supports the following types of brackets:
- Round brackets: `()`
- Curly brackets: `{}`
- Square brackets: `[]`

### Features
- Uses a stack to validate the balance of brackets.
- Supports nested and mixed types of brackets.
- Returns "Balanced" if the brackets are properly closed and nested, otherwise "Unbalanced".

### How to Run
1. Clone the repository or download the `labtask2.py` file.
2. Run the script in a Python environment:
   ```bash
   python labtask2.py
   ```
3. Enter an equation or string with brackets when prompted.
4. The script will display whether the input is balanced or not.

### Sample Output
```
Enter equation: {[()()]}
The eq '{[()()]}' is Balanced
```

---

## Requirements
- Python 3.6 or higher

## Repository Structure
```
.
├── labtask1.py  # Palindrome Checker
├── labtask2.py  # Parentheses Balancer
└── README.md    # Project Documentation
```
