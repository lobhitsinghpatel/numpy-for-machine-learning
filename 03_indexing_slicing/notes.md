# Numpy Indexing and Slicing

## What is indexing?
Indexing is used to access a specific element in a NumPy array.

>> Why it is important?
In machine learning , you constantly need to access
1. Specific rows
2. Specific Columns
3. Individual values
from datasets

---

## What is slicing?
Slicing means extracting a portion of an array 

Syntax:      
'''python
array[Start:End]
'''

Example:

'''python
arr = np.array[(10, 20, 30, 40, 50)]
arr[1:4]
'''

Output:

'''python
[20 30 40 50]
'''

---

## Indexing in 2D Arrays

Datasets:
'''python
X = np.array([
    [22, 25000, 1],
    [25, 30000, 2],
    [30, 50000, 5],
    [35, 70000, 8]
])
'''

Columns: Age | Salary | Experience

Access first employee age :
'''python
X[0, 0]
'''

Output:

'''python
22
'''

---

## Column Selection

Salary Column:

'''python
X[:, 1]
'''

Output:
'''python
[25000 30000 50000 70000]
'''

---

## Row Selection

First Row:

```python
X[0]
```

Last Row:

```python
X[-1]
```

---

## Applications in Machine Learning

- Feature Selection
- Data Cleaning
- Data Preprocessing
- Dataset Exploration
