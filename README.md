# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

Step 2:
Read the file and store in a variable.

Step 3:
Now create a new file in which we want to paste the content using write access mode.

Step 4:
Use write function to copy the read file that has been stored in the variable.

Step 5:
The content in the original file will be copied in the new file.

Step 6:
End the program.

## PROGRAM:
~~~
with open('text','r') as file1:
    with open('text1','w') as file2:
        for i in file1:
            file2.write(i)


### OUTPUT:
~~~
<img width="578" alt="mi" src="https://user-images.githubusercontent.com/94882905/154803118-b1ed32a4-d74d-4696-a3ce-70c50f52a21b.png">
<img width="941" alt="mi1" src="https://user-images.githubusercontent.com/94882905/154803126-9a785b51-4de9-423c-8d37-eeb672ae8bd1.png">




## RESULT:
Thus the program is written to copy the contents from one file to another file.
