# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.

### Step 2: 
Read the text using read() function.
 
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.

### Step 4:  
Split the text using space separator.We assume that words in a sentance are separted by a space character.

### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6: 
End the program.

## PROGRAM:
```
Developed by : ESHWAR T
Register No: 212223230054

def wordcount(filename):
    count=0
    with open("Myfile.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
```

### OUTPUT:
![](.![image](https://github.com/NAVEEN23013059/Word-count/assets/150319555/7562f9ef-8810-48d0-928e-740842d4663e)
![](.![image](https://github.com/NAVEEN23013059/Word-count/assets/150319555/8de3eb70-e71a-4ce6-8071-edc284f71f5e)




## RESULT:
Thus the program is written to find the word count from a text.
