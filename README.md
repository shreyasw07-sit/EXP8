# EXP8
🐍 Experiment 8: Use of for Loop in Python
Name: SHREYAS WANI

PRN: 25070123131

Category: Python Programming Basics

📖 Description
This experiment explores the versatility of the for loop in Python. It covers fundamental iterations using range(), nested loops for matrix operations, and conditional logic for mathematical problem-solving like prime number identification.

🛠️ Features & Examples
The notebook contains several practical implementations of loops:

1. Basic Iteration

Sequential Counting: Simple loops to print numbers from 1 to 5.

Step Values: Using range(1, 11, 2) to print only odd numbers.

2. Mathematical Calculations

Sum of N Numbers: Accepts user input to calculate the cumulative sum of the first N integers.

Prime Number Finder: A nested loop structure that identifies and prints all prime numbers between 2 and 50.

3. Matrix Operations

3x3 Matrix Display: Iterates through a 2D list to display a matrix in a readable grid format.

Matrix Multiplication: Performs dot-product multiplication between two 3×3 matrices using triple nested loops.

4. Pattern Generation

Reverse Triangle: Uses a decreasing step in the range to print a descending star (*) pattern.

💻 Code Snippets
Matrix Multiplication Logic

Python
for i in range(3):
  for j in range(3):
    for k in range(3):
      result[i][j] += A[i][k] * B[k][j]
Prime Number Logic

Python
for i in range(2, 50):
  for n in range(2, i):
    if i % n == 0:
      break
  else:
    print(i) # Executed if no factor is found
