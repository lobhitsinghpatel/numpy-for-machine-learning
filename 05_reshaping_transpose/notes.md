# NumPy Reshaping, Flattening & Transpose

## Why is Reshaping Important?

Machine Learning models expect data in specific shapes.

Example:

A dataset with:

100 samples
5 features

Shape:

(100, 5)

Sometimes data comes in a different format and must be reshaped.

---

## Reshape

Reshape changes the dimensions of an array without changing the data.

Example:

```python
import numpy as np

arr = np.array([1,2,3,4,5,6])

arr.reshape(2,3)
```

Output:

```python
[[1 2 3]
 [4 5 6]]
```

Shape:

(2,3)

---

## Flatten

Converts a multi-dimensional array into a 1D array.

Example:

```python
arr = np.array([
    [1,2,3],
    [4,5,6]
])

arr.flatten()
```

Output:

```python
[1 2 3 4 5 6]
```

---

## Transpose

Rows become columns and columns become rows.

Example:

```python
arr.T
```

Original Shape:

(2,3)

Transposed Shape:

(3,2)

---

## Applications in Machine Learning

- Data Preprocessing
- Feature Engineering
- Image Processing
- Neural Networks
- Deep Learning