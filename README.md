# command-line-arguments-to-count-word

## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:
Import sys module.

### Step 2: 
Open the file with sys.argv[1]. 
 
### Step 3: 
Use the for loop to select the content in file

### Step 4:  
Use split function to to separate the file content into words or strings

### Step 5: 
Count the length of the words using len

### Step 6: 
Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: Surendhar A
RegisterNumber: 212222110049
import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```

### OUTPUT:
![ex51](https://github.com/Surendhar6/command-line-arguments-to-count-word/assets/118352907/afacc690-1a20-4e34-8cab-1fc2e2370dc5)
![ex52](https://github.com/Surendhar6/command-line-arguments-to-count-word/assets/118352907/d5c2653a-6c62-4fe1-8c38-b271f030dec5)
![ex53](https://github.com/Surendhar6/command-line-arguments-to-count-word/assets/118352907/c12efeab-271d-4c3a-b90b-51f423781e29)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
