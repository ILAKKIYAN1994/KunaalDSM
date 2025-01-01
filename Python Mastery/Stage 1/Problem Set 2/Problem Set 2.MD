### **Stage 1: Data Types and Operations - Problem Statements with Solutions**

#### **Problem 1: Sum of Two Numbers**
**Scenario:** You are tasked with calculating the sum of two integers.
- **Problem Statement:**  
  Write a program that takes two integer inputs from the user and returns the sum.
- **Starter Code:**
  ```python
  num1 = int(input("Enter the first number: "))
  num2 = int(input("Enter the second number: "))
  sum = num1 + num2
  print(f"The sum is: {sum}")
  ```
- **Hint:** Use the `+` operator to add the two integers.
- **Solution:**
  ```python
  num1 = int(input("Enter the first number: "))
  num2 = int(input("Enter the second number: "))
  sum = num1 + num2
  print(f"The sum is: {sum}")
  ```
- **Expected Output:**  
  ```
  Enter the first number: 5
  Enter the second number: 7
  The sum is: 12
  ```

---

#### **Problem 2: Find the Product of Two Numbers**
**Scenario:** You need to multiply two floating-point numbers.
- **Problem Statement:**  
  Write a program that takes two float inputs from the user and returns their product.
- **Starter Code:**
  ```python
  num1 = float(input("Enter the first number: "))
  num2 = float(input("Enter the second number: "))
  product = num1 * num2
  print(f"The product is: {product}")
  ```
- **Hint:** Use the `*` operator to multiply the two floats.
- **Solution:**
  ```python
  num1 = float(input("Enter the first number: "))
  num2 = float(input("Enter the second number: "))
  product = num1 * num2
  print(f"The product is: {product}")
  ```
- **Expected Output:**  
  ```
  Enter the first number: 3.5
  Enter the second number: 2.4
  The product is: 8.4
  ```

---

#### **Problem 3: Dividing Two Numbers**
**Scenario:** You are calculating the division of two numbers and need to handle division by zero.
- **Problem Statement:**  
  Write a program that divides two numbers, but handles division by zero by displaying an appropriate error message.
- **Starter Code:**
  ```python
  num1 = float(input("Enter the numerator: "))
  num2 = float(input("Enter the denominator: "))
  if num2 == 0:
      print("Error: Cannot divide by zero!")
  else:
      result = num1 / num2
      print(f"The result is: {result}")
  ```
- **Hint:** Use an `if` condition to check if the denominator is zero before performing division.
- **Solution:**
  ```python
  num1 = float(input("Enter the numerator: "))
  num2 = float(input("Enter the denominator: "))
  if num2 == 0:
      print("Error: Cannot divide by zero!")
  else:
      result = num1 / num2
      print(f"The result is: {result}")
  ```
- **Expected Output:**  
  ```
  Enter the numerator: 10
  Enter the denominator: 0
  Error: Cannot divide by zero!
  ```

---

#### **Problem 4: String Concatenation**
**Scenario:** You are working with user input to combine two strings.
- **Problem Statement:**  
  Write a program that takes two strings from the user and combines them into a single string.
- **Starter Code:**
  ```python
  string1 = input("Enter the first string: ")
  string2 = input("Enter the second string: ")
  result = string1 + " " + string2
  print(f"The concatenated string is: {result}")
  ```
- **Hint:** Use the `+` operator to concatenate strings and add a space in between.
- **Solution:**
  ```python
  string1 = input("Enter the first string: ")
  string2 = input("Enter the second string: ")
  result = string1 + " " + string2
  print(f"The concatenated string is: {result}")
  ```
- **Expected Output:**  
  ```
  Enter the first string: Hello
  Enter the second string: World
  The concatenated string is: Hello World
  ```

---

#### **Problem 5: String Length**
**Scenario:** You need to find the length of a string entered by the user.
- **Problem Statement:**  
  Write a program that takes a string input from the user and prints the length of that string.
- **Starter Code:**
  ```python
  string = input("Enter a string: ")
  length = len(string)
  print(f"The length of the string is: {length}")
  ```
- **Hint:** Use the built-in `len()` function to find the length of a string.
- **Solution:**
  ```python
  string = input("Enter a string: ")
  length = len(string)
  print(f"The length of the string is: {length}")
  ```
- **Expected Output:**  
  ```
  Enter a string: Python
  The length of the string is: 6
  ```

---

