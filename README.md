# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:Create a user defined function. 
### Step 2:Get the variables from user to enter inside the list 
### Step 3:Get the value from the user for the number of rotation
### Step 4:Using the slicing concept rotate the list
### Step 5:After rotating the variables, store the rotated variables in a seperate list 
### Step 6:At last, print the list of rotated variables
## Program:
```
#Program to circulate N values.
#Developed by: praveen v
#RegisterNumber:23013808
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print('After circulating the values are:' ,l)
```
## Output:
![Screenshot 2023-11-15 094314](https://github.com/praveenv23013808/Circulate-the-values-of-N-variables/assets/145824728/1f0ac73a-57db-4b36-a995-5bd0407ea0bf)

## Result:
The output for circulate the values of n variables is successfully.
