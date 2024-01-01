# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
to write a python program for getting the word count from a text file

### Step 2: 
open the required file by using the function "With"
 
### Step 3: 
then use the laptop to assign the i value in the file

### Step 4: 
using split function to split the words 

### Step 5: 
finding the given length of the words by using by using len() function

### Step 6: 
calling the function and printing the number of words

## PROGRAM:

fname=input("Enter the file name:")

num_words=0

with open(fname,"r") as f

  for line in f:
  
    words=line.split()
    
    num_words+=len(words)
    
  print("Numbers of words:",num_words)
  

### OUTPUT:
![Screenshot 2024-01-01 124719](https://github.com/23004345/Word-count/assets/138849203/f7badfff-603d-4280-a718-0c1d71d5462e)

## RESULT:
Thus the program is written to find the word count from a text.
