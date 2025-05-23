# 12 Finding Whether a Number is Prime Using a Recursive Function in Python

## Aim

Write a Python program to check if a given number is prime using recursion.

## Algorithm:

Start
Read the input number n.
Define a recursive function is_prime(n, i) where:
n is the number to check
i starts from 2 (the smallest prime divisor).
Base cases:
If n is less than 2, it is not prime.
If i is greater than sqrt(n), return True (no divisor found).
If n is divisible by i, return False.
Recursive case:
Call is_prime(n, i+1) to check the next possible divisor.
Use the recursive function to check the primality of n.
Print the result accordingly.
End


## Program

```
reg no:212223070023
name:Saran Krishna P S
def is_prime(n, i=2):
    if n <= 2:
        return n == 2
    if n % i == 0:
        return False
    if i * i > n:
        return True
    return is_prime(n, i + 1)
num = int(input())
if is_prime(num):
    print(f"{num} is a Prime number")
else:
    print(f"{num} is not a Prime number")



## OUTPUT

![image](https://github.com/user-attachments/assets/bc31e539-5185-4df5-94ab-b1f6380789ac)

## RESULT
thus the program is executed successfully.
