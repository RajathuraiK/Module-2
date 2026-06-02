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
