# 🐍 Python for STEM — GitHub Portfolio Guide
**Bishop's Stortford College | Year 12 | Independent Study**

> This guide will walk you through building a professional GitHub portfolio that showcases your Python skills. Work through each section at your own pace. By the end, you will have a portfolio you can share with universities and future employers.

---

## 📋 What You Will Build

| Section | What You'll Do | Where You'll Work |
|---|---|---|
| **Part 1** | Set up your GitHub account and repository | github.com |
| **Part 2** | Write your portfolio README using Markdown | github.dev |
| **Part 3** | Complete Python programs and add them as evidence | github.dev + Thonny |
| **Part 4** | Add Jupyter Notebooks to your portfolio | github.dev |
| **Part 5** | Polish and present your portfolio | github.dev |

---

## ⚠️ Before You Start — Read This

**Two tools, two jobs:**

- **github.dev** — A code editor that runs in your browser. Use this for writing Markdown, editing `.py` files, and uploading notebooks. *You cannot run Python here.*
- **Thonny** — Your Python IDE on your school computer. Use this for writing and testing Python programs. Upload finished files to GitHub afterwards.

---

---

# PART 1 — Setting Up Your GitHub Account

## Step 1.1 — Create a GitHub Account

1. Go to [https://github.com](https://github.com)
2. Click **Sign up**
3. Use a **professional username** — this will appear on your CV. Good examples:
   - `j-smith-bsc` or `johnsmith-dev`
   - Avoid usernames like `xXgamer99Xx`
4. Use your school email address
5. Complete the setup and verify your email

> 💡 **Tip:** Your GitHub username will be part of your portfolio URL. Choose something you'd be happy showing a university admissions tutor.

---

## Step 1.2 — Create Your Portfolio Repository

A **repository** (or "repo") is a folder on GitHub that stores all your project files.

1. Once logged in, click the **green "New"** button (top left)
2. Fill in the form:
   - **Repository name:** `python-stem-portfolio`
   - **Description:** `Python programming portfolio — Bishop's Stortford College STEM course`
   - Set to **Public** (so universities can view it)
   - ✅ Tick **"Add a README file"**
3. Click **Create repository**

You will now see your empty repository. 🎉

---

## Step 1.3 — Open Your Repository in github.dev

This is the browser-based editor you will use for most of this guide.

1. On your repository page, press the **full stop key ( . )** on your keyboard
2. The page will reload as a code editor — this is **github.dev**
3. You should see your `README.md` file listed on the left

> 💡 You can also reach it by changing `github.com` to `github.dev` in the URL bar.

---

---

# PART 2 — Writing Your README with Markdown

Your README is the **front page** of your portfolio. It is the first thing anyone sees. This section teaches you Markdown — the simple formatting language used on GitHub.

## Step 2.1 — Markdown Basics

Markdown uses plain text symbols to create formatted headings, lists, and more. Here is a quick reference:

### Headings
```markdown
# Large Heading (H1)
## Medium Heading (H2)
### Small Heading (H3)
```

### Text Formatting
```markdown
**bold text**
*italic text*
`inline code` (use for code, filenames, and technical terms)
```

### Lists
```markdown
- Item one
- Item two
- Item three

1. First step
2. Second step
3. Third step
```

### Links
```markdown
[Link text](https://www.example.com)
```

### Code Blocks
Use triple backticks to show multi-line code:

````markdown
```python
name = input("What is your name? ")
print(f"Hello, {name}!")
```
````

### Tables
```markdown
| Column 1 | Column 2 | Column 3 |
|---|---|---|
| Value A  | Value B  | Value C  |
```

### Horizontal Rule (divider)
```markdown
---
```

---

## Step 2.2 — Write Your Portfolio README

In github.dev, click on `README.md` in the left panel to open it.

Delete everything that is there and replace it with the template below. **Fill in the sections marked with [ ].**

```markdown
# 🐍 Python Programming Portfolio

**Name:** [Your Full Name]  
**School:** Bishop's Stortford College  
**Course:** Python for STEM  
**Year:** Year 12, [Academic Year]

---

## About Me

[Write 3–4 sentences about yourself. Include your STEM interests, what subjects you study at A Level, and what you hope to study at university or do as a career. Be genuine — this is your voice.]

---

## Course Overview

This portfolio documents my progress through a Python programming course designed for students preparing for STEM pathways at university. The course covers:

- Python fundamentals (variables, input/output, data types)
- Control structures (loops and conditionals)
- Functions and modular code
- Data structures (lists, dictionaries, tuples, sets)
- Validation and error handling
- File handling
- Object-Oriented Programming (OOP)
- Version control with Git and GitHub
- Working with Jupyter Notebooks

---

## Portfolio Projects

| # | Project | Key Skills | Status |
|---|---|---|---|
| 1 | [Unit Converter](#) | Variables, functions, input/output | ✅ Complete |
| 2 | [Number Guessing Game](#) | Loops, conditionals, random | ✅ Complete |
| 3 | [To-Do List](#) | Lists, functions, data structures | ✅ Complete |
| 4 | [Student Grade Calculator](#) | Dictionaries, validation, error handling | ✅ Complete |
| 5 | [OOP Bank Account](#) | Classes, OOP principles | ✅ Complete |
| 6 | [Data Analysis Notebook](#) | Jupyter Notebooks, data exploration | ✅ Complete |

---

## Skills I Have Developed

**Programming Concepts**
- Writing clean, well-commented Python code
- Using functions to organise and reuse code
- Handling user input safely with validation

**Tools and Technologies**
- Python 3 (Thonny IDE)
- Jupyter Notebooks
- Git version control
- GitHub for code sharing and portfolio management
- Markdown for documentation

---

## Contact

- **GitHub:** [your-username]
- **Email:** [your school email]
```

---

## Step 2.3 — Save and Commit Your README

In github.dev, saving to GitHub is called **committing**.

1. Click the **Source Control icon** in the left sidebar (it looks like a branch/fork symbol, or shows a number badge)
2. You will see `README.md` listed as a changed file
3. In the **Message** box at the top, type: `Add portfolio README`
4. Click the **✓ Commit & Push** button (or press `Ctrl+Enter`)

Your README is now live on GitHub. Go to `github.com/your-username/python-stem-portfolio` to see it.

> ✅ **Checkpoint:** Your repository front page should now show your formatted README.

---

---

# PART 3 — Python Projects as Portfolio Evidence

For each project below, you will:
1. Write and test the code in **Thonny**
2. Upload the `.py` file to your GitHub repository using **github.dev**
3. Add a short description to your README

---

## How to Upload a Python File to GitHub

After completing each program in Thonny and saving the `.py` file:

1. Open your repository in **github.dev** (press `.` on your repo page)
2. In the left panel, right-click in the file list and choose **"Upload Files…"** (or drag your file into the panel)
3. Your file will appear in the file list
4. Go to **Source Control** (left sidebar), write a commit message like `Add unit converter program`, and click **Commit & Push**

---

## Project 1 ⭐ — Unit Converter

**Skills covered:** Variables, functions, input/output, type casting  
**File to create:** `unit_converter.py`

### What it should do:
A program that converts between common units. At minimum:
- Kilometres ↔ Miles
- Celsius ↔ Fahrenheit
- Kilograms ↔ Pounds

### Guidance

Start by writing one conversion as a function:

```python
def km_to_miles(km):
    """Convert kilometres to miles."""
    miles = km * 0.621371
    return miles

def miles_to_km(miles):
    """Convert miles to kilometres."""
    km = miles / 0.621371
    return km
```

Then add a menu so the user can choose which conversion to perform:

```python
def show_menu():
    print("=== Unit Converter ===")
    print("1. Kilometres to Miles")
    print("2. Miles to Kilometres")
    print("3. Celsius to Fahrenheit")
    print("4. Fahrenheit to Celsius")

def main():
    show_menu()
    choice = input("Enter your choice (1-4): ")
    
    if choice == "1":
        km = float(input("Enter kilometres: "))
        result = km_to_miles(km)
        print(f"{km} km = {result:.2f} miles")
    # Add more elif branches for choices 2, 3, 4...

main()
```

> 💡 `:.2f` in an f-string means "round to 2 decimal places". Try it!

### ⭐ Challenge extension
Add kg ↔ pounds and litres ↔ pints conversions. Add input validation so the program doesn't crash if the user types a letter instead of a number.

---

## Project 2 ⭐ — Number Guessing Game

**Skills covered:** Loops, conditionals, random module, input validation  
**File to create:** `guessing_game.py`

### What it should do:
The computer picks a random number. The player guesses until they get it right. The program tells them if their guess is too high or too low. It counts the number of guesses.

### Guidance

```python
import random

def play_game():
    """Play one round of the guessing game."""
    secret = random.randint(1, 100)
    attempts = 0
    
    print("I'm thinking of a number between 1 and 100.")
    
    while True:
        guess = int(input("Your guess: "))
        attempts += 1
        
        if guess < secret:
            print("Too low! Try again.")
        elif guess > secret:
            print("Too high! Try again.")
        else:
            print(f"Correct! You got it in {attempts} attempts.")
            break  # Exit the loop

play_game()
```

### ⭐ Challenge extension
- Ask if the player wants to play again when they win
- Keep track of their best score (fewest attempts) across multiple rounds
- Add difficulty levels: Easy (1–50), Medium (1–100), Hard (1–500)

---

## Project 3 ⭐⭐ — To-Do List Manager

**Skills covered:** Lists, functions, loops, conditionals  
**File to create:** `todo_list.py`

### What it should do:
A simple to-do list where the user can add tasks, view all tasks, mark a task as done, and remove tasks.

### Guidance

```python
def show_tasks(tasks):
    """Display all tasks with their numbers."""
    if len(tasks) == 0:
        print("No tasks yet!")
        return
    
    print("\n=== Your Tasks ===")
    for i, task in enumerate(tasks, start=1):
        print(f"{i}. {task}")
    print()

def add_task(tasks):
    """Add a new task to the list."""
    new_task = input("Enter task: ")
    tasks.append(new_task)
    print(f"Added: '{new_task}'")

def remove_task(tasks):
    """Remove a task by number."""
    show_tasks(tasks)
    number = int(input("Enter task number to remove: "))
    if 1 <= number <= len(tasks):
        removed = tasks.pop(number - 1)
        print(f"Removed: '{removed}'")
    else:
        print("Invalid number.")

def main():
    tasks = []
    
    while True:
        print("=== To-Do List ===")
        print("1. View tasks")
        print("2. Add task")
        print("3. Remove task")
        print("4. Quit")
        
        choice = input("Choose: ")
        
        if choice == "1":
            show_tasks(tasks)
        elif choice == "2":
            add_task(tasks)
        elif choice == "3":
            remove_task(tasks)
        elif choice == "4":
            print("Goodbye!")
            break

main()
```

### ⭐ Challenge extension
Add the ability to mark tasks as "done" without removing them (e.g., show `✓ Task name` for completed tasks). Use a list of dictionaries instead of a list of strings, where each dictionary stores the task name and a done/not-done status.

---

## Project 4 ⭐⭐ — Student Grade Calculator

**Skills covered:** Dictionaries, functions, validation, error handling  
**File to create:** `grade_calculator.py`

### What it should do:
The user enters a student's name and their scores for several subjects. The program calculates the average and assigns a grade (A, B, C, D, U). It handles invalid input gracefully.

### Guidance

```python
def get_grade(average):
    """Return a letter grade based on average percentage."""
    if average >= 70:
        return "A"
    elif average >= 60:
        return "B"
    elif average >= 50:
        return "C"
    elif average >= 40:
        return "D"
    else:
        return "U"

def get_valid_score(subject):
    """Ask for a score and keep asking until a valid number is entered."""
    while True:
        try:
            score = float(input(f"Enter score for {subject} (0-100): "))
            if 0 <= score <= 100:
                return score
            else:
                print("Score must be between 0 and 100.")
        except ValueError:
            print("Please enter a number.")

def calculate_results():
    """Collect scores and display results."""
    name = input("Student name: ")
    subjects = ["Maths", "English", "Science"]
    scores = {}
    
    for subject in subjects:
        scores[subject] = get_valid_score(subject)
    
    average = sum(scores.values()) / len(scores)
    grade = get_grade(average)
    
    print(f"\n=== Results for {name} ===")
    for subject, score in scores.items():
        print(f"  {subject}: {score:.1f}")
    print(f"Average: {average:.1f}%")
    print(f"Grade: {grade}")

calculate_results()
```

> 💡 Notice the `try/except` block — this is **error handling**. It prevents the program from crashing if someone types "hello" instead of a number.

### ⭐ Challenge extension
Allow the user to enter scores for multiple students. Store all results in a list of dictionaries and display a summary table at the end showing all students ranked by average.

---

## Project 5 ⭐⭐⭐ — OOP Bank Account

**Skills covered:** Classes, objects, OOP principles, methods  
**File to create:** `bank_account.py`

### What it should do:
A simple bank account simulation using a class. The user can deposit money, withdraw money (with a check for sufficient funds), and check their balance.

### Guidance

```python
class BankAccount:
    """A simple bank account class."""
    
    def __init__(self, owner, initial_balance=0):
        """Set up the account with an owner name and starting balance."""
        self.owner = owner
        self.balance = initial_balance
        self.transactions = []
    
    def deposit(self, amount):
        """Add money to the account."""
        if amount > 0:
            self.balance += amount
            self.transactions.append(f"Deposit: +£{amount:.2f}")
            print(f"Deposited £{amount:.2f}. New balance: £{self.balance:.2f}")
        else:
            print("Deposit amount must be positive.")
    
    def withdraw(self, amount):
        """Remove money from the account if funds are available."""
        if amount <= 0:
            print("Withdrawal amount must be positive.")
        elif amount > self.balance:
            print(f"Insufficient funds. Balance is only £{self.balance:.2f}")
        else:
            self.balance -= amount
            self.transactions.append(f"Withdrawal: -£{amount:.2f}")
            print(f"Withdrew £{amount:.2f}. New balance: £{self.balance:.2f}")
    
    def show_balance(self):
        """Display the current balance."""
        print(f"\nAccount holder: {self.owner}")
        print(f"Current balance: £{self.balance:.2f}")
    
    def show_history(self):
        """Display all transactions."""
        print(f"\n=== Transaction History for {self.owner} ===")
        for t in self.transactions:
            print(f"  {t}")
        print(f"  Current balance: £{self.balance:.2f}")


# --- Using the class ---
def main():
    name = input("Enter account holder name: ")
    opening = float(input("Enter opening balance: £"))
    
    account = BankAccount(name, opening)
    
    while True:
        print("\n1. Deposit")
        print("2. Withdraw")
        print("3. Check balance")
        print("4. View history")
        print("5. Exit")
        
        choice = input("Choose: ")
        
        if choice == "1":
            amount = float(input("Amount to deposit: £"))
            account.deposit(amount)
        elif choice == "2":
            amount = float(input("Amount to withdraw: £"))
            account.withdraw(amount)
        elif choice == "3":
            account.show_balance()
        elif choice == "4":
            account.show_history()
        elif choice == "5":
            print("Thank you for banking with us.")
            break

main()
```

### ⭐ Challenge extension
Create a second class `SavingsAccount` that *inherits* from `BankAccount` but adds an interest rate. Add a method `apply_interest()` that increases the balance by the interest rate percentage.

---

## File Handling and Database Projects — Thonny Only

> ⚠️ **Note:** The following two projects use file handling and SQLite databases. These **must be written and run in Thonny** on your school computer due to how these features work. Once complete, upload the finished `.py` files to your GitHub repository.

---

## Project 6 ⭐⭐ — Contact Book with File Saving *(Thonny)*

**Skills covered:** File handling, reading/writing text files, functions  
**File to create:** `contact_book.py`

### What it should do:
A contact book that saves names and phone numbers to a text file. Each time you run the program, it loads existing contacts from the file.

```python
import os

FILENAME = "contacts.txt"

def load_contacts():
    """Load contacts from file. Return empty list if file doesn't exist."""
    contacts = []
    if os.path.exists(FILENAME):
        with open(FILENAME, "r") as f:
            for line in f:
                parts = line.strip().split(",")
                if len(parts) == 2:
                    contacts.append({"name": parts[0], "phone": parts[1]})
    return contacts

def save_contacts(contacts):
    """Save all contacts to file."""
    with open(FILENAME, "w") as f:
        for c in contacts:
            f.write(f"{c['name']},{c['phone']}\n")
    print("Contacts saved.")

def add_contact(contacts):
    name = input("Name: ")
    phone = input("Phone: ")
    contacts.append({"name": name, "phone": phone})
    save_contacts(contacts)

def view_contacts(contacts):
    if not contacts:
        print("No contacts saved.")
        return
    print("\n=== Contacts ===")
    for i, c in enumerate(contacts, 1):
        print(f"{i}. {c['name']} — {c['phone']}")

def main():
    contacts = load_contacts()
    print(f"Loaded {len(contacts)} contact(s).")
    
    while True:
        print("\n1. View contacts  2. Add contact  3. Exit")
        choice = input("Choose: ")
        if choice == "1":
            view_contacts(contacts)
        elif choice == "2":
            add_contact(contacts)
        elif choice == "3":
            break

main()
```

---

## Project 7 ⭐⭐⭐ — Student Records Database *(Thonny)*

**Skills covered:** SQLite, database integration, SQL queries  
**File to create:** `student_records.py`

### What it should do:
A program that stores student names and scores in an SQLite database. Users can add records, view all records, and search by name.

```python
import sqlite3

def create_database():
    """Create the database and table if they don't exist."""
    conn = sqlite3.connect("students.db")
    cursor = conn.cursor()
    cursor.execute("""
        CREATE TABLE IF NOT EXISTS students (
            id INTEGER PRIMARY KEY AUTOINCREMENT,
            name TEXT NOT NULL,
            score REAL NOT NULL
        )
    """)
    conn.commit()
    conn.close()

def add_student(name, score):
    conn = sqlite3.connect("students.db")
    cursor = conn.cursor()
    cursor.execute("INSERT INTO students (name, score) VALUES (?, ?)", (name, score))
    conn.commit()
    conn.close()
    print(f"Added {name} with score {score}.")

def view_all_students():
    conn = sqlite3.connect("students.db")
    cursor = conn.cursor()
    cursor.execute("SELECT id, name, score FROM students ORDER BY score DESC")
    rows = cursor.fetchall()
    conn.close()
    
    if not rows:
        print("No records found.")
        return
    
    print("\n=== All Students ===")
    print(f"{'ID':<5} {'Name':<20} {'Score':<10}")
    print("-" * 35)
    for row in rows:
        print(f"{row[0]:<5} {row[1]:<20} {row[2]:<10}")

def search_student(name):
    conn = sqlite3.connect("students.db")
    cursor = conn.cursor()
    cursor.execute("SELECT * FROM students WHERE name LIKE ?", (f"%{name}%",))
    results = cursor.fetchall()
    conn.close()
    
    if not results:
        print(f"No student found with name '{name}'.")
    else:
        for r in results:
            print(f"ID: {r[0]}, Name: {r[1]}, Score: {r[2]}")

def main():
    create_database()
    
    while True:
        print("\n=== Student Records ===")
        print("1. View all  2. Add student  3. Search  4. Exit")
        choice = input("Choose: ")
        
        if choice == "1":
            view_all_students()
        elif choice == "2":
            name = input("Name: ")
            score = float(input("Score: "))
            add_student(name, score)
        elif choice == "3":
            name = input("Search name: ")
            search_student(name)
        elif choice == "4":
            break

main()
```

> 💡 Run this in Thonny. A file called `students.db` will be created in the same folder as your script. Upload `student_records.py` to GitHub — you do not need to upload the `.db` file.

---

---

# PART 4 — Adding a Jupyter Notebook

A Jupyter Notebook lets you mix code, output, and explanations in one document. They are widely used in data science and academic research — great to have in your portfolio.

## Step 4.1 — Create a Notebook File in github.dev

1. Open your repository in github.dev
2. In the left file panel, right-click and choose **New File**
3. Name it `data_exploration.ipynb`

## Step 4.2 — Paste the Notebook Content

Jupyter notebooks are stored as JSON. Copy the content below exactly into your new file:

```json
{
 "nbformat": 4,
 "nbformat_minor": 5,
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "name": "python",
   "version": "3.10.0"
  }
 },
 "cells": [
  {
   "cell_type": "markdown",
   "id": "a1",
   "metadata": {},
   "source": [
    "# Data Exploration with Python\n",
    "\n",
    "**Author:** Your Name  \n",
    "**Course:** Python for STEM — Bishop's Stortford College\n",
    "\n",
    "This notebook demonstrates basic data analysis using Python lists and built-in functions.\n",
    "No external libraries are needed — this is pure Python.\n",
    "\n",
    "---"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "a2",
   "metadata": {},
   "source": [
    "## 1. Creating a Dataset\n",
    "\n",
    "We'll create a simple dataset of student scores to explore."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "b1",
   "metadata": {},
   "outputs": [],
   "source": [
    "# A sample dataset: student names and their test scores\n",
    "students = [\n",
    "    {\"name\": \"Alice\",   \"score\": 78},\n",
    "    {\"name\": \"Bob\",     \"score\": 65},\n",
    "    {\"name\": \"Charlie\", \"score\": 92},\n",
    "    {\"name\": \"Diana\",   \"score\": 54},\n",
    "    {\"name\": \"Edward\",  \"score\": 83},\n",
    "    {\"name\": \"Fiona\",   \"score\": 71},\n",
    "    {\"name\": \"George\",  \"score\": 88},\n",
    "    {\"name\": \"Hannah\",  \"score\": 61}\n",
    "]\n",
    "\n",
    "print(f\"Dataset contains {len(students)} students.\")"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "a3",
   "metadata": {},
   "source": [
    "## 2. Basic Statistics\n",
    "\n",
    "Let's calculate some summary statistics from the scores."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "b2",
   "metadata": {},
   "outputs": [],
   "source": [
    "# Extract just the scores into a list\n",
    "scores = [s[\"score\"] for s in students]\n",
    "\n",
    "# Calculate statistics\n",
    "total    = sum(scores)\n",
    "count    = len(scores)\n",
    "average  = total / count\n",
    "highest  = max(scores)\n",
    "lowest   = min(scores)\n",
    "\n",
    "print(f\"Number of students : {count}\")\n",
    "print(f\"Average score      : {average:.1f}\")\n",
    "print(f\"Highest score      : {highest}\")\n",
    "print(f\"Lowest score       : {lowest}\")\n",
    "print(f\"Range              : {highest - lowest}\")"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "a4",
   "metadata": {},
   "source": [
    "## 3. Assigning Grades\n",
    "\n",
    "Using the grade boundaries from the Grade Calculator project."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "b3",
   "metadata": {},
   "outputs": [],
   "source": [
    "def get_grade(score):\n",
    "    \"\"\"Return a letter grade for a given score.\"\"\"\n",
    "    if score >= 70:\n",
    "        return \"A\"\n",
    "    elif score >= 60:\n",
    "        return \"B\"\n",
    "    elif score >= 50:\n",
    "        return \"C\"\n",
    "    elif score >= 40:\n",
    "        return \"D\"\n",
    "    else:\n",
    "        return \"U\"\n",
    "\n",
    "print(f\"{'Name':<12} {'Score':<8} {'Grade'}\")\n",
    "print(\"-\" * 26)\n",
    "for student in students:\n",
    "    grade = get_grade(student[\"score\"])\n",
    "    print(f\"{student['name']:<12} {student['score']:<8} {grade}\")"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "a5",
   "metadata": {},
   "source": [
    "## 4. Your Turn — Extend This Notebook\n",
    "\n",
    "Add a new code cell below and try the following:\n",
    "\n",
    "- Count how many students got each grade (A, B, C, D, U)\n",
    "- Find the name of the student with the highest score\n",
    "- Calculate the median score (sort the list first, then find the middle value)\n",
    "\n",
    "**Hint for median:**\n",
    "```python\n",
    "sorted_scores = sorted(scores)\n",
    "mid = len(sorted_scores) // 2\n",
    "median = sorted_scores[mid]\n",
    "```"
   ]
  }
 ]
}
```

3. Commit this file with the message: `Add data exploration notebook`

> 💡 GitHub will render this notebook directly — anyone visiting your repository can read it without running any code.

---

---

# PART 5 — Polishing Your Portfolio

## Step 5.1 — Create a Folder Structure

A well-organised repository looks professional. In github.dev, create the following folders by creating files inside them (GitHub doesn't allow empty folders).

**Recommended structure:**

```
python-stem-portfolio/
│
├── README.md                  ← Your portfolio front page
│
├── projects/
│   ├── unit_converter.py
│   ├── guessing_game.py
│   ├── todo_list.py
│   ├── grade_calculator.py
│   ├── bank_account.py
│   ├── contact_book.py        ← uploaded from Thonny
│   └── student_records.py     ← uploaded from Thonny
│
└── notebooks/
    └── data_exploration.ipynb
