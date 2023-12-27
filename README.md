# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: Get the two values from the user
### Step 2: Assign the value of second variable to a temporary variabl
### Step 3: Assign the value of the first variable to the second variable.
Get the value from the user for the number of rotation
### Step 4: Assign the value in temporary variable to the first variable
Using the slicing concept rotate the list

### Step 5: Print both the values it would be interchanged
### Step 6: End the program
## Program:
#Program to circulate N values.
#Developed by: M.vignesh
#RegisterNumber:23014020
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
## Output:
![Screenshot 2023-12-27 235523](https://github.com/vigneshvickyu/Circulate-the-values-of-N-variables/assets/151948835/449a4e17-c0f7-4f86-ad9d-19a6e0d6e339)

## Result:
