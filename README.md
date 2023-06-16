# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the created file.

### Step 2:
Use the split function to split the words.

### Step 3:
Find the length of the words using len() function.

### Step 4:
Print the number of words in the file.

## PROGRAM:
```
#Developed By: CHAITANYA PS 
#Register No: 212222230024
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of wordds:",wordslen)
```
### OUTPUT:
![image](https://github.com/chaitanya18c/Word-count/assets/119392724/aa03dee8-5f57-4b31-8790-cde9d1b9cc2d)

## RESULT:
Thus the program is written to find the word count from a text.
