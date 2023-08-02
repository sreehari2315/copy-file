# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the source file in read mode.
### Step 2:
Read the contents of the source file and store it in a variable
### Step 3:
Close the source file.
### Step 4:
Open the destination file in write mode. If the file doesn't exist, it will be created.
### Step 5:
Write the contents from the variable to the destination file.
### Step 6:
Read the contents of the destination file and print it to verify the copy operation.
### Step 7:
End the program
## PROGRAM:
```python
#Program to copy the text from one file to another
#Developed by :Sree Hari K
#Register umber : 23000908
from google.colab import drive
drive.mount('/content/drive',force_remount=True)
f=open('messi.txt',"r")
a=f.read()
print(a)
b=open('way.txt',"w+")
b.write(a)
b.seek(0)
print(b.read())
```

### OUTPUT:
![output](2.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.