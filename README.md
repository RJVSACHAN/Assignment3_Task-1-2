# ASSIGNMENT 3: Module 4: Task_1_and_2
# Task1: Factorial of any number
n=int(input('Enter the number: '))
def factorial(n):
    if n<2:
        return 1
    else:
        return n*(factorial(n-1))
result = factorial(n)
print(f'The factorial of {n} is: {result}')

#  Task2: Use of modules in python
n=int(input('Enter the number: '))
from math import *
print(sqrt(n))
print(log(n))
print(sin(n))