```

To create a subfolder in github.dev, right-click in the file panel and choose **New Folder**.

---

## Step 5.2 — Update Your README with Links

Once your files are in the `projects/` folder, update your README table to link directly to each file. The link format is:

```markdown
[Unit Converter](projects/unit_converter.py)
```

---

## Step 5.3 — Write a Reflection Comment for Each Project

For each `.py` file, add a comment block at the very top explaining what the program does and what you learnt. This shows employers and universities that you understand your own work.

**Template — paste this at the top of each file and fill it in:**

```python
"""
==============================================
 Project: Unit Converter
 Author:  [Your Name]
 Date:    [Month Year]
 Course:  Python for STEM — BSC
==============================================
 Description:
     A program that converts between common units of measurement,
     including distance, temperature, and weight.

 Skills demonstrated:
     - Defining and calling functions
     - User input and output with f-strings
     - If/elif/else conditional logic
     - Type conversion (str to float)

 What I found challenging:
     [Write one sentence about something you had to figure out]

 What I would add next:
     [Write one thing you'd improve or extend if you had more time]
==============================================
"""
```

---

## Step 5.4 — Final Checklist

Before sharing your portfolio link, check each item:

- [ ] README displays correctly with your name and a short bio
- [ ] All 5+ projects are uploaded and accessible
- [ ] Each `.py` file has a header comment block
- [ ] Notebook is in the `notebooks/` folder and renders on GitHub
- [ ] README table has working links to each project file
- [ ] Repository is set to **Public**
- [ ] Username is professional

---

---

# 🎓 Portfolio Complete — What's Next?

## Sharing Your Portfolio

Your portfolio URL is:  
`https://github.com/your-username/python-stem-portfolio`

This link can go on:
- Your UCAS personal statement ("evidence of independent coding projects")
- Your CV in an "Additional Skills" or "Projects" section
- University application forms that ask about technical experience

## Going Further (Optional Extensions)

If you have completed all projects and want to go further:

| Extension | Skill developed |
|---|---|
| Add a second notebook analysing real data (e.g. weather data from a CSV) | Data analysis, file handling |
| Rewrite the To-Do List using a class | OOP applied to a real project |
| Add a `requirements.txt` file listing any libraries you used | Professional software practice |
| Write a `REFLECTION.md` file summarising what you have learnt across the course | Communication and self-assessment |

---

*Resource created for Bishop's Stortford College — Python for STEM, Year 12*
