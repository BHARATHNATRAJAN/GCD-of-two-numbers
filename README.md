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
#To find GCDof a number
#Developed by : Bharath.N
#Referance number : 23003413

def gcd():
    a=int(input())
    b=int(input())
    while b:
        a,b=b,a%b
    print ("GCD of two numbers is:",a)
```

## Output:
![gcd](https://github.com/BHARATHNATRAJAN/GCD-of-two-numbers/assets/147473529/bbaa4e2a-5ee7-4d97-a8e1-1bdb2e9a0df9)

![output](https://github.com/BHARATHNATRAJAN/GCD-of-two-numbers/assets/147473529/9526756d-de97-48ac-a099-26b0e7809082)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
