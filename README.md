# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

ALGORITHM:

Step 1:
Import sys

Step 2:
Open file using commandline arguments.

Step 3:
Using for loop find the word count from the contents of a file.

Step 4:
Use len to count number of words.

Step 5:
Give print statement.

Step 6:
End the program.

## PROGRAM:
```
##Developed by : K.NIVETHA
##Register number :22009186

import sys

with open(sys.argv[1],'r') as f:
    num_words =0
    for i in f:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```

### OUTPUT:



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
