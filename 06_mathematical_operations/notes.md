# NumPy Mathematical Operations & Statistical Functions

## Why Are These Important?

Machine Learning is all about numbers.

Before training models, we often need to:

- Find averages
- Find maximum values
- Calculate standard deviation
- Analyze distributions
- Summarize datasets

NumPy provides built-in functions that are extremely fast.

---

## Sum

```python
np.sum(arr)
```

Returns the total sum of all elements.

---

## Mean

```python
np.mean(arr)
```

Returns the average value.

---

## Median

```python
np.median(arr)
```

Returns the middle value.

---

## Maximum Value

```python
np.max(arr)
```

Returns the largest element.

---

## Minimum Value

```python
np.min(arr)
```

Returns the smallest element.

---

## Standard Deviation

```python
np.std(arr)
```

Measures data spread.

---

## Variance

```python
np.var(arr)
```

Measures variability.

---

## Axis Operations

For a 2D dataset:

Rows = Samples

Columns = Features

### Column-wise Sum

```python
np.sum(X, axis=0)
```

### Row-wise Sum

```python
np.sum(X, axis=1)
```

Axis 0 → Vertical (Columns)

Axis 1 → Horizontal (Rows)

---

## Applications in Machine Learning

- Data Analysis
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Normalization
- Statistical Insights











