# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
class Demo: def init(self):
 print("Hello World!")
 ef del(self):
 print("Hello from the del method.")
 obj = Demo()
 del obj

## 🧪 Output
<img width="737" height="130" alt="image" src="https://github.com/user-attachments/assets/82f885dc-ab9d-47dc-b2fc-c706fbed9249" />


## Result
Thus, the program has been successfully executed.
