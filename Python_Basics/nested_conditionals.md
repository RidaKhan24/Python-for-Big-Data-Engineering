# Nested Conditional Statements

## What is Nested IF?

When one if statement is written inside another if statement, it is called nested if.

## Example

age = 20
citizen = True

if age >= 18:
    if citizen == True:
        print("You can vote")
    else:
        print("You are not a citizen")
else:
    print("You are underage")

## Explanation

- First condition checks age  
- If age is valid, inner condition checks citizenship  
- Decision is taken based on both conditions  

Nested conditions are useful when multiple levels of checking are required.
