# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program
class details:
    
    def __init__(self,a,b,c,d,e):
    
        self.a=a
        
        self.b=b
        
        self.c=c
        
        self.d=d
        
        self.e=e
        
class Employee(details):
    
    def __init__(self,a,b,c,d,e):
    
        details.__init__(self,a,b,c,d,e)
    
    def emp(self):
    
        print("Employee Object")
        
        print(f"Id:  {self.a}")
        
        print(f"Name:  {self.b}")
        
        print(f"Gender:  {self.c}")
        
        print(f"Company:  {self.d}")
        
        print(f"Department:  {self.e}")
        
class patient(details):

    def __init__(self,a,b,c,d,e):
    
        details.__init__(self,a,b,c,d,e)
    
    def pat(self):
    
        print("Patient Object")
        
        print(f"Id:  {self.a}")
        
        print(f"Name:  {self.b}")
        
        print(f"Gender:  {self.c}")
        
        print(f"Hospital:  {self.d}")
        
        print(f"Department:  {self.e}")


a=int(input())

b=input()

c=input()

d=input()

e=input()

l=int(input())

m=input()

n=input()

o=input()

p=input()

employee=Employee(a,b,c,d,e)

patient=patient(l,m,n,o,p)

employee.emp()

print()

patient.pat()
## Sample Output
<img width="801" height="448" alt="image" src="https://github.com/user-attachments/assets/4766fb8e-011d-40c0-9364-8ef2fe848305" />
## Result

Thus, the program has been successfully executed.
