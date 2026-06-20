# 🧮 Interactive Command-Line Calculator

A dynamic, interactive command-line calculator built with Python. This project utilizes Python dictionaries to map mathematical functions, allowing users to perform continuous calculations or start fresh ones seamlessly.

---

## ✨ Features

* **Basic Arithmetic:** Supports Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`).
* **Accumulate Results:** Allows you to carry over the previous answer to continue a long chain of calculations (typing `y`).
* **Instant Reset:** Easily clear the session and start a brand-new calculation whenever you want (typing `n`).
* **ASCII Art:** Features a stylish ASCII art logo on startup for a classic terminal UI feel.

---

## 🛠️ Prerequisites & Installation

To run this project locally, you will need **Python 3** installed on your system along with the `art` library for the logo.

1. **Install the required library:**
```bash
   pip install art

How it Works

Input the First Number: The program prompts you to type your starting number.

Choose an Operation: Pick from the displayed operations: +, -, *, or /.

Input the Next Number: Type the second number to complete the equation.

See the Result: The program prints the formatted equation and its answer.

Decide Next Step:

Type y to continue calculating using the current answer as the new starting number.

Type n to clear the screen and start a completely new calculation.


This project showcases clean coding principles in Python:

First-Class Functions & Dictionaries: Instead of bulky if/elif/else statements, operations are neatly mapped to their respective functions inside a dictionary (operations).

Recursion: The program calls itself (calculator()) to smoothly reset the state and loop back to the beginning when a user wants to start over.

👤
 Author: [Ayush Rawat]
