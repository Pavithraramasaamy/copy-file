# copy-file

## AIM:

To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:
import sys

### Step 2: 
Get the input values

 
### Step 3: 

write a python program for copying the contents from one file to another file.

### Step 4:  

Run the program

### Step 6: 

End the program

## PROGRAM:
```python
'''Program For Copying The Contents:
Developed by:Pavithra R
RegisterNumber: 22008965 '''

print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()

fileHandle = open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()

print("\nFile Copied Successfully!")
```
### OUTPUT:
![](./copy%201.png)

![](./copy%202.png)

![](./copy%203.png)
## RESULT:
Thus the program is written to copy the contents from one file to another file.