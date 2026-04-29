# 💳 Credit Card Validator in Python

A clean and professional terminal-based Credit Card Validator built with Python.

This project validates credit card numbers using the **Luhn Algorithm**, a widely used checksum formula for detecting errors in identification numbers such as credit card numbers.

It demonstrates algorithmic thinking, input validation, string manipulation, function-based programming, and real-world problem solving using Python.

---

# 📌 Project Overview

The Credit Card Validator allows the user to enter a credit card number and checks whether the number is valid or invalid using the Luhn Algorithm.

The program also cleans user input by removing spaces and hyphens, validates the input format, checks the card number length, and detects common card types.

This project is more algorithm-focused than a simple game project, making it a strong addition to a beginner-to-intermediate Python portfolio.

---

# ✨ Features

## Core Features

* Credit card validation using the Luhn Algorithm
* Input cleaning for spaces and hyphens
* Number-only input validation
* Card length validation
* Card type detection
* Clean terminal interface
* Function-based code organization

## Supported Card Type Detection

| Card Type        | Common Starting Digits |
| ---------------- | ---------------------- |
| Visa             | 4                      |
| MasterCard       | 51, 52, 53, 54, 55     |
| American Express | 34, 37                 |
| Discover         | 6                      |

---

# 🛠 Technologies Used

* Python 3

No external libraries are required.

---

# 🚀 How to Run the Project

## Step 1 — Clone the Repository

```bash
git clone https://github.com/DonUserOn/python-credit-card-validator.git
cd python-credit-card-validator
```

## Step 2 — Run the Program

```bash
python main.py
```

---

# 🧪 Example Usage

```text
=============================================
        Credit Card Validator
=============================================
Enter a credit card number: 4539 1488 0343 6467

Result: Valid card number
Card Type: Visa
=============================================
```

---

# 🧠 How the Luhn Algorithm Works

The Luhn Algorithm checks whether a card number is mathematically valid.

Basic steps:

1. Remove spaces and hyphens from the input
2. Reverse the card number
3. Starting from the second digit, double every second digit
4. If the doubled number is greater than 9, subtract 9
5. Add all digits together
6. If the total is divisible by 10, the card number is valid

---

# 🧠 Programming Concepts Practiced

This project helps strengthen understanding of:

* Functions
* String methods
* Input validation
* Loops
* Conditional statements
* Reversing strings
* Arithmetic operations
* Algorithm implementation
* Clean code organization
* Real-world validation logic

---

# 📈 Future Improvements

Future versions of this project may include:

* GUI version using Tkinter
* Web version using Flask or Streamlit
* Masked card number display
* More advanced card issuer detection
* Unit testing with `pytest`
* Error logging
* Object-Oriented Programming version
* Batch validation from a text file or CSV file

---

# 💡 What I Learned

While building this project, I improved my understanding of:

* Implementing real-world algorithms in Python
* Writing cleaner and more modular code
* Validating user input properly
* Using string manipulation for data cleaning
* Detecting and fixing logical bugs
* Preparing practical Python projects for GitHub

This project helped me move beyond simple games and practice more practical programming skills that are useful in real software development.

---

# 👨‍💻 Author

## Hanan Ossama

AI Student | Python Developer | Future AI Engineer

Focused on building practical Python projects, AI assistant tools, automation systems, and beginner-to-intermediate software projects with real-world value.

## Connect With Me

GitHub:
https://github.com/DonUserOn

Future Portfolio Website:
Coming Soon

---

# ⭐ Repository Goal

This repository is part of my Python learning journey and portfolio development. It demonstrates my ability to implement algorithms, validate user input, write clean Python code, and prepare professional GitHub projects for future internship opportunities.
