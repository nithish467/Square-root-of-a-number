# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
## Program to find the square root for the given number(newton's method) using function.
## Developed by: NITHISH KUMAR S
## RegisterNumber: 23013506
```
n=int(input())
a=0.5*n
b=0.5*(a+n/a)
while b!=a:
    a=b
    b=0.5*(a+n/a)
print("Square root of the number:",b)

```

## Output:
![Square root of a number](https://github.com/nithish467/Square-root-of-a-number/assets/150232274/4aab4039-9f39-4f19-8cf7-67ba01185a7c)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
