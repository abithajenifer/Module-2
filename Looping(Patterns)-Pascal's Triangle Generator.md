![WhatsApp Image 2026-03-26 at 6 22 38 PM](https://github.com/user-attachments/assets/3cc66815-6db9-4160-8e61-d359c230a4c8)# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

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
Add Code Here
~~~
rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()
~~~

## Sample Output

![WhatsApp Image 2026-03-26 at 6 23 41 PM](https://github.com/user-attachments/assets/48874c30-4bed-4c09-8285-9f50faf915d9)

## Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.

