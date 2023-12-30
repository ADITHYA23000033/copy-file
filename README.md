# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1
Import panda module as pd

### Step 2:
Read the csv file

### Step 3:
Print the first 10rows

### Step 4:
Print the next 5rows

### Step 5:
Print the toal no.of rows and columns with argument 0 for row and argument 1 for column.
## PROGRAM:
```
#Program to read contents from a CSV file.
#Developed by: Aditya V
#Reg No: 23000033
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))
```
### OUTPUT:
![5 C](https://github.com/ADITHYA23000033/copy-file/assets/148514544/73d65810-f4f6-4222-8281-9d479b20df78)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
