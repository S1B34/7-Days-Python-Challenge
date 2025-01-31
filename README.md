# 7 Days Python Challenge

Welcome to the **7 Days Python Challenge**! 🎉 This plan is designed to help you start your Python journey and become a confident beginner in just one week. Each day builds on the previous day's knowledge, so stay consistent and enjoy the process!

---

## **Day 1: Introduction to Python** 🐍

### Goals:
- Understand what Python is and why it's awesome.
- Set up your Python environment.
- Write your first Python script.

### Tasks:
1. Install Python from [python.org](https://www.python.org).
2. Set up an IDE like VS Code or PyCharm.
3. Write and run your first Python script:
   ```python
   print("Hello, World!")
   ```

_(Hint: If your program runs without errors, celebrate like you just solved world hunger!)_

---

## **Day 2: Variables and Data Types** 💾

### Goals:
- Learn about variables and their types.
- Perform basic operations with numbers and strings.

### Tasks:
1. Experiment with different data types:
   ```python
   name = "Python"
   version = 3.10
   is_fun = True
   print(f"{name} {version} is fun: {is_fun}")
   ```
2. Write a program that takes input and displays output:
   ```python
   user_name = input("What is your name? ")
   print("Hello, " + user_name + "!")
   ```
3. Try basic arithmetic operations.

_(Pro Tip: Variables are like containers. You wouldn’t store juice in a shoe, right? Make sure your data type fits your variable!)_

---

## **Day 3: Control Flow** 🚦

### Goals:
- Understand conditional statements.
- Use loops to repeat tasks.

### Tasks:
1. Write an age-checking program:
   ```python
   age = int(input("Enter your age: "))
   if age < 18:
       print("You're a minor.")
   elif age == 18:
       print("You're exactly 18!")
   else:
       print("You're an adult.")
   ```
2. Use a `for` loop to print numbers 1 to 10.
3. Use a `while` loop to create a simple guessing game.

_(Loops are your new best friend! Just don’t get stuck in an infinite one, or you’ll be coding forever!)_

---

## **Day 4: Data Structures** 📦

### Goals:
- Learn about lists, tuples, dictionaries, and sets.
- Perform basic operations on these structures.

### Tasks:
1. Create a list of favorite foods and add/remove items.
   ```python
   foods = ["Pizza", "Burger", "Ice Cream"]
   foods.append("Tacos")
   print(foods)
   ```
2. Use a dictionary to store and retrieve user details.
   ```python
   user = {"name": "Ahmed", "age": 25}
   print(user["name"])
   ```
3. Experiment with set operations (union, intersection).

_(Fun fact: Python’s data structures are like superheroes. Lists are your utility belt, and dictionaries are your all-knowing sidekick!)_

---

## **Day 5: Functions** 🛠️

### Goals:
- Write reusable code using functions.
- Understand parameters and return values.

### Tasks:
1. Write a function to calculate the square of a number:
   ```python
   def square(x):
       return x ** 2
   print(square(4))
   ```
2. Create a function to greet the user:
   ```python
   def greet(name):
       print(f"Hello, {name}!")
   greet("Ahmed")
   ```
3. Experiment with lambda functions.

_(Remember: Functions are like your favorite playlist. Create them once, use them forever!)_

---

## **Day 6: Modules and File Handling** 📂

### Goals:
- Learn to import and use Python modules.
- Handle reading and writing files.

### Tasks:
1. Import the `math` module and use its functions:
   ```python
   import math
   print(math.sqrt(16))
   ```
2. Write and read from a file:
   ```python
   with open("example.txt", "w") as file:
       file.write("Hello, Python!")
   
   with open("example.txt", "r") as file:
       print(file.read())
   ```
3. Practice error handling with `try` and `except`.

_(Files are like time capsules. Use them wisely to save your data for the future!)_

---

## **Day 7: Practice Projects** 🎯

### Goals:
- Apply everything you’ve learned by building simple projects.

### Tasks:
1. Build a **Simple Calculator**:
   ```python
   def calculator():
       a = float(input("Enter first number: "))
       b = float(input("Enter second number: "))
       print("Sum:", a + b)
   calculator()
   ```
2. Create a **To-Do List** program:
   ```python
   tasks = []
   while True:
       task = input("Add a task (or type 'done' to finish): ")
       if task.lower() == 'done':
           break
       tasks.append(task)
   print("Your tasks:", tasks)
   ```
3. Write a **Guessing Game**:
   ```python
   import random
   number = random.randint(1, 10)
   while True:
       guess = int(input("Guess the number (1-10): "))
       if guess == number:
           print("Correct!")
           break
       else:
           print("Try again!")
   ```

_(Practice projects are your playground. Don’t be afraid to try new ideas—Python won’t judge!)_

---

## Final Thoughts 🏁
Congratulations on completing the **7 Days Python Challenge**! 🎉 Keep practicing and building small projects to solidify your knowledge. Python is a versatile and fun language, and you’re just getting started!

_(P.S. The only bug you should worry about is the one crawling on your screen, not in your code!)_

Happy Coding! 😄
