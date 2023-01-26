# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
```
Step 1:
import numpy as np

Step 2:
Enter the correct input values

Step 3:
write a python program for getting the word count from the contents of a file using command line arguments.

Step 4:
Use command line srguments

Step 5:
End the program
``
## PROGRAM:
```
#program is developed: Suji.G
# REF.NO: 22008563
```
import sys
count = {}
with open(sys.argv[1],'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word]=1
            else:
                count[word] +=1
````
### OUTPUT:

![a1](https://user-images.githubusercontent.com/119559822/214852509-2855aeb2-f041-4da3-a848-2dcc2954245f.png)
![a2](https://user-images.githubusercontent.com/119559822/214852554-9cd0c564-ff30-435d-a720-5d1e2513b106.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
