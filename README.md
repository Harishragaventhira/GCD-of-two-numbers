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
Developed by: harish
RegisterNumber: 23013571 
*/
def gcd():
    n=int(input())
    m=int(input())
    if n>m:
        s=m
    else:
        s=n
    for i in range (1,s+1):
        if(n%i==0 and m%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)
```
## Output:
![image](https://github.com/Harishragaventhira/GCD-of-two-numbers/assets/145548269/50547ab3-d0f3-45eb-902f-abfe378557d1)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
