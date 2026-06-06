# NumPy Boolean Masking & Fancy Indexing

## What is Boolean Masking?

Boolean Masking is used to filter data based on conditions.

It returns only the values where the condition is True.

Example:

```python
import numpy as np

salary = np.array([25000, 30000, 50000, 70000, 90000])

print(salary > 50000)
```

Output:

```python
[False False False True True]
```

---

## Filtering Data

```python
salary[salary > 50000]
```

Output:

```python
[70000 90000]
```

---

## Multiple Conditions

### AND

```python
salary[(salary > 30000) & (salary < 80000)]
```

### OR

```python
salary[(salary < 30000) | (salary > 80000)]
```

### NOT

```python
salary[~(salary > 50000)]
```

---

## What is Fancy Indexing?

Fancy Indexing allows selecting custom rows or columns.

Example:

```python
arr = np.array([10,20,30,40,50])

arr[[0,2,4]]
```

Output:

```python
[10 30 50]
```

---

## Applications in Machine Learning

- Data Cleaning
- Data Filtering
- Feature Selection
- Feature Engineering
- Dataset Preprocessing