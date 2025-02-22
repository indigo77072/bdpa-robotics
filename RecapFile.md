# Python Basics Review

## **Introduction**
This document is a quick review of all the Python basics we have learned so far. It includes key concepts and short exercises to help refresh your memory. Try to complete each exercise on your own before checking the solutions!

---

## **1. Printing Output**
### **Concept:**
- We use `print()` to display text on the screen.
- Strings must be in quotes (`" "` or `' '`).

### **Example:**
```python
print("Hello, Python!")
print('This is a string.')
```

### **Quick Exercise:**
Write a program that prints your name and favorite food.

---

## **2. Variables**
### **Concept:**
- Variables store values.
- Variable names should be meaningful.

### **Example:**
```python
name = "Alex"
age = 12
print("My name is", name, "and I am", age, "years old.")
```

### **Quick Exercise:**
Create a variable for your favorite color and print a sentence using it.

---

## **3. Data Types**
### **Concept:**
Python has different types of data:
- **String (`str`)** → `"Hello"`
- **Integer (`int`)** → `15`
- **Float (`float`)** → `5.6`
- **Boolean (`bool`)** → `True` / `False`

### **Example:**
```python
print(type("Hello"))  # str
print(type(15))       # int
print(type(5.6))      # float
print(type(True))     # bool
```

### **Quick Exercise:**
Try printing the type of different values (e.g., a number, a word, and a decimal number).

---

## **4. User Input**
### **Concept:**
- `input()` gets user input.
- `int()` or `float()` converts input into numbers.

### **Example:**
```python
name = input("What is your name? ")
print("Hello, " + name + "!")
```

### **Quick Exercise:**
Ask the user for their age and print a message with it.

---

## **5. Arithmetic Operations**
### **Concept:**
| Operator | Meaning |
|----------|---------|
| `+` | Addition |
| `-` | Subtraction |
| `*` | Multiplication |
| `/` | Division |
| `//` | Floor Division |
| `%` | Modulus (Remainder) |
| `**` | Exponentiation |

### **Example:**
```python
num1 = 10
num2 = 3
print("Sum:", num1 + num2)
print("Difference:", num1 - num2)
print("Product:", num1 * num2)
print("Quotient:", num1 / num2)
print("Floor Division:", num1 // num2)
print("Remainder:", num1 % num2)
print("Power:", num1 ** num2)
```

### **Quick Exercise:**
Write a program that asks the user for two numbers and prints their sum and difference.

---

## **6. String Formatting**
### **Concept:**
- We can format strings in different ways:

### **Example 1: Using `+` for Concatenation:**
```python
name = "Alex"
print("Hello, " + name + "!")
```

### **Example 2: Using f-strings (Recommended):**
```python
age = 12
print(f"Next year, you will be {age + 1} years old.")
```

### **Quick Exercise:**
Use an f-string to print a sentence about your favorite hobby.

---

## **7. Comparison and Boolean Logic**
### **Concept:**
| Operator | Meaning |
|----------|---------|
| `==` | Equal to |
| `!=` | Not equal to |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal to |
| `<=` | Less than or equal to |

### **Example:**
```python
print(5 > 3)  # True
print(10 == 5)  # False
```

### **Quick Exercise:**
Write a program that asks the user for their age and checks if they are older than 18.

---

## **8. If-Else Statements**
### **Concept:**
- `if` statements allow conditional execution.
- `else` runs if the condition is false.

### **Example:**
```python
age = int(input("Enter your age: "))
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```

### **Quick Exercise:**
Write a program that asks for a number and prints whether it is positive or negative.

---

## **9. Loops**
### **Concept:**
- `for` loops iterate over a sequence.
- `while` loops run until a condition is false.

### **Example 1: For Loop**
```python
for i in range(5):
    print("Hello")
```

### **Example 2: While Loop**
```python
x = 0
while x < 3:
    print("Looping!")
    x += 1
```

### **Quick Exercise:**
Write a loop that prints numbers from 1 to 10.

---

## **10. Mini Challenge**
### **Task:**
Write a Python script that:
1. Asks the user for their name.
2. Asks the user for a number.
3. Prints the user’s name that many times.

Example:
```
Enter your name: Lily
Enter a number: 3
Lily
Lily
Lily
```

---

## **Final Review**
You now have a solid understanding of:
✅ Printing output  
✅ Variables and data types  
✅ User input  
✅ Math operations  
✅ String formatting  
✅ Comparison and boolean logic  
✅ If-else statements  
✅ Loops  

Keep practicing and have fun coding! 🚀