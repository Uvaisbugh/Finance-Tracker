# Personal Finance Tracker

A simple Python program for tracking personal finances, including income and expenses. The program allows the user to record financial entries by specifying the date, amount, category (Income or Expense), and an optional description.

---

## Features

1. **Add Financial Records:**
   - Records income or expenses with date, amount, category, and description.

2. **Input Validations:**
   - Ensures date format is `dd-mm-yyyy`.
   - Ensures amount is a positive, non-zero value.
   - Accepts only valid categories (`I` for Income and `E` for Expense).

3. **Defaults for Convenience:**
   - Allows default date (`today's date`) if no input is provided.

---

## Functions

### 1. `get_date(prompt, allow_default=False)`
- **Purpose:** Prompts the user to input a date.
- **Parameters:**
  - `prompt`: Message to display to the user.
  - `allow_default`: If `True`, defaults to today's date if no input is provided.
- **Returns:** A valid date in the format `dd-mm-yyyy`.

---

### 2. `get_amount()`
- **Purpose:** Prompts the user to input a valid amount.
- **Validations:**
  - Ensures the amount is a non-negative, non-zero value.
- **Returns:** The entered amount as a `float`.

---

### 3. `get_category()`
- **Purpose:** Prompts the user to select a category for the transaction.
- **Options:**
  - `'I'` for Income.
  - `'E'` for Expense.
- **Returns:** The selected category as a string (`"Income"` or `"Expense"`).

---

### 4. `get_description()`
- **Purpose:** Prompts the user to enter an optional description for the transaction.
- **Returns:** The entered description as a string.

---

## How to Run

1. **Clone or Download:**
   Download this repository to your local machine.

2. **Requirements:**
   - Python 3.x must be installed.
   - No additional libraries are required (uses Python's standard library).

3. **Run the Code:**
   ```bash
   python finance_tracker.py
