# PRODIGY_CS_03

# 🔑 Password Complexity Checker
Internship Task_03 at Prodigy InfoTech

## 📜 Overview
This program implements a password complexity checker tool using Python and Tkinter for the graphical user interface. 
The tool evaluates the strength of a given password based on several criteria and provides feedback to the user.

## 📚 Theoretical Explanation

### 🔐 Password Strength
Password strength is a measure of the effectiveness of a password in resisting guessing and brute-force attacks. 
The strength of a password depends on various factors such as its length, the use of different character
types (uppercase, lowercase, digits, and special characters), and unpredictability.

### 🛡️ Cybersecurity Concepts
- **Password Security:** Ensuring that passwords are strong enough to protect user accounts from unauthorized access.
- **Criteria for Strong Passwords:**
  - Length: Should be at least 8 characters.
  - Uppercase Letters: Including at least one uppercase letter.
  - Lowercase Letters: Including at least one lowercase letter.
  - Digits: Including at least one digit.
  - Special Characters: Including at least one special character.

## 📝 Prerequisites
- Basic understanding of Python programming.
- Familiarity with GUI development using Tkinter.
- Knowledge of regular expressions.

## 💻 Software Requirements
- Python 3.x

## 🖥️ Hardware Requirements
- A computer with at least 2GB of RAM.
- Any operating system that supports Python 3.x.

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries:** Tkinter, re

## 🚀 How to Execute the Program

1. **Clone the Repository:**
   ```bash
   git clone <repository-directory> (https://github.com/trupti-K-ghenand/PRODIGY_CS_03)
   cd <repository-directory>
   ```

2. **Run the Program:**
   ```bash
   python task3_password_complexity_checker.ipynb
   ```

3. **Usage Instructions:**
   - Enter your password in the input field.
   - Click on "Check Strength" to assess the password's strength.
   - A message box will display the strength of your password and provide suggestions for improvement.

## 📄 Code Details Overview

### `task3_password_complexity_checker.ipynb`

#### Imports
```python
import tkinter as tk
from tkinter import messagebox
import re
```
- `tkinter`: For creating the GUI application.
- `re`: For using regular expressions to check password criteria.

#### Functions
- `assess_password_strength(password)`: Evaluates the strength of the password based on length, presence of uppercase and lowercase letters, digits, and special characters. Returns feedback and suggestions.
- `check_password_strength()`: Retrieves the password from the input field, calls `assess_password_strength`, and displays the results in a message box.

#### GUI Setup
- **Main Window**: The root window is set up with a title and dimensions.
- **Label**: Prompts the user to enter a password.
- **Entry Field**: Allows the user to input their password.
- **Button**: Triggers the password strength assessment.

## Thanks👏
Thank you for using and contributing to this repository! I sincerely appreciate your interest and hope you find the Caesar Cipher programs helpful for your cryptography learning journey.

## Contribute🤝
Welcome all contributions to enhance these programs and expand their capabilities.

To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push them to your branch.
4. Open a pull request describing your changes.

✅Please ensure your code adheres to the existing style and includes appropriate documentation and tests.


## 🛡️Secure coding!🛡️
