## NAME: DEEPAK.V
## REGISTER NO: 212225230044

## EX 1:Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
n = int(input())

if n % 2 == 0:
    print("Even")
else:
    print("Odd")
```
## Output

<img width="556" height="217" alt="{2EA91259-3C70-4E0A-8B65-A3E9DB09AB54}" src="https://github.com/user-attachments/assets/7f8a45ce-b7a8-480e-a073-579169609428" />

<img width="446" height="211" alt="{3E77CFCB-A746-4D4C-87EE-EF2525925206}" src="https://github.com/user-attachments/assets/37ed763d-5223-4b77-b624-3ca02532fc12" />

## Result
Thus, the Python program to check whether the given number is even or odd using if...else statements was successfully implemented and executed, and the result was verified.

## EX 2:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a = (0 == True)
b = (False == False)
c = (True + True)
d = (False + 9)

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```
## Output

<img width="487" height="223" alt="{F3F2E7F0-D58E-45C5-856D-0A297D8AF1C7}" src="https://github.com/user-attachments/assets/6cc22384-7f1d-48a2-9709-76e8879e62fe" />

## Result
Thus, the Python program to evaluate and print the results of boolean and arithmetic expressions involving True and False was successfully implemented and executed, and the results were verified.

## EX 3:Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
print('T')
print('a')
```
## Output

<img width="404" height="205" alt="{D51729B6-6A69-4966-9AF0-F26A34E977C2}" src="https://github.com/user-attachments/assets/cdfcd5de-96a2-4e35-a0f0-8857dc6664d1" />

## Result
Thus, the Python program to print the characters 'T' and 'a' using character literals was successfully implemented and executed, and the output was verified.

## EX 4:Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))

x = complex(a, b)

print(x)
print(x.real)
print(x.imag)
```
## Output

<img width="451" height="280" alt="{8EE010ED-714E-4C83-8AD6-0C47E63EFD87}" src="https://github.com/user-attachments/assets/48e27e0e-09de-4ccd-8173-9e10ad68e6b6" />

## Result
Thus, the Python program to create a complex number and display its real and imaginary parts was successfully implemented and executed, and the output was verified.

## EX 5:Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon = input("Enter a string: ")

print(men_stepped_on_the_moon)
```
## Output

<img width="455" height="246" alt="{FB11D454-0305-4DCA-9DD7-7FF21667FAF8}" src="https://github.com/user-attachments/assets/de67327e-031c-4c36-a208-8a61bd3b7132" />

## Result
Thus, the Python program to read a string from the user and print it was successfully implemented and executed, and the output was verified.
