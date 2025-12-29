# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
rows=int(input())
num=1
for i in range(1,rows+1):
    for j in range(1,i+1):
        print(num,end=" ")
        num+=1
    print()
```
## Sample Output

<img width="880" height="651" alt="Screenshot 2025-12-29 123100" src="https://github.com/user-attachments/assets/bfffcfc0-47b7-48e2-ad00-b00a0683d3ad" />

## Result

