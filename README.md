
odle-Code Runner

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


![python exp 4](https://github.com/Janani23014108/GCD-of-two-numbers/assets/146822085/b6f8ad43-a759-43af-9605-02536f7fcd16)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
