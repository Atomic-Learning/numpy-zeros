# Numpy: Zeros

You can create an array of zeros with `np.zeros()`.

```py-cell
import numpy as np

zero = np.zeros([2, 2, 3])

print(zero)
```

The argument gives the shape of the array, so the length of the sequence controls the number of dimensions and each value gives the size of one dimension. `np.zeros()` returns an array of floats.

As the number of dimensions increases, it becomes harder to read the whole array at once when printing it.