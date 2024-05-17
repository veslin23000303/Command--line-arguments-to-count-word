# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function which will count the word in the given file.
### Step 2:
Create a file pointer and open the file.
### Step 3:
Initialize word count as zero.
### Step 4:
For each line in file, split it into words and find number of the words in every line.
### Step 5:
Sum the number of words in each line.
### Step 6:
Display the total words in the file.
### Step 7:
Close the file pointer and end the program. 

## PROGRAM:
```python
Developed by: Antony Abishek K
Register no: 212223240009
import sys
fp=open(sys.argv[1])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()
```
### OUTPUT:

![image](https://github.com/mercyarulappan/Command--line-arguments-to-count-word/assets/149233730/8f64ac57-532c-489e-85da-ca18b28b74e0)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
