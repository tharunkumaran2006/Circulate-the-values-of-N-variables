# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Define a function.
### Step 2: 
Get the list from the user.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the list.
### Step 6: 
End the program.
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2024-03-16 101828](https://github.com/tharunkumaran2006/Circulate-the-values-of-N-variables/assets/151625188/9e8cad18-58d0-4d6d-bf6a-587a9fde69fb)

## Result:
