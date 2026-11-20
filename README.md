# Python for Beginners 🐍

This repository contains a collection of source code and documentation from learning the fundamentals of Python programming.

## 📚 Summary of Topics Learned

Based on the project structure, here are the core Python topics that have been studied and practiced:

1. **Initialization & Workspace Setup (`hello.py`, `pip.py`)**
   - Introduction to basic Python syntax (`print()`) and executing the first program.
   - Setting up the IDE (PyCharm), creating a *Virtual Environment* (`venv`), and managing packages using `pip`.
2. **Variables (`variable.py`)**
   - Declaring, storing, and manipulating values in variables, along with understanding basic data types (String, Integer, Float, Boolean).
3. **Operators (`operators.py`)**
   - Using arithmetic, comparison, assignment, and logical operators to perform operations on data.
4. **Conditionals (`if_elif.py`)**
   - Decision-making and program flow control using `if`, `elif`, and `else` statements.
5. **Looping (`looping.py`)**
   - Executing blocks of code repeatedly using `for` and `while` loops.
6. **Data Structures (`list_and_dicionaries.py`)**
   - Managing collections of data using collective data types such as `List` (ordered collections) and `Dictionary` (*key-value* pairs).
7. **Functions (`function.py`)**
   - Creating structured and reusable blocks of code using the `def` keyword, parameters, and return values (`return`).
8. **Object-Oriented Programming / OOP (`class_and_object.py`)**
   - Introduction to basic OOP concepts through creating a `Class` (blueprint) and instantiating an `Object`.

## 📂 Directory Structure

```text
python-untuk-pemulaa/
├── python-untuk-pemula/       # Main source code directory
│   ├── class_and_object.py    # Class & Object exercises
│   ├── function.py            # Function exercises
│   ├── hello.py               # Hello World program
│   ├── if_elif.py             # Conditional exercises
│   ├── list_and_dicionaries.py# List & Dictionary exercises
│   ├── looping.py             # Looping exercises
│   ├── operators.py           # Operator exercises
│   ├── pip.py                 # PIP verification script
│   └── variable.py            # Variable exercises
├── screenshot/                # Execution output screenshots
├── venv/                      # Python virtual environment
├── .gitignore                 # Files/folders ignored by Git
├── README.md                  # Project documentation
└── requirements.txt           # Project dependencies list
```

## 🚀 How to Run the Programs

Follow these steps to run the programs on your local machine:

1. **Clone this repository** (if downloading from GitHub):
   ```bash
   git clone https://github.com/Dizannputra/python-untuk-pemulaa.git
   cd python-untuk-pemulaa
   ```

2. **Activate the Virtual Environment (`venv`)**:
   - **Windows (Command Prompt / PowerShell):**
     ```bash
     venv\Scripts\activate
     ```
   - **Linux / macOS:**
     ```bash
     source venv/bin/activate
     ```

3. **Install Dependencies** (optional if external libraries are added later):
   ```bash
   pip install -r requirements.txt
   ```

4. **Run a Python Program**:
   Execute any of the desired topic files directly from the root directory:
   ```bash
   python python-untuk-pemula/hello.py
   ```
   *(Replace `hello.py` with any other file name you wish to run, such as `variable.py` or `function.py`).*