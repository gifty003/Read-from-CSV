# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
 Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.
## PROGRAM:
```
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head())
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:
![image](https://github.com/gifty003/Read-from-CSV/assets/145822352/231fb31a-0115-45af-a8bf-64795a058eb9)

## RESULT:
Thus python program for reading content from a CSV file is successful.
