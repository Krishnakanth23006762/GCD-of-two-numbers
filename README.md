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
```python
# GCD of Two Numbers
#B.KRISHNAKANTH
#23006762
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n1
    for i in range(1,smaller+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)
```

## Output:
![image](https://github.com/Krishnakanth23006762/GCD-of-two-numbers/assets/138849446/0132ecc9-a1d0-441a-b430-6fbc24a9d1d9)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
