# Ex 1 Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

```
a=16
res=bin(a)
print(res)
```

## Output

<img width="718" height="291" alt="image" src="https://github.com/user-attachments/assets/51035031-b722-4b25-9eba-314e79b42e56" />

## Result

The python program to convert a number **16**  into its **binary representation** using built-in Python functions is successfully executed.

# Ex 2 Functions in Python: Modulo Calculator

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
def result(a,b):
    res=a%b
    print(res)
a=int(input())
b=int(input())
result(a,b)
```

## Output

<img width="661" height="391" alt="image" src="https://github.com/user-attachments/assets/ec62f23f-946d-4d12-a1f8-31341cd08007" />

## Result

The Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator is successfully executed.

# Ex 3 Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program

```
a=int(input())
b=int(input())
f = lambda a,b: a+b
print(f(a,b))
```

## Output

<img width="912" height="346" alt="image" src="https://github.com/user-attachments/assets/89e21892-293e-488d-8556-0a4ee9934738" />

## Result

The Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum is successfully executed.

# 🔺 Ex 4 Looping(Patterns)-Pascal's Triangle Generator in Python

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
import math
rows = int(input("Enter number of rows: "))
for i in range(rows):
    print(" " * (rows - i), end="")
    for j in range(i + 1):
        val = math.factorial(i)/(math.factorial(j)*math.factorial(i-j))
        print(int(val), end=" ")
    print()
```

## Sample Output

<img width="896" height="444" alt="image" src="https://github.com/user-attachments/assets/5b892d87-4270-4bc4-b15e-b107e52d0a90" />


## Result

The Python program that generates **Pascal's Triangle** using numbers is successfully executed.

## Ex 5 Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program

```
num=int(input())
temp=num
rev=0
while temp>0:
    rev=10*(rev) + temp%10
    temp//=10
if num==rev:
    print("The number is a Palindrome")
else:
    print("The number is not a Palindrome")
```
## Output

<img width="906" height="252" alt="image" src="https://github.com/user-attachments/assets/54c7038e-f86f-420c-a761-ae9fbf9b4eba" />

## Result

The Python program that checks whether a given number is a **palindrome** using loops is successfully executed.
