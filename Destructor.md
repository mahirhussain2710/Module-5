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
```
class demo:
    def __init__(self):
        self.status="Alive"
    def __del__(self):
        print("The object no longer exists")
a=demo()
print(a.status)
```

## 🧪 Output
<img width="964" height="219" alt="image" src="https://github.com/user-attachments/assets/9400dd83-5f9e-4d7f-8c6a-789b5e55d229" />

## Result
Thus, the program demonstrates how to implement a non-parameterized constructor in Python using a simple class and has been executed successfully
