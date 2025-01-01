Here are **10 Python basics problems** for **Stage 1**, with scenarios, problem statements, hints, and solutions:

---

### **Problem 1: Greeting the User**
**Scenario:** Write a program to greet the user by name.
- **Problem Statement:**  
  Prompt the user to input their name, then print a message that says, "Hello, [name]! Welcome to Python!"
- **Starter Code:**
  ```python
  name = input("Enter your name: ")
  print("Hello, " + name + "! Welcome to Python!")
  ```
- **Hint:** Use `input()` to get the name and `print()` to display the message.
- **Solution:**  
  ```python
  name = input("Enter your name: ")
  print("Hello, " + name + "! Welcome to Python!")
  ```
- **Expected Output:**
  ```
  Enter your name: John
  Hello, John! Welcome to Python!
  ```

---

### **Problem 2: Basic Arithmetic**
**Scenario:** Perform basic arithmetic operations.
- **Problem Statement:**  
  Get two numbers from the user and print their sum, difference, product, and quotient.
- **Starter Code:**
  ```python
  num1 = float(input("Enter the first number: "))
  num2 = float(input("Enter the second number: "))
  print("Sum: ", num1 + num2)
  print("Difference: ", num1 - num2)
  print("Product: ", num1 * num2)
  print("Quotient: ", num1 / num2)
  ```
- **Hint:** Use arithmetic operators (`+`, `-`, `*`, `/`) to perform calculations.
- **Solution:**  
  ```python
  num1 = float(input("Enter the first number: "))
  num2 = float(input("Enter the second number: "))
  print("Sum: ", num1 + num2)
  print("Difference: ", num1 - num2)
  print("Product: ", num1 * num2)
  print("Quotient: ", num1 / num2)
  ```
- **Expected Output:**
  ```
  Enter the first number: 10
  Enter the second number: 5
  Sum:  15.0
  Difference:  5.0
  Product:  50.0
  Quotient:  2.0
  ```

---

### **Problem 3: Even or Odd**
**Scenario:** Check whether a number is even or odd.
- **Problem Statement:**  
  Take an integer input from the user and determine whether the number is even or odd.
- **Starter Code:**
  ```python
  num = int(input("Enter a number: "))
  if num % 2 == 0:
      print("Even")
  else:
      print("Odd")
  ```
- **Hint:** Use the modulo operator `%` to check if a number is divisible by 2.
- **Solution:**  
  ```python
  num = int(input("Enter a number: "))
  if num % 2 == 0:
      print("Even")
  else:
      print("Odd")
  ```
- **Expected Output:**
  ```
  Enter a number: 7
  Odd
  ```

---

### **Problem 4: Temperature Conversion**
**Scenario:** Convert Celsius to Fahrenheit.
- **Problem Statement:**  
  Write a program that takes a temperature in Celsius as input and converts it to Fahrenheit using the formula `F = (C * 9/5) + 32`.
- **Starter Code:**
  ```python
  celsius = float(input("Enter temperature in Celsius: "))
  fahrenheit = (celsius * 9/5) + 32
  print(f"{celsius}°C is equal to {fahrenheit}°F")
  ```
- **Hint:** Apply the conversion formula provided.
- **Solution:**  
  ```python
  celsius = float(input("Enter temperature in Celsius: "))
  fahrenheit = (celsius * 9/5) + 32
  print(f"{celsius}°C is equal to {fahrenheit}°F")
  ```
- **Expected Output:**
  ```
  Enter temperature in Celsius: 25
  25.0°C is equal to 77.0°F
  ```

---

### **Problem 5: Area of a Rectangle**
**Scenario:** Calculate the area of a rectangle.
- **Problem Statement:**  
  Prompt the user to input the length and width of a rectangle, and calculate the area.
- **Starter Code:**
  ```python
  length = float(input("Enter the length of the rectangle: "))
  width = float(input("Enter the width of the rectangle: "))
  area = length * width
  print(f"The area of the rectangle is {area}")
  ```
- **Hint:** Use the formula `area = length * width` to calculate the area.
- **Solution:**  
  ```python
  length = float(input("Enter the length of the rectangle: "))
  width = float(input("Enter the width of the rectangle: "))
  area = length * width
  print(f"The area of the rectangle is {area}")
  ```
- **Expected Output:**
  ```
  Enter the length of the rectangle: 5
  Enter the width of the rectangle: 3
  The area of the rectangle is 15.0
  ```

---

### **Problem 6: Sum of Natural Numbers**
**Scenario:** Calculate the sum of the first N natural numbers.
- **Problem Statement:**  
  Prompt the user to input a number `N`, and then calculate the sum of numbers from 1 to `N`.
- **Starter Code:**
  ```python
  N = int(input("Enter a number: "))
  sum_of_numbers = sum(range(1, N + 1))
  print(f"The sum of numbers from 1 to {N} is {sum_of_numbers}")
  ```
