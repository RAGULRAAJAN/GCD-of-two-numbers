# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: RAGUL RAAJAN T
RegisterNumber: 212223100043     
*/


def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
        a,b=b,a%b
    print("GCD of two numbers is:",a)


```

## Output:
![Screenshot 2024-03-16 093551](https://github.com/RAGULRAAJAN/GCD-of-two-numbers/assets/147473144/95b7081b-ccee-4c21-af2a-1a81d3fe7f0b)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
