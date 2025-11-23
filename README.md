
# Simple Banking System in Python

Project Overview: This is a simple banking system developed for the purposes of a Python beginner project. A user can see the balance, deposit money, withdraw funds, or exit the system using this program. It runs on a loop until the user decides to quit the system; hence, it's an interactive console-based application.


## Features

• Show current account balance

• Deposit money (with invalid amount check)

• Withdraw money (with insufficient balance check)

• Menu-driven interface

• Easy for first-year students
## Concepts Used:
• Functions

• Variables

• Loops (while)

• Conditional statements (if/elif/else)

• User input handling
## Deployment
### 1. Install Python
• Make sure Python 3 is installed on your system.

• You can download it from: https://www.python.org

### 2. Download the project file
• Save the Python script (e.g., banking_program.py) to your computer.

### 3. Open a Terminal / Command Prompt
• Windows: Open Command Prompt

• Mac/Linux: Open Terminal

### 4. Navigate to the Project Folder

```bash
  cd path/to/your/project
```

### 5. Run the Program

```bash
  python banking_program.py
```
• The menu will appear

• Follow the on-screen instructions



## Instructions for Testing

You can test the program manually using these steps:

### 1. Test Show Balance
• Start the program and press 1

• Should show the balance as $0.00 initially

### 2. Test Deposit
• Choose 2

• Please enter a valid amount (e.g., 100)

• Check that the balance increases

• Try entering a negative number → Program should reject it

### 3. Test Withdraw
• Choose 3

• Enter an amount less than or equal to the balance → Should work

• Enter an amount greater than the balance → Should display “Insufficient funds”

• Enter a negative amount → Should display “Amount must be greater than 0”

### 4. Test Invalid Menu Input
• Enter anything other than 1–4, for example 9 or a letter

• Program should indicate “That is not a valid choice”

### 5. Test Exit
• Press 4

• Program should terminate by displaying a good-bye message.
