# Read-from-CSV

## AIM:

## ALGORITHM:
## Step 1:
Import pandas as pd.

## Step 2:
Read the CSV file using read_csv method.

## Step 3:
Use head and tail method to get the required contents from the file.

## Step 4:
Use len() method to get the number of rows and columns.

## Step 5:
Print the output.
## PROGRAM:
```
#Developed by: M.Jayachandran
#Reference No: 22008847
import pandas as pd 
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```

## OUTPUT:
![panda](https://user-images.githubusercontent.com/118447015/214832867-547d1740-8bc2-4f71-8a9c-a0d96b816f3c.jpg)




## RESULT:
