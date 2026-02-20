# Assignment 2 – Control Structures

This folder contains Python programs developed as part of **Assignment 2**, focusing on the use of control structures such as conditional statements and loops.

---

## Task 1: Check if a Number is Even or Odd

### Problem Statement
Write a Python program that:
1. Takes an integer input from the user.
2. Checks whether the number is even or odd using an if-else statement.
3. Displays the result accordingly.

### Code
```python
num = int(input("Enter a number: "))
if (num % 2) == 0:
    print(num, "is an even number")
else:
    print(num, "is an odd number")
```
Output:
(Odd number scenario)
Enter a number: 7
7  is an odd number

(Even number scenario)
Enter a number: 12
12  is an even number

## Task 2: Sum of Integers from 1 to 50 Using a Loop
 
### Problem Statement:
Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.

### Code:
```python
sum_of_num = 0
for i in range(0,51):
    sum_of_num += i
print("The sum of numbers from 1 to 50 is ",sum_of_num)
```
Output:
The sum of numbers from 1 to 50 is  1275
