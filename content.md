You can create an array of zeros with `np.zeros()`.

```py-cell
import numpy as np

zero = np.zeros([2, 2, 3])

print(zero)
```

The argument is a sequence (in the example above a list) that gives the shape of the array, so the length of the sequence controls the number of dimensions and each value gives the size of one dimension. In the example above, the shape is `[2, 2, 3]`, so the array has three dimensions, with sizes 2, 2 and 3 respectively.

`np.zeros()` returns an array of zeroes expressed as floats.