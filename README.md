# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Commence the program
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
### Step 6: 
## Program:
~~~
#Program to circulate N values.
#Developed by: pragatheesvaran AB
#RegisterNumber: 21003592
def circulate(): 
    num1=[10,20,30,40,50,60]
    n=int(input())
    num1=num1[n:]+num1[:n]
    print("After circulating the values are:",num1)
~~~
## Output: 
![output](ex2.jpg)
## Result:
The variables are rotated successfully
