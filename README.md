# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
From shutil import copy file
### Step 2: 
 From sys import exit
### Step 3: 
Getting input for source file
### Step 4:  
Getting input for target file
### Step 5: 
Giving condition for files
### Step 6: 
Getting statement from the user to print or not want to print
## PROGRAM:
```
#Program #Program for copying the contents from one file to another file 
#Developed by: JANANI S
#Register Number:23013409
with open("file1.txt",'r')as fp:
    msg1=fp.read()
with open("file2.txt",'a')as fp1:
    fp1.write(msg1)
print("Copied Successfully")
```
### OUTPUT:
![image](https://github.com/SJananisenthilkumar/copy-file/assets/144871139/1471f1cd-6881-4403-b578-13c282db98f3)
![photo 1](https://github.com/SJananisenthilkumar/copy-file/assets/144871139/4a39a98e-cc32-4332-9ef6-c87788291b6b)
![photo 2](https://github.com/SJananisenthilkumar/copy-file/assets/144871139/f67d4c63-ee19-4131-86b9-f8a23a5a9033)
<br>
<br>
## RESULT:
Thus the program is written to copy the contents from one file to another file.
