# Day 2
> 22 September 2022, 16min
### Working on:
- [Scientific Computing with Python on FreeCodeCamp](https://www.freecodecamp.org/learn/scientific-computing-with-python)

### What I learned:
1. Variables
2. Types
3. Conversion between types
4. User input
5. Comments
6. If-Elif-Else Conditionals
7. Try-Except Conditionals
8. F-Strings

### Programs I made:
#### Division Calculator
```python
print("Division Calculator")
num1 = input("Number 1: ")
num2 = input("Number 2: ")
ans = int(num1) / int(num2)
print(ans)
```

#### Calculator
```python
print("Calculator")
operator = input("Operation (+ or - or * or /): ")
num1 = int(input("Number: "))
num2 = int(input("Number: "))
if operator == "+":
    ans = num1 + num2
elif operator == "-":
    ans = num1 - num2
elif operator == "*":
    ans = num1 * num2
elif operator == "/":
    ans = num1 / num2
else:
    print("Invalid operation")
print(f"{num1} {operator} {num2} = {ans}")
```
