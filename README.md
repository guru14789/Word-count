# Word-count
## AIM:
To write a Python program for getting the word count from a text.
## EQUIPMENT REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a txt file to count the number of words in that file.
### Step 2: 
Open the txt file in read mode using open(). 
### Step 3: 
Using the split() function to split the words in txt file and count it
### Step 4:  
 Save the Python program using.py extension.
### Step 5: 
Run the Python program in the terminal to get the output.
### Step 6: 
The number of words in the file is displayed as the output

## PROGRAM:
```
#program developed by: SREEKUMAR S
#register number:23008070
num_words = 0 
with open("C:\\Users\\admin\\OneDrive\\Desktop\\text.txt", 'r') as f1:
    for line in f1:
        words = line.split()
        num_words += len(words)

print("Number of words in the file = {}".format(num_words))

```

### OUTPUT:
![Screenshot 2023-12-24 203500](https://github.com/guru14789/Word-count/assets/151705853/59cecbe9-1074-4d83-b37e-244cabca61ec)

## RESULT:
Thus the program is written to find the word count from a text.
