# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: Step 1:
```
Import sys module

Step 2:
Open the file with sys.argv[1]

Step 3:
Use the for loop to select the content in file

Step 4:
Use split function to to separate the file content into words or strings

Step 5:
Count the length of the words using len

Step 6:
Print the number of words
```


## PROGRAM:



```

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```

### OUTPUT:

![image](https://github.com/Jerushli/command-line-arguments-to-count-word/assets/120041243/cd32f586-e3d7-4c6d-9e64-720ae01ab45f)



![image](https://github.com/Jerushli/command-line-arguments-to-count-word/assets/120041243/e13c836b-1639-4444-a286-9e9ace075db5)



![image](https://github.com/Jerushli/command-line-arguments-to-count-word/assets/120041243/8f162b5b-633d-4dca-8b88-9280a4b64c83)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
