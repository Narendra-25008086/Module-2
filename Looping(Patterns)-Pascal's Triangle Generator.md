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
Add Code Here
```
def pascal_triangle(n):
    for i in range(n):
        print(" "*(n-i-1),end="")
        val=1
        for j in range(i+1):
            print(val,end=" ")
            val=val*(i-j)//(j+1)
        print()
n=int(input())
pascal_triangle(n)
```


## Sample Output
![WhatsApp Image 2025-10-19 at 19 31 36_831fbaf4](https://github.com/user-attachments/assets/818e79d2-e43f-47e8-b1bd-0ba71c278922)




## Result
The Python program successfully takes the number of rows as input from the user and generates Pascal’s Triangle.


