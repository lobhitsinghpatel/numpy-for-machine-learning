# NumPy Random Module

## Why is Random Module Important?

Machine Learning relies heavily on randomness.

Examples:

- Train/Test Split
- Data Sampling
- Weight Initialization
- Random Dataset Generation
- Simulations

NumPy provides powerful random number generation tools.

---

## Random Integer

```python
import numpy as np

np.random.randint(1, 10)
```

Generates a random integer.

---

## Random Float

```python
np.random.rand()
```

Generates a random float between 0 and 1.

---

## Random Array

```python
np.random.rand(3, 4)
```

Creates a 3×4 matrix of random values.

---

## Random Choice

```python
np.random.choice([10, 20, 30, 40])
```

Randomly selects one value.

---

## Seed

```python
np.random.seed(42)
```

Makes random results reproducible.

---

## Why Seeds Matter?

Without seed:

Every run → Different output

With seed:

Every run → Same output

This is essential for ML experiments.

---

## Applications in Machine Learning

- Dataset Generation
- Reproducible Experiments
- Random Sampling
- Neural Network Initialization