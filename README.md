# Word count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file iusing with open()
### Step 2: 
Specify reading mode while passing the open()
### Step 3: 
Iterate through the file using for loop
### Step 4:  
Use .split() to split the words in the file
### Step 5: 
Increment count by len of obtained list
### Step 6: 
Display the no. of words
## PROGRAM:
```
# Program to search number of words in a filr
# Developed by: Prajin S
# Register Number: 23012918
with open("file1.txt",'r') as np:
    wordcnt=0
    for line in np:
        words=line.split()
        wordcnt+=len(words)
    print("No. of words in file are:",wordcnt)
```

### OUTPUT:
![Screenshot 2023-12-30 135804](https://github.com/Prajin19/Word-count/assets/144979377/0f11004f-89f4-4b78-a345-949ac7b448cd)

![Screenshot 2023-12-30 135754](https://github.com/Prajin19/Word-count/assets/144979377/d31e74bb-d262-4688-acea-8e3ca1fb0199)


## RESULT:
Thus the program is written to find the word count from a text.
