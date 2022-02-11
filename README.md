# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Open a file which has to be filled.

# Step 2:
open a file which has to be copied.

# Step 3:
Using write function copy the file contents.

# Step 4:
Use with keyword to open the files.

# Step 5:
Run the code using terminal.

# Step 6:
Now the contents are copied.

## PROGRAM:
with open('file2.txt','w') as file2:
    with open("file1.txt",'r') as file1:
        for words in file1:
            file2.write(words)

### OUTPUT:
![image](https://user-images.githubusercontent.com/94525955/153637965-4e66527e-7ab8-4b0c-8b53-c435b6be3103.png)
![image](https://user-images.githubusercontent.com/94525955/153638066-7742838e-3bb7-499d-b688-9246ee095465.png)
![image](https://user-images.githubusercontent.com/94525955/153638140-37ef1983-86f3-4375-8556-96adf873591a.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
