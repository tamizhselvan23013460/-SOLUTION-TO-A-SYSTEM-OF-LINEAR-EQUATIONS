# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by:TAMIZHSELVAN B 
#RegisterNumber:23013460
import numpy as np
A = [[1,-3],[3,1]]
B = [0,10]
C = np.linalg.solve(A,B)
print(C)
```

## Output:
![output]![linear system output](https://github.com/tamizhselvan23013460/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/150231370/ad31bf29-2409-47a6-967d-391cfcb7de92)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

