# copy-file
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
End the program.
## PROGRAM:
```
#Developed By: JANARTHANAN V K
#Register No: 212222230051
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![Screenshot 2023-06-10 135358](https://github.com/Janarthanan2/copy-file/assets/119393515/741056b2-f861-482e-b7ea-2b7177b8d051)

![Screenshot 2023-06-10 140604](https://github.com/Janarthanan2/copy-file/assets/119393515/5e3603cd-bcab-4d08-9b4a-c4f9e0c242b5)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
