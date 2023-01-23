# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read
mode.


### Step 2: 
Read the file and store in a variable.

 
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.


### Step 4:  
Use write function to copy the read file that has been stored in the variable

### Step 5: 
The content in the original file will be copied in the new file

### Step 6: 
End the program.

## PROGRAM:
Developed by: Subhikshaa M
RegisterNumber: 22001030
with open("sample1.txt", "r") as firstfile:
with open("sample2.txt", "a") as secondfile:
for line in firstfile:
secondfile.write(line)

### OUTPUT1:
![image](https://user-images.githubusercontent.com/118787344/214053348-6c3d448c-90ab-4a16-8c89-081feeb1db68.png)

###OUTPUT2:
![image](https://user-images.githubusercontent.com/118787344/214053473-15399e28-e320-4c30-abd0-aeed5e707888.png)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
