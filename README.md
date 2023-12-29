# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
 Write some lines in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
Developed by:Tanushree.A
Register No:23004953

def copy(filename,newfile):
    with open(filename,'r') as fp:
         with open(newfile,'w') as fp1:
             data1=fp.read()
             fp1.write(date1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
### OUTPUT:
![copy file op1](https://github.com/Tanug25/copy-file/assets/138849166/5766ffa8-fbee-491b-87fd-b2c0f79ed7a8)

![copy file op2](https://github.com/Tanug25/copy-file/assets/138849166/3c956c3a-62a8-4179-8310-f5eee88c1793)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
