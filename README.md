# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.



### Step 2: 
Give a new file name to create a copy of a file content.


 
### Step 3: 
Read the file and close the file



### Step 4:  
Now write the content in the new file.



### Step 5: 
When done print "File copied successfully".



### Step 6: 
End of the program.



## PROGRAM:
```
'''

#developed by : JEGATHEESWARI R
#Register number : 23013697
'''
with open("words.txt",'r')as fp:
    msg1=fp.read()
with open("word.txt",'a')as fp1:
    fp1.write(msg1)
print("Copied Successfully")

```

### OUTPUT:
![output](<Screenshot 2024-01-02 204850.png>)
![output](<Screenshot 2024-01-02 205209.png>)
![output](<Screenshot 2024-01-02 205741.png>)



## RESULT:
Thus the program is written to copy the contents from one file to another file.