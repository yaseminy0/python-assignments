# python-assignments
Introductory Python assignments covering variables, conditionals, loops, and functions.
## Topics Covered
- Variables and Data Types
- Boolean Expressions
- If Statements and Conditional Logic
- Loops (for & while)
- Functions
- Basic Problem Solving

## Structure
- **Week 1:** Variables and simple calculations  
- **Week 2:** Boolean expressions and conditionals  
- **Week 3:** Loops and iterations  
- **Week 4:** Functions and basic applications  

## Example Code
```python
# Program to check if a year is a leap year
year = 2024
if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(year, "is a leap year")
else:
    print(year, "is not a leap year")
