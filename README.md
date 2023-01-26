# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign values in a variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
By concentration operator,it will join the two values

## Program:
```
#Program to CIRCULATE THE VALUES OF N-VARIABLES.
#Developed by : SABARI S
#Register no: 22008698
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```    

## Output:
![Screenshot (7)](https://user-images.githubusercontent.com/118660461/214778946-42469509-2df5-4022-a8ec-93989cffba17.png)

## Result:
The program is executed sucessfully.
