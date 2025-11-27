# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
class A:
    
    def __init__(self,a):
    
        self.a=a
class B:

    def __init__(self,b):
    
        self.b=b
class sol(A,B):
    
    def __init__(self,a,b):
        
        A.__init__(self,a)
    
        B.__init__(self,b)
    def res(self):
    
        print(self.a+self.b)
        
        print(self.a*self.b)
        
        print(self.a/self.b)
        
a=int(input())

b=int(input())

sol=sol(a,b)

sol.res()
## Output Example
<img width="801" height="206" alt="image" src="https://github.com/user-attachments/assets/d260d0b3-5fe3-4c74-a423-1585aa2f29f2" />

## Result

Thus, the program has been successfully executed.
