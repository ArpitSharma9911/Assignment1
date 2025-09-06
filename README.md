# Assignment1
This repository contains Python scripts for basic programming practice.  

## 📌 Task 1: Perform Basic Mathematical Operations  

### Problem Statement:  
Write a Python program that:  
1. Takes two numbers as input from the user.  
2. Performs the following operations:  
   - Addition  
   - Subtraction  
   - Multiplication  
   - Division

**#Code**
a= float (input ("Enter first number: "))
b= float (input ("Enter second number: "))
c= a+b
d=a-b
e=a*b
f=a/b
print("Addition is=", c)
print("Subtraction is=", d)
print("Multiplication is=", e)
print("Division is=", f)

### Example Output:  
Enter first number: 10
Enter second number: 5

Results:
Addition is=15.0
Subtraction is=5.0
Multiplication is=50.0
Division is=2.0


## 📌 Task 2: Personalized Greeting  

### Problem Statement:  
Write a Python program that:  
1. Takes a user's first name and last name as input.  
2. Concatenates the first name and last name into a full name.  
3. Prints a personalized greeting message using the full name.

**#Code**
firstname=input("Enter your first name: ")
lastname=input("Enter your last name: ")
fullname=firstname+" "+lastname
print ("Hello,"+fullname+"! Welcome to Python programming. ")

### Example Output:  
Enter your first name: Arpit
Enter your last name: Sharma
Hello,Arpit Sharma! Welcome to Python programming. 

