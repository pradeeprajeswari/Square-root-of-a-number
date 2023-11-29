# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

## STEP1:
Define a function.

## STEP2:
Assign number_iters = 100 in the function to perform 100 iteratios.

## STEP3:
Set i = 0.

## STEP4:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.

## STEP5:
Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: PRADEEP.E
RegisterNumber: 23013416

def newton_method (number , number_iters = 100):
    a = float (number)
    for i in range(number_iters):
        number =0.5*(number + a / number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
*/
```

## Output:
![gcd of two number](gcd.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
