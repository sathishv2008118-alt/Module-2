# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def fact(n):
    f=1
    for i in range(1,n+1):
        f*=i
    return f
def strong(n):
    s=0
    temp=n
    while temp>0:
        d=temp%10
        s+=fact(d)
        temp//=10
    return s==n
number=int(input())
if strong(number):
    print(f"The number is a strong number")
else:
    print(f"The number is not a strong number")
```
## Output
<img width="991" height="290" alt="image" src="https://github.com/user-attachments/assets/1f161040-9e27-47ca-8052-47c701869e21" />


## Result
