# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file
### Step 2: 
 Open the required file by using the function "with".
### Step 3: 
Then use the laptop to assign the i value in the file.
### Step 4:  
Using split function to spilt the words
### Step 5: 
Finding the given length of the words by using len() fuction.
### Step 6: 
Calling the function and Printing the number of words.
## PROGRAM:
```
Developed by:S.Premalatha
Ref no:22009393
num_words = 0
with open('text.txt'.'r') as f1:
     for i in f1:
         word = i.split()
         num_words += len(word)
print("number of words in the file = {}".format(num_words))
```

### OUTPUT:

![Screenshot (73)](https://user-images.githubusercontent.com/120620842/214808077-de5b31ed-0fc5-435f-944f-359e9680200b.png)





## RESULT:
Thus the program is written to find the word count from a text.
