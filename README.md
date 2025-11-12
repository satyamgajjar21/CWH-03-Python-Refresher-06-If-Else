# 🧠 Python If-Else Statements — Beginner Tutorial

This repository contains a Jupyter Notebook demonstrating the concept of **conditional statements** in Python — one of the most fundamental parts of programming logic.  
You’ll learn how to make decisions in code using **if**, **elif**, and **else**.

---

## 📘 Project Overview

Conditional statements allow programs to **make choices** based on certain conditions.  
This notebook walks through examples that show how Python executes different blocks of code depending on whether conditions are **True** or **False**.

---

## 🧩 Topics Covered

1. **Introduction to Conditional Statements**
   - What are conditions?
   - How boolean expressions work (`True`/`False`).

2. **Using `if` Statements**
   - Basic structure and indentation rules.
   - Single condition checks.

3. **Using `if-else` Statements**
   - Handling two possible outcomes (True / False).

4. **Using `if-elif-else`**
   - Handling multiple possible conditions.

5. **Nested Conditions**
   - Writing conditions inside other conditions.

6. **Practical Examples**
   - Checking even or odd numbers.
   - Comparing two or more values.
   - Grading systems (A/B/C/F).
   - Checking age eligibility.

---

## ⚙️ Code Example

```python
# Example: Check if a number is positive, negative, or zero
num = float(input("Enter a number: "))

if num > 0:
    print("Positive number")
elif num == 0:
    print("Zero")
else:
    print("Negative number")
