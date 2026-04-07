📘 Python Program: Try-Except-Finally Example


📌 Overview

This Python program demonstrates the use of try, except, and finally blocks in exception handling.

try → contains code that may cause an error
except → handles the error (if any)
finally → always executes, whether an error occurs or not
⚙️ Source Code
try:
    print("Try block running")
    x = 10 / 2

except:
    print("Error occurred")

finally:
    print("This will always run")
🧠 How It Works
1️⃣ Try Block
try:
    print("Try block running")
    x = 10 / 2
Executes normally.
Performs division (10 / 2 = 5.0).
No error occurs here.
2️⃣ Except Block
except:
    print("Error occurred")
This block runs only if an error occurs in the try block.
In this case, it is not executed because no error happens.
3️⃣ Finally Block
finally:
    print("This will always run")
This block always executes, regardless of whether an error occurs or not.
▶️ Output
Try block running
This will always run
🔑 Key Concepts Used
Exception handling (try-except-finally)
Guaranteed execution using finally
Safe program execution
⏱️ Time Complexity

O(1) — Constant time execution.

⚠️ Important Note
Using a generic except: is not recommended in real applications.
It’s better to catch specific exceptions.
🚀 Improved Version
try:
    print("Try block running")
    x = 10 / 2

except ZeroDivisionError:
    print("Cannot divide by zero")

finally:
    print("This will always run")
📚 Learning Outcome

After understanding this program, you will learn:

How try, except, and finally work together
Why finally is useful (cleanup, closing files, etc.)
How to make programs more reliable
