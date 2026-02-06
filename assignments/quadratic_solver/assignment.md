# Assignment: Quadratic Equation Solver

## Overview

Complete a Python program that solves quadratic equations of the form $ax^2 + bx + c = 0$. You will practice using functions, conditionals, and returns.

## Instructions

- Complete the To-Dos in the provided code files.
- Your program should:
  - Prompt the user for coefficients a, b, and c.
  - Calculate the discriminant.
  - Determine if there are 0, 1, or 2 real roots.
  - Print the roots if they exist.

## Files to Edit

- `main.py`: Handles user input/output.
- `quadratic.py`: Contains the function to solve the equation.

## Hints

- Use the quadratic formula: $x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$
- Use `math.sqrt()` for square roots.
- Remember to handle the case where the discriminant is negative.
- Start by writing a function that takes three arguments (a, b, c).
- Use `input()` to get values from the user and convert them to floats.
- Calculate the discriminant first and print it for debugging.
- Use `if`, `elif`, and `else` to handle the three cases (no real roots, one root, two roots).
- Try printing intermediate results to check your logic.

---

## Extension

Add input validation to ensure the user enters valid numbers.
