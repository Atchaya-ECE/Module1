# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **odd** or **not anodd** using `nested if..else.` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`
3. Use the modulo operator `%` to check if `a % 2 == 1`.
   - If true, print `"Odd number"`.
   - Else, print `"Not an Odd number"`.
4. End the program.

## 🧾 Program
```
Developed by:Priya.B
Register.no:212224230208
a=int(input())
if a%2==1:
    if a>=25:
        print(f"{a} is an Odd number")
        print(f"{a} is greater than or equal to 25")
    else:
        print(f"{a} is an Odd number")
        print(f"{a} is lesser than 25")
else:
    print(f"{a} is NOT an Odd number")
```
## Output
.![Screenshot 2025-05-14 210516](https://github.com/user-attachments/assets/6ab63256-491c-4a4e-b184-b61d72ca5bbc)

## Result
Thus the program to check whether the given number is **odd** or **not anodd** using `nested if..else.` statements has been successfully executed.
