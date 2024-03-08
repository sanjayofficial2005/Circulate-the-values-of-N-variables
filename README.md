# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Import def circulate
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Add coding to input values
### Step 6: 
Print the coding to get answer.

## Program:
```python

NAME  :SANJAY M
Reg No:212223230187


def circulate():
    values=eval(input())
    n=int(input())
    for i in range(n):
        temp=values.pop(0)
        values.append(temp)
    print("After circulating the values are:",values)
```

## Output:
![Screenshot 2024-03-08 182657](https://github.com/sanjayofficial2005/Circulate-the-values-of-N-variables/assets/148048602/8635189d-ee21-4a10-aede-479c804bbd28)

![Screenshot 2024-03-08 182710](https://github.com/sanjayofficial2005/Circulate-the-values-of-N-variables/assets/148048602/e5cb95af-1bcd-47c3-9ad7-a1a37890cf19)


## Result:
This experiment Circulate-the-values-of-N-variables verified succesfully.
