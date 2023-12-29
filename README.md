# command-line-arguments-to-count-word
### Name: Anbuselvan.S
### Reference No: 23005959
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys module

### Step 2:
using sys module,open a file with read mode

### Step 3:
read the file and split the file and stor in the variable

### Step 4:
print the length of the variable

### Step 5:
End the program

## PROGRAM:
```
To write a python program for getting the word count from the contents of a file using command line arguments.
Developed by: Anbuselvan.S
Reference no: 23005959

import sys
f=open(sys.argv[1],"r")
a=f.read().split()
print(len(a))
```
### OUTPUT:
![image](https://github.com/anbuselvan1519/command-line-arguments-to-count-word/assets/139841744/c155515b-eaac-489e-810d-c44702a95458)
### TEXT FILE
![image](https://github.com/anbuselvan1519/command-line-arguments-to-count-word/assets/139841744/8c89c4b6-25c0-4f32-a757-d4a63dd7b1dd)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
