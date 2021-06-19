# Readings: Data Analysis

## JupyterLab :
- JupyterLab is a next-generation web-based user interface for Project Jupyter.

- JupyterLab enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner

- JupyterLab also offers a unified model for viewing and handling data formats. JupyterLab understands many file formats (images, CSV, JSON, Markdown, PDF, Vega, Vega-Lite, etc.)

- You can arrange multiple documents and activities side by side in the work area using tabs and splitters. Documents and activities integrate with each other, enabling new workflows for interactive computing


- JupyterLab extensions can customize or enhance any part of JupyterLab, including new themes, file editors, and custom components.

- JupyterLab is served from the same server and uses the same notebook document format as the classic Jupyter Notebook.


## Numpy
### What is NumPy :
 - NumPy stands for Numerical Python, is a library consisting of multidimensional array objects and a collection of routines for processing those arrays. Using NumPy, mathematical and logical operations on arrays can be performed.

- NumPy is a commonly used Python data analysis package. By using NumPy, you can speed up your workflow, and interface with other packages in the Python ecosystem, like scikit-learn, that use NumPy under the hood. NumPy was originally developed in the mid 2000s, and arose from an even older package called Numeric. This longevity means that almost every data analysis or machine learning package for Python leverages NumPy in some way. 

- With NumPy, we can work with multidimensional arrays. NumPy makes it simple to perform mathematical operations on arrays. This is one of the primary advantages of NumPy, and makes it quite easy to do computations.

- the core of NumPy is written in a programming language called C, which stores data differently than the Python data types. NumPy data types map between Python and C, allowing us to use NumPy arrays without any conversion hitches.

### NumPy data types:

- float — numeric floating point data.

- int — integer data.

- string — character data.

- object — Python objects

### Creating A NumPy

Creating A NumPy  Array We can create a NumPy array using the numpy.array function. If we pass in a list of lists, it will automatically create a NumPy array with the same number of rows and columns.

Using NumPy To Read In Files It’s possible to use NumPy to directly read csv or other files into arrays. We can do this using the numpy.genfromtxt function.

Broadcasting Unless the arrays that you’re operating on are the exact same size, it’s not possible to do elementwise operations. In cases like this, NumPy performs broadcasting to try to match up elements