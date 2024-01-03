# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required the from which we need to copy the text.
### Step 2: 
 Using keyword "with" to open the required file.
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The for function is used to take each line from the main file.
### Step 6: 
Write() is used to write the lines of main file to the empty file or to the directed file.

## PROGRAM:
```
#Developed by: SAI GURUCHANDRAN G
#Register Number: 23014037
def copy(fname,newfile):
    with open(fname,'r')as fp:
        with open(newfile,'w')as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter as existing file: ")
newfile=input("Enter a name for new files: ")
copy(fname,newfile)
```

### OUTPUT:
![WhatsApp Image 2024-01-03 at 00 16 06_35f0d621](https://github.com/Saiguruchandran/copy-file/assets/144870946/80fb853e-f03b-4b76-9d6a-56ffd9440dae)

![WhatsApp Image 2024-01-03 at 00 16 22_c0762ce8](https://github.com/Saiguruchandran/copy-file/assets/144870946/0e244b5f-b841-4920-8989-074195d45fc4)

![WhatsApp Image 2024-01-03 at 00 16 35_4d930d9e](https://github.com/Saiguruchandran/copy-file/assets/144870946/befc43c3-007c-48b5-8f6f-9a8c184c8c27)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
