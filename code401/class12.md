# pandas 
Pandas is a game-changer for data science and analytics, particularly if you came to Python because you were searching for something more powerful than Excel and VBA. Pandas uses fast, flexible, and expressive data structures designed to make working with relational or labeled data both easy and intuitive.

Customarily, we import as follows:
```
In [1]: import numpy as np

In [2]: import pandas as pd
```
![panda](https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg)
## class pandas
class pandas.DataFrame(data=None, index=None, columns=None, dtype=None, copy=False)


Two-dimensional, size-mutable, potentially heterogeneous tabular data.
Data structure also contains labeled axes (rows and columns). Arithmetic operations align on both row and column labels. Can be thought of as a dict-like container for Series objects. The primary pandas data structure.

## Parameters
datandarray (structured or homogeneous), Iterable, dict, or DataFrame
Dict can contain Series, arrays, constants, dataclass or list-like objects. If data is a dict, column order follows insertion-order.

Changed in version 0.25.0: If data is a list of dicts, column order follows insertion-order.


Selecting a single column, which yields a Series, equivalent to df.A:

```
In [23]: df["A"]
Out[23]: 
2013-01-01    0.469112
2013-01-02    1.212112
2013-01-03   -0.861849
2013-01-04    0.721555
2013-01-05   -0.424972
2013-01-06   -0.673690
Freq: D, Name: A, dtype: float64
```
- indexIndex or array-like
Index to use for resulting frame. Will default to RangeIndex if no indexing information part of input data and no index provided.

- columnsIndex or array-like
Column labels to use for resulting frame. Will default to RangeIndex (0, 1, 2, …, n) if no column labels are provided.

- dtypedtype, default None
Data type to force. Only a single dtype is allowed. If None, infer.

- copybool, default False
Copy data from inputs. Only affects DataFrame / 2d ndarray input.

- Pandas is mainly used for data analysis. Pandas allows importing data from various file formats such as comma-separated values, JSON, SQL, Microsoft Excel.[8] Pandas allows various data manipulation operations such as merging,[9] reshaping,[10] selecting,[11] as well as data cleaning, and data wrangling features
