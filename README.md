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
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:] + l[:n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2024-03-09 093754](https://github.com/sanjayy2431/Circulate-the-values-of-N-variables/assets/149365143/85716027-2f9d-4cb8-a3f0-8f4bfad83a77)

## Result:

The output for circulate the values of n variables is successfull.
