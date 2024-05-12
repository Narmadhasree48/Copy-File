# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
 Open the file f2 in append mode.
### Step 3: 
Copy the contents using write() with the for loop.
### Step 4:  
End the program
## PROGRAM:
```PYTHON
#DEVELOPED BY :NARMADHA SREE S
# REGISTER NO:212223240105
with open("text.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![alt text](<Screenshot 2024-05-12 205631.png>)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