#### **Problem 6: String to Uppercase**
**Scenario:** Convert a string to uppercase.
- **Problem Statement:**  
  Write a program that converts a given string to uppercase.
- **Starter Code:**
  ```python
  string = input("Enter a string: ")
  uppercased_string = string.upper()
  print(f"The uppercase string is: {uppercased_string}")
  ```
- **Hint:** Use the `.upper()` method to convert the string to uppercase.
- **Solution:**
  ```python
  string = input("Enter a string: ")
  uppercased_string = string.upper()
  print(f"The uppercase string is: {uppercased_string}")
  ```
- **Expected Output:**  
  ```
  Enter a string: python
  The uppercase string is: PYTHON
  ```

---

#### **Problem 7: List of Numbers**
**Scenario:** You are working with a list of numbers and need to perform some operations.
- **Problem Statement:**  
  Write a program that adds all numbers in a list and prints the result.
- **Starter Code:**
  ```python
  numbers = [10, 20, 30, 40, 50]
  total = sum(numbers)
  print(f"The total sum of numbers is: {total}")
  ```
- **Hint:** Use the built-in `sum()` function to find the sum of all numbers in a list.
- **Solution:**
  ```python
  numbers = [10, 20, 30, 40, 50]
  total = sum(numbers)
  print(f"The total sum of numbers is: {total}")
  ```
- **Expected Output:**  
  ```
  The total sum of numbers is: 150
  ```

---

#### **Problem 8: Check if Element Exists in List**
**Scenario:** You need to check if an element exists in a list.
- **Problem Statement:**  
  Write a program that checks if a specific number exists in a list of numbers.
- **Starter Code:**
  ```python
  numbers = [1, 2, 3, 4, 5]
  number_to_find = int(input("Enter a number to check: "))
  if number_to_find in numbers:
      print(f"The number {number_to_find} exists in the list.")
  else:
      print(f"The number {number_to_find} does not exist in the list.")
  ```
- **Hint:** Use the `in` keyword to check for the presence of an element in a list.
- **Solution:**
  ```python
  numbers = [1, 2, 3, 4, 5]
  number_to_find = int(input("Enter a number to check: "))
  if number_to_find in numbers:
      print(f"The number {number_to_find} exists in the list.")
  else:
      print(f"The number {number_to_find} does not exist in the list.")
  ```
- **Expected Output:**  
  ```
  Enter a number to check: 3
  The number 3 exists in the list.
  ```

---

#### **Problem 9: Dictionary Operations**
**Scenario:** You are working with a dictionary of students and their grades.
- **Problem Statement:**  
  Write a program that adds a new student to a dictionary and prints all student names.
- **Starter Code:**
  ```python
  students = {"Alice": 85, "Bob": 92, "Charlie": 78}
  new_student = input("Enter the student's name: ")
  new_grade = int(input(f"Enter {new_student}'s grade: "))
  students[new_student] = new_grade
  print("Updated student list:")
  for student in students:
      print(student)
  ```
- **Hint:** Use the dictionary's `[]` notation to add new entries.
- **Solution:**
  ```python
  students = {"Alice": 85, "Bob": 92, "Charlie": 78}
  new_student = input("Enter the student's name: ")
  new_grade = int(input(f"Enter {new_student}'s grade: "))
  students[new_student] = new_grade
  print("Updated student list:")
  for student in students:
      print(student)
  ```
- **Expected Output:**  
  ```
  Enter the student's name: Diana
  Enter Diana's grade: 90
  Updated student list:
  Alice
  Bob
  Charlie
  Diana
  ```

---

#### **Problem 10: Average of Numbers in a List**
**Scenario:** Calculate the average of numbers in a list.
- **Problem Statement:**  
  Write a program that calculates and prints the average of numbers in a list.
- **Starter Code:**
  ```python
  numbers = [10, 20, 30, 40, 50]
  average = sum(numbers) / len(numbers)
  print(f"The average of the numbers is: {average}")
  ```
- **Hint:** Use the `sum()` function to get the total and `len()` to get the number of elements.
- **Solution:**
  ```python
  numbers = [10, 20, 30, 40, 50]
  average = sum(numbers) / len(numbers)
  print(f"The average of the numbers is: {average}")
  ```
- **Expected Output:**  
  ```
  The average of the numbers is: 30.0
  ```

---

This set of problems takes you through basic arithmetic operations, string manipulations, and working with Python's built-in data types like lists, dictionaries, and strings. The solutions provided help you understand each concept and allow you to practice writing Python code that solves real-world problems.