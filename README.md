# Read-from-CSV

## AIM:
To read the contents from a CSV file

## ALGORITHM:
Step 1:
Download the CSV file

Step 2:
Open a python platform

Step 3:
Create a folder in python

Step 4:
Copy the downloaded CSV file to the python folder

Step 5:
Run the program

## PROGRAM:
```
# Program for reading a content from CSv file
# Developed by: YUVARAJ B
# Reg.no: 212222230182
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:

![9](https://github.com/Yuva2005raj/Read-from-CSV/assets/118343998/0e932310-4869-4522-982f-be3dc2657d10)



## RESULT:
Thus a program to read a CSV file has been developed and executed successfully
