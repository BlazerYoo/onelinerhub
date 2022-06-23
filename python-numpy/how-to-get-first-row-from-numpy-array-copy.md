# How to get first row from Numpy array

```python
import numpy as np
arr = np.array([[1, 2], [3, 4]])
row = arr[0,:]
```

- `import numpy as np` - load [lib:Numpy module](/python-numpy/how-to-install-python-numpy-lib) for Python
- `[[1, 2], [3, 4]]` - sample matrix data (2-dimensional array)
- `np.array` - declare Numpy array
- `arr` - variable contains array
- `[0,:]` - return first row (index number is `0`) of the specified matrix

group: get_row

## Example: 
```python
import numpy as np
arr = np.array([[1, 2], [3, 4]])
row = arr[0,:]
print(row)
```
```
[1 2]

```

link_youtube: https://youtu.be/fO4F87BYqm4
