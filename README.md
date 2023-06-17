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
DEVELOPED BY:JERUSHLIN JOSE J B
REG NO:212222240039
```

```
import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()

```

### OUTPUT:



![image](https://github.com/Jerushli/command-line-arguments-to-count-word/assets/120041243/39b4abaa-f4d8-466c-b856-a84efb7d0fef)





![image](https://github.com/Jerushli/command-line-arguments-to-count-word/assets/120041243/2466fe46-f240-4542-9490-9b2b94d79503)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
