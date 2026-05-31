# PYTHON MODULE---1

### NAME : DEEPAK PRABHAKARAANN VB
### REFERENCE NUMBER : 212225060054
### DATE : 

# EXPERIMENT-1(A): PYTHON BASICS

## AIM
Write a python program to print the result of the following expression as true or false.

a = (False == True)

b = (False== 0)

c = False + True

d = False + 5

## ALGORITHM

- Start
- Evaluate Expression a: Compare the boolean False to True using the equality operator (==). Store the result.
- Evaluate Expression b: Compare the boolean False to the integer 0 using the equality operator (==). In Python, False is numerically equal to 0. Store the result.
- Evaluate Expression c: Add the boolean False (treated as 0) to True (treated as 1). Store the result.
- Evaluate Expression d: Add the boolean False (treated as 0) to the integer 5. Store the result. 
-Convert and Format: Convert the results of expressions c and d into boolean values using the bool() function so they print as True or False.
-Print Results: Display the final boolean outcomes for a, b, c, and d.
-End

## PROGRAM
```
a = (False == True)

b = (False== 0)

c = False + True

d = False + 5
print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
```

## OUTPUT
<img width="1146" height="244" alt="image" src="https://github.com/user-attachments/assets/d2d2f03f-2d7a-4fe6-ab7c-63a219912dd6" />

## RESULT 
Thus the python program to print the result of expressions as True or False has been successfully executed.


# EXPERIMENT-1(B): DATA TYPES

## AIM
Write a python program to read two numbers and convert and print them into a complex number and print the real and imaginary part of the complex number.

## ALGORIHTM

- Start
- Read Inputs: Prompt the user and accept the first number (for the real part) and the second number (for the imaginary part).
- Convert to Float: Convert both input values to floating-point numbers to allow for decimal inputs.
- Create Complex Number: Form the complex number by passing the real and imaginary values into Python's built-in complex(real, imaginary) function.
- Display Complex Number: Print the complete complex number (which Python formats as real + imaginaryj).
- Extract Real Part: Access the .real attribute of the created complex number.Extract Imaginary Part: Access the .imag attribute of the created complex number.
- Print Parts: Display the extracted real and imaginary parts individually.
- End

## PROGRAM
```
a=float(input())
b=float(input())
c=complex(a,b)
print(c)
print(a)
print(c.imag)
```

## OUTPUT
<img width="801" height="307" alt="image" src="https://github.com/user-attachments/assets/0961cf94-e53c-4528-a3d4-ad52d247a4bc" />

## RESULT
Thus the pyhton program to read two numbers and convert, print them as complex(real and imaginary) number has been executed successfully.


# EXPERIMENT-1(C): VARIABLES & EXPRESSIONS OPERATOR

## AIM
write a program to convert temperature from Fahrenheit to Celsius

## ALGORITHM

- Start
- Read Input: Prompt the user to enter the temperature in Fahrenheit.
- Convert to Numeric: Convert the input string into a floating-point number (decimal) to allow for precise calculations.
- Calculate Celsius
- Print Result: Display the calculated temperature in Celsius, rounded to two decimal places for readability.
- End

## PROGRAM
```
f=float(input())
c=(f-32)/1.8
print("Fahrenheit = {:.2f}\nCelsius = {:.2f}".format(f,c))
```

## OUTPUT
<img width="565" height="305" alt="image" src="https://github.com/user-attachments/assets/12b6d24c-85d1-48e3-83ae-5627f1899be6" />

## RESULT
Thus the python program to convert temperature from Farenheit to Celsius has been executed successfully.


# EXPERIMENT-1(D) CONDITIONAL STATEMENTS

## AIM
Write a Python program to find the eligibility of admission for a professional course based on the following criteria:

Total in all three subject >=180
Marks in Maths >=60
Marks in Phy >=60
Marks in Chem>=60

## ALGORITHM

- Start
- Read Inputs: Input the marks obtained in Mathematics, Physics, and Chemistry.
- Calculate Total: Calculate the sum of the marks obtained in all three subjects (Total = Maths + Physics + Chemistry).
- Check Individual Marks Criteria: Verify if Maths >= 60 AND Physics >= 60 AND Chemistry >= 60.
- Check Total Marks Criteria: Verify if Total >= 180.
- Evaluate Eligibility: If both conditions (Step 4 and Step 5) are met, set status to "Eligible".
- Display Result: Print the eligibility status ("Eligible" or "Not Eligible") to the user.
- End

## PROGRAM
```
ad=int(input())
a=int(input())
b=int(input())
c=int(input())
if(ad<180):
    
    print("The candidate is not eligible.The total marks is less than 180.")
    
elif (a<60 or b<60 or c<60):
    
    print("The candidate is not eligible. Marks is less than 60 in any one of the Subjects")
else:
    
      print("The  candidate is eligible for admission.")
```

## OUTPUT
<img width="1157" height="464" alt="image" src="https://github.com/user-attachments/assets/8ebe9137-f6bd-4f78-a898-08d3aceaca6a" />

## RESULT
Thus the python program to find the eligibility for admission through the given criteria has been executed successfully.


# EXPERIMENT-1(E) VARIABLES & EXPRESSIONS OPERATOR

## AIM
Write the python program to check whether the entered username and password is matching . 
username=saveetha
password=saveetha12

## ALGORITHM

- Start
- Define Credentials: Store the predefined valid username ("saveetha") and password ("saveetha12") as string constants.
- Read Username: Prompt the user and input the entered username.
- Read Password: Prompt the user and input the entered password.
- Check Match: Compare if the entered username matches the valid username AND the entered password matches the valid password.
- Print Success: If both match, display a message indicating successful login.
- Print Failure: If either does not match, display an error message indicating invalid credentials.
- End

## PROGRAM
```
uname=input()
passw=input()
uname1="saveetha"
pass1="saveetha12"
if uname==uname1 and passw==pass1:
    print("Login successfull")
else:
    print("Login Failed")
```

## OUTPUT
<img width="585" height="241" alt="image" src="https://github.com/user-attachments/assets/78684016-8df3-4848-b9e3-ca98cd061699" />

## RESULT
Thus the python program to check the username and password is matching or not has been executed successfully.




