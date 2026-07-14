You can create an array of zeros with `np.zeros()`.

```py-cell
import numpy as np

zero = np.zeros([2, 2, 3])

print(zero)
```

The argument is a sequence (in the example above a list) that gives the shape of the array, so the length of the sequence controls the number of dimensions and each value gives the size of one dimension. `np.zeros()` returns an array of zeroes expressed as floats.