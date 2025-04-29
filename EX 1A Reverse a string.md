# EX 1A Factorial Calculation using Recursion
## DATE:

## Aim
To write a Python program that calculates the factorial of a given number using recursion.

---

## Algorithm
1. Start the program.
2. Define a recursive function `factorial(n)`:
   - If `n` is 0 or 1, return 1.
   - Else, return `n * factorial(n - 1)`.
3. Take user input and convert it to an integer.
4. Check if the number is negative:
   - If yes, display a message that factorial is not defined for negative numbers.
   - If no, call the `factorial()` function and display the result.
5. End the program.

   ---

## Program
```python
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)  

num = int(input(""))

if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    print(f"Factorial of number {num} = {factorial(num)}")
```
---
## Output

![image](https://github.com/user-attachments/assets/c2aacc11-f5f2-40bb-ae89-384870275d85)

---

## Result 

The program was successfully executed and it correctly calculates the factorial of a given number using recursion.

