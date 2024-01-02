# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:

### OUTPUT:
#Program to find the Word Count using command line arguments

#Developed by:ajina joshpin

#register Number:23013547

fname=input("enter the file name")

num_words=0

with open(fname, 'r') as f:

for line in f:

words=line.split()

num_words+=len (words)

print('Number of words: ',num_words)

## output:
![Screenshot 2024-01-02 144953](https://github.com/ajinajoshpin/Word-count/assets/148514578/421d7a55-7698-4760-970c-39e6b77a53be)


## RESULT:
Thus the program is written to find the word count from a text.
