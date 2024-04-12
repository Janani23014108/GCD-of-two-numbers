## Find the GCD of two numbers
Name:J.JANANI

Register no:212223230085

Department:B.Tech AIDS

## AIM:

To write a program to find the GCD of two numbers using function.

## Equipments Required:

1.Hardware – PCs

2.Anaconda – Python 3.7 Installation / Moodle-Code Runner


## Algorithm
**step 1:**

Define a function.

**step 2:**

Get the two numbers from the user.

**step 3:**

Compare the two values, to find the smaller number.

**step 4:** 

Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: J.JANANI
RegisterNumber:  212223230085
*/
def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller = n2
    else:
        smaller = n1
    for i in range (1,smaller+1):
        if(n1%i==0 and n2%i==0):
           hcf=i
    print("GCD of two numbers is:",hcf)
```

## Output:

![python 4th](https://github.com/Janani23014108/GCD-of-two-numbers/assets/146822085/b6b5bff8-1137-4351-a023-3e155fa943ca)




## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
