# Read from CSV

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
```Python
import pandas as pd
df = pd.read_csv("C:/Users/sst/Downloads/bba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
#### program file
<img width="673" alt="image" src="https://github.com/Nijeesh-bit/Read-from-CSV/assets/89188014/0cedb2c3-520b-4ba6-9478-97986bbf49c5">
<br>
<br>

#### output:
<img width="960" alt="image" src="https://github.com/Nijeesh-bit/Read-from-CSV/assets/89188014/e7837c6c-10a3-4ee3-a890-b30f6f2ab089">

## RESULT:
Thus python program for reading content from a CSV file is successful.
