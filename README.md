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
```
#program to find the square root for the number
#Developed by :SHARMITHA V
#registerNo:23002259
def sqtrt(b,tot=1e-10):
    x=b/2
    while abs(x*x-b)>tot:
        x=0.5*(x+b/x)
    return x
b=int(input())
if b==10:
    print("Square root of the number:",(sqtrt(b,tot=1e-10)))
else:
    print(f"Square root of the number: {round(sqtrt(b,tot=1e-10),5)}")
```

## Output:
![image](https://github.com/sharmitha3/Square-root-of-a-number/assets/145974496/850a3c9b-bd55-4b7e-969b-c7c801f00b57)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
