# EXP-10
EXP 10 : Study of Panda Library

Theory
Pandas is an open-source Python library used for data manipulation and
analysis. It provides two primary data structures:
Series: One-dimensional labeled array capable of holding any data
type.\
DataFrame: Two-dimensional labeled data structure with columns of
potentially different types.
Pandas is widely used in: - Data Analysis\
Data Cleaning\
Data Visualization\
Machine Learning Preprocessing
---
Experiment Procedure
1. Import Pandas
import pandas as pd
2. Create a Series
s = pd.Series([10, 20, 30, 40])  
print(s)
3. Create a DataFrame
data = {  
"NAME": ["A", "B", "C"],  
"MARKS": [85, 90, 78]  
}
df = pd.DataFrame(data)  
print(df)
4. Basic DataFrame Operations
Shape: print(df.shape)
Dimensions: print(df.ndim)
Size: print(df.size)
5. Column Information
Columns: print(df.columns)
Data types: print(df.dtypes)
6. Accessing Data
print(df["NAME"])  
print(df["MARKS"])
print(df.loc[0, "NAME"])
---
Output
Successfully created a Series and DataFrame\
Performed operations like shape, size, and dimensions\
Accessed specific rows and columns
---
Conclusion
This experiment helped in understanding the basics of the Pandas
library, including creating Series and DataFrames, performing
operations, and accessing data.
---
Notes
Ensure Pandas is installed\
Use `.loc[]` for indexing\
DataFrames are widely used in real-world projects
