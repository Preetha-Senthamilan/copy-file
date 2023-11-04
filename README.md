# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Open the file f1 in read mode.

Step 2:
Open the file f2 in append mode.

Step 3:
Copy the contents using write() with the for loop.

Step 4:
End the program. 

## PROGRAM:
```
#Developed By: PREETHA.S
#Register No: 212222230110
with open('f11.txt','r') as f1:
    with open ('f12.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:

F1:

![Screenshot 2023-11-04 183046](https://github.com/Preetha-Senthamilan/copy-file/assets/119390282/09c9c4fd-fa11-4ed1-8188-6a51ef25a5ab)

F2:

![Screenshot 2023-11-04 183122](https://github.com/Preetha-Senthamilan/copy-file/assets/119390282/b0f90d89-0419-4901-83e3-f77d3994708a)

OUTPUT:

![Screenshot 2023-11-04 182952](https://github.com/Preetha-Senthamilan/copy-file/assets/119390282/1dd5ca91-7368-4623-9c8a-1d14b4820ed5)  ![Screenshot 2023-11-04 183005](https://github.com/Preetha-Senthamilan/copy-file/assets/119390282/640e39d2-31db-4541-b25e-ec41d11b45a6)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