- **Hint:** Use `range(1, N+1)` to iterate over numbers from 1 to N, and `sum()` to calculate the sum.
- **Solution:**  
  ```python
  N = int(input("Enter a number: "))
  sum_of_numbers = sum(range(1, N + 1))
  print(f"The sum of numbers from 1 to {N} is {sum_of_numbers}")
  ```
- **Expected Output:**
  ```
  Enter a number: 5
  The sum of numbers from 1 to 5 is 15
  ```

---

### **Problem 7: Simple Calculator**
**Scenario:** Build a basic calculator.
- **Problem Statement:**  
  Write a program that allows the user to select an arithmetic operation (+, -, *, /) and perform the operation on two numbers entered by the user.
- **Starter Code:**
  ```python
  num1 = float(input("Enter the first number: "))
  num2 = float(input("Enter the second number: "))
  operation = input("Choose an operation (+, -, *, /): ")
  
  if operation == "+":
      print(f"Result: {num1 + num2}")
  elif operation == "-":
      print(f"Result: {num1 - num2}")
  elif operation == "*":
      print(f"Result: {num1 * num2}")
  elif operation == "/":
      print(f"Result: {num1 / num2}")
  else:
      print("Invalid operation")
  ```
- **Hint:** Use `if-elif-else` to check for the selected operation and perform the corresponding calculation.
- **Solution:**  
  ```python
  num1 = float(input("Enter the first number: "))
  num2 = float(input("Enter the second number: "))
  operation = input("Choose an operation (+, -, *, /): ")
  
  if operation == "+":
      print(f"Result: {num1 + num2}")
  elif operation == "-":
      print(f"Result: {num1 - num2}")
  elif operation == "*":
      print(f"Result: {num1 * num2}")
  elif operation == "/":
      print(f"Result: {num1 / num2}")
  else:
      print("Invalid operation")
  ```
- **Expected Output:**
  ```
  Enter the first number: 10
  Enter the second number: 5
  Choose an operation (+, -, *, /): *
  Result: 50.0
  ```

---

### **Problem 8: Leap Year Check**
**Scenario:** Check whether a given year is a leap year.
- **Problem Statement:**  
  Prompt the user to input a year and check whether it's a leap year.
- **Starter Code:**
  ```python
  year = int(input("Enter a year: "))
  if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
      print("Leap year")
  else:
      print("Not a leap year")
  ```
- **Hint:** A year is a leap year if divisible by 4, but divisible by 100 only if also divisible by 400.
- **Solution:**  
  ```python
  year = int(input("Enter a year: "))
  if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
      print("Leap year")
  else:
      print("Not a leap year")
  ```
- **Expected Output:**
  ```
  Enter a year: 2024
  Leap year
  ```

---

### **Problem 9: Count Vowels in a String**
**Scenario:** Count the vowels in a string.
- **Problem Statement:**  
  Write a program that counts the vowels (`a, e, i, o, u`) in a string provided by the user.
- **Starter Code:**
  ```python
  string = input("Enter a string: ")
  vowels = "aeiou"
  count = 0
  for char in string:
      if char.lower() in vowels:
          count += 1
  print(f"Vowels in '{string}': {count}")
  ```
- **Hint:** Loop through the string and check each character against the list of vowels.
Here's the solution for the problem **"Count Vowels in a String"** using the given scenario:

### Solution:

```python
# Starter code
string = input("Enter a string: ")  # Taking input from the user
vowels = "aeiou"  # Defining the vowels
count = 0  # Initializing the count variable

# Looping through each character in the input string
for char in string:
    if char.lower() in vowels:  # Checking if the character is a vowel
        count += 1  # Incrementing count if it's a vowel

# Output the result
print(f"Vowels in '{string}': {count}")
```

### Example Outputs:

1. **For input "hello":**
   ```
   Enter a string: hello
   Vowels in 'hello': 2
   ```

2. **For input "Python programming":**
   ```
   Enter a string: Python programming
   Vowels in 'Python programming': 4
   ```

3. **For input "aeiou":**
   ```
   Enter a string: aeiou
   Vowels in 'aeiou': 5




### **Problem 10: Reverse a String**
**Scenario:** Reverse a string entered by the user.
- **Problem Statement:**  
  Write a program that takes a string input from the user and reverses it.
- **Starter Code:**
  ```python
  string = input("Enter a string: ")
  reversed_string = string[::-1]
  print(f"The reversed string is: {reversed_string}")
  ```
- **Hint:** Use string slicing to reverse the string.
- **Solution:**  
  ```python
  string = input("Enter a string: ")
  reversed_string = string[::-1]
  print(f"The reversed string is: {reversed_string}")
  ```
- **Expected Output:**
  ```
  Enter a string: Python
  The reversed string is: nohtyP
  ```

---

This makes the total of 10 problems for Python Basics, each designed to help you practice foundational concepts in Python programming.