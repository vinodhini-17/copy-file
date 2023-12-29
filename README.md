# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
 
Read the file and store in a variable.

### Step 3: 

Now create a new file in which we want to paste the content using write access mode.

### Step 4:  

Use write function to copy the read file that has been stored in the variable.

### Step 5:

The content in the original file will be copied in the new file.

### Step 6: 

End the program.

## PROGRAM:

```python
To write a program for copying the contents from one file to another file.
Developed by: Aadithyan R 
RegisterNumber: 22000618

with open("f45.txt","r") as fp:
    x = fp.read()
with open("f44.txt","w") as fp1:
    fp1.write(x)
```

### OUTPUT:
![copy 1](https://github.com/vinodhini-17/copy-file/assets/145742741/fc79171c-3fe7-4a85-8fde-74079ca6aa1e)
![copy 1](https://github.com/vinodhini-17/copy-file/assets/145742741/190d67a0-e1db-478f-856d-86dc3a5447d8)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
