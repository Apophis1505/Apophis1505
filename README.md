import pandas as pd
import numpy as np

# Load the dataset into a Pandas DataFrame
df = pd.DataFrame({
    'ID': [1, 2, 3, 4, 5],
    'Name': ['Alice', 'Bob', 'Charlie', 'David', 'Eve'],
    'Age': [20, 21, 19, 22, 20],
    'Math_Score': [85, 95, 70, 98, 88],
    'Science_Score': [92, 88, 94, 96, 91],
    'English_Score': [78, 85, 0, 88, 90],
    'History_Score': [80, 90, 75, 92, 85]
})

# Check for missing values in the dataset
print(df.isnull().sum())
