# AIM: Study of Conditional Statements in Python
## Objective
To understand and implement different types of **conditional statements** in Python and solve various decision-making problems using them.
## THEORY:
## Conditional Statements in Python

### 1. if statement
Used when we want to execute a block of code only if a condition is true.

Syntax:  
if condition:  
    statement(s)

### 2. if-else statement
Executes one block if condition is true, another block if false.

Syntax:  
if condition:  
    statement(s)  
else:  
    statement(s)

### 3. if-elif-else statement
Used when we need to check multiple conditions in sequence.

Syntax:  
if condition1:  
    statement(s)  
elif condition2:  
    statement(s)  
else:  
    statement(s)

### 4. Nested if statements
if statement inside another if statement (used for more complex conditions)

## Important Concepts Used
- Comparison operators: >, <, >=, <=, ==, !=
- Logical operators: and, or, not
- Membership operators: in, not in (used less in this experiment)
- Modulus operator (%) => to check even/odd, divisibility
- Input type conversion => int(input(...))
- Multiple conditions using and / or

## Problems Covered in the Experiment

### 1. Check whether a number is positive or negative
- Input: any number
- Output: tells whether it is positive or negative

### 2. Check whether a number is positive, negative or zero
- Uses if-elif-else
- Handles three possible cases

### 3. Check whether a number is even or odd
- Uses modulus operator (%)
- If number % 2 == 0 => even
- Else => odd

### 4. Find the largest of two numbers
- Compares two numbers using if-else
- Prints which one is greater (or smaller)

### 5. Find the largest among three numbers
- Uses multiple conditions with and operator
- Compares all three numbers step-by-step

### 6. Calculate average of 5 subjects and assign grade
- Takes marks of 5 subjects
- Calculates average
- Assigns grade using if-elif-else ladder:
  - 95  =>O grade
  - 85 =>A grade
  - 75 => B grade
  - 65 => C grade
  - else => Fail

### 7. Check whether a year is a leap year
- A year is leap if:
  - divisible by 4 AND not divisible by 100, OR
  - divisible by 400
- Uses logical OR and AND operators

### 8. Validate a date and print next date
- Input date in dd/mm/yyyy format
- Checks:
  - valid month (1–12)
  - valid number of days in month
  - handles February (28 or 29 days in leap year)
- If valid => prints next day (increments date correctly)
- If invalid => prints "Invalid date"

### 9. Calculate gross salary of an employee
- Input: basic salary
- Calculates HRA and DA based on basic salary slabs:
  - ≤ 10000 => HRA 20%, DA 80%
  - ≤ 20000 => HRA 25%, DA 90%
  - > 20000 => HRA 30%, DA 95%
- Gross salary = basic + HRA + DA

## Conclusion
Conditional statements (if, elif, else) form the foundation of decision-making in programming.  
They allow the program to:
- make choices
- handle different cases
- validate input
- perform calculations based on conditions
