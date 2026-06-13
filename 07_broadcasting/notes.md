# NumPy Broadcasting

## What is Broadcasting?

Broadcasting allows NumPy to perform operations on arrays of different shapes without using loops.

It automatically expands the smaller array to match the larger array.

---

## Example 1

```python
import numpy as np

arr = np.array([10, 20, 30, 40])

result = arr + 5

print(result)
```

Output:

```python
[15 25 35 45]
```

The value 5 is automatically broadcasted to every element.

---

## Example 2

```python
arr = np.array([
    [1,2,3],
    [4,5,6]
])

arr + 10
```

Output:

```python
[
 [11 12 13]
 [14 15 16]
]
```

---

## Broadcasting Rules

Rule 1:
Dimensions must be equal

OR

Rule 2:
One dimension must be 1

Otherwise NumPy raises an error.

---

## Example

Shape:

(2,3)

+

(1,3)

Valid

---

Shape:

(2,3)

+

(2,2)

Invalid

---

## Applications in Machine Learning

- Feature Scaling
- Normalization
- Standardization
- Deep Learning
- Matrix Computation