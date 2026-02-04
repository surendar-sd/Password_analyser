# 🔐 Password Analyzer

Password Analyzer is a simple Python project that checks how strong a password is and helps users understand whether their password is secure or not.  
It analyzes the password based on length, character complexity, entropy, and whether it appears in a list of commonly used passwords.

This project was built as part of learning **cybersecurity basics and secure coding practices**.

---

## 📌 Why this project?

Weak passwords are one of the most common reasons for security breaches.  
Many users still use short or predictable passwords like `123456` or `password`.

The goal of this project is to:
- Make users aware of password security
- Detect weak and common passwords
- Suggest improvements for better security

---

## 🎯 What this project does

- Checks password length
- Verifies use of uppercase, lowercase, numbers, and symbols
- Detects commonly used passwords
- Calculates password entropy (randomness)
- Classifies passwords as **Weak**, **Medium**, or **Strong**
- Gives simple suggestions to improve weak passwords

---

## 🚀 Features

- Easy-to-use command line interface
- Clear password strength classification
- Entropy-based strength analysis
- Common password blacklist check
- Lightweight and fast execution
- Beginner-friendly Python code

---

## 🛠️ Technologies Used

- Python 3
- Regular Expressions (re module)
- Math module
- Command Line Interface (CLI)

---

## 📂 Project Structure
└── password_analyzer.py
├── README.md

## ▶️ How to run the project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Password-Analyzer.git
Go to the project folder:

cd Password-Analyzer
Run the program:

python src/password_analyzer.py

Output:

<img width="1919" height="1138" alt="image" src="https://github.com/user-attachments/assets/40ed482f-741b-4912-bf51-10a1f5a423bb" />




#🔐 Password strength criteria

-> A password is considered strong if it:

-> Has at least 8 characters

-> Includes uppercase and lowercase letters

-> Includes numbers

-> Includes special characters

-> Is not a commonly used password

-> It Has high entropy


---
#⚠️ Limitations

-> Passwords are not stored anywhere

-> No online breach database is used

-> Command-line interface only

---

#🔮 Future improvements

-> Add a graphical user interface (GUI)

-> Add a password generator

-> Check passwords against data breaches

-> Convert this into a web application

-> Add password hashing support

---

#📚 What I learned

-> Basics of password security

-> How entropy affects password strength

-> Using regular expressions in Python

-> Writing clean and readable Python code

-> Structuring a project for GitHub

---
