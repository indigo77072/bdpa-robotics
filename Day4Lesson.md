# Python Lesson Plan - Day 4: GitHub & Recap + Quiz

## **Objective**
Students will learn how to use GitHub to save and share their Python projects. They will review everything covered so far, then take a quiz to reinforce their knowledge.

---

## **1. Introduction to GitHub (45 minutes)**
### **What is GitHub?**
- A cloud-based platform for saving and sharing code.
- Helps with **version control** (tracking changes).
- Allows for **collaboration** with others.

### **Basic Git Commands:**
| Command | Purpose |
|---------|---------|
| `git clone <repo-url>` | Download a repository to your computer. |
| `git status` | Check which files have changed. |
| `git add .` | Stage all changes for commit. |
| `git commit -m "message"` | Save changes locally. |
| `git push origin main` | Upload changes to GitHub. |

---

## **2. Hands-On: Setting Up GitHub with VS Code (45 minutes)**
### **Step 1: Create a GitHub Account**
1. Go to [GitHub](https://github.com/) and sign up.
2. Verify your email and set up a username.

### **Step 2: Create a Repository**
1. Log in to GitHub.
2. Click the **"+" button** and select **"New Repository"**.
3. Type a **repository name** (example: `python-projects`).
4. Check **"Add a README file"**.
5. Click **"Create repository"**.

### **Step 3: Clone the Repository in VS Code**
1. Open **VS Code**.
2. Click **Source Control** (left sidebar).
3. Click **Clone Repository** and select **GitHub**.
4. Choose your repository and select a folder to save it.
5. The project will open in VS Code.

### **Step 4: Add and Commit a Python File**
1. Inside the repository, create a **Python file** (e.g., `day4.py`).
2. Add the following sample code:
   ```python
   print("Hello, I am learning GitHub!")
   ```
3. Save the file.
4. In the **Source Control** tab, type a commit message like **"Added day4.py"**.
5. Click **Commit** and then **Sync Changes** to upload your work to GitHub.

---

## **3. Recap of Python Lessons (30 minutes)**
### **Topics to Review:**
1. **Running Python in VS Code** (`print()`, saving and running `.py` files).
2. **Variables & User Input** (`input()`, `int()`, `float()`, `str()`).
3. **Math & String Formatting** (`+`, `-`, `*`, `/`, `//`, `%`, `**`, `f-strings`).

### **Hands-on Recap:**
- Create a new file (`recap.py`) and add this script:
  ```python
  name = input("What is your name? ")
  age = int(input("How old are you? "))
  print(f"Hello {name}, next year you will be {age + 1} years old!")
  ```
- **Commit and push the changes to GitHub**.

---

## **4. Python Quiz (45 minutes)**
### **Section 1: Multiple Choice (5 Questions)**
1. What does `git push origin main` do?
   - A) Download a GitHub repository  
   - B) Upload changes to GitHub ✅  
   - C) Delete a file  
   - D) Start a new project  

2. What is the correct way to take user input in Python?  
   - A) `getInput()`  
   - B) `input()` ✅  
   - C) `read()`  
   - D) `ask()`  

3. What is the result of `10 // 3` in Python?  
   - A) `3.33`  
   - B) `3` ✅  
   - C) `4`  
   - D) `Error`  

4. How do you print `"Hello, Alex!"` using an f-string?  
   - A) `print("Hello, " + Alex + "!")`  
   - B) `print(f"Hello, {Alex}!")` ✅  
   - C) `print("Hello, {Alex}")`  
   - D) `print("Hello," Alex "!")`  

5. What happens if you try to divide by zero in Python?  
   - A) `0`  
   - B) `Python guesses the answer`  
   - C) `Error` ✅  
   - D) `Infinity`  

---

### **Section 2: True/False (5 Questions)**
1. `git commit -m "message"` saves your changes to GitHub. **(False)**
2. `input()` always returns a string. **(True)**
3. The modulus operator `%` gives the remainder of division. **(True)**
4. `int(input("Enter a number: "))` converts user input to an integer. **(True)**
5. `print("Hello" + 5)` is a valid Python statement. **(False)**

---

### **Section 3: Coding Questions (5 Questions)**
1. Write a Python script that asks the user for two numbers and prints their sum.
   ```python
   num1 = int(input("Enter first number: "))
   num2 = int(input("Enter second number: "))
   print(f"Sum: {num1 + num2}")
   ```

2. What will this code print?
   ```python
   print(type(10.5))
   ```
   **Answer:** `<class 'float'>`

3. Fix the error in this code:
   ```python
   age = input("Enter age: ")
   print("Next year, you will be " + age + 1)
   ```
   **Corrected Code:**
   ```python
   age = int(input("Enter age: "))
   print(f"Next year, you will be {age + 1}")
   ```

4. What is the output of:
   ```python
   print(2 ** 3)
   ```
   **Answer:** `8`

5. How do you push changes to GitHub? **(Write 3 Git commands)**
   ```bash
   git add .
   git commit -m "Updated file"
   git push origin main
   ```

---

## **5. Quiz Review & Wrap-up (15 minutes)**
- Go over quiz answers with the class.
- Discuss any **common mistakes**.
- Congratulate students for completing **4 days of Python & GitHub!** 🎉
