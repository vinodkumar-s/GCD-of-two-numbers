# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step1
Define a function.
## step2
Get the two numbers from the user.
## step3
Compare the two values, to find the smaller number.
## step4
Use for() and if() loop to find the GCD of the two numbers.

## Program:
Program to find the gcd of a number using function.

 Developed by:s.vinod kumar
 
 RegisterNumber:22004903
 
``` python
def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n1
    for i in range(1, smaller+1):
        if(n1%i==0 and n2%i==0):
            gcd1=i
    print("GCD of two numbers is:",gcd1)
```


## Output:
![gcd of two number](/output.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
