# Libraries
It's about the Machine Learning Libraries
## Essential libraries for Machine Learning in Python
Libraries are sets of routines and functions that are written in a given language. A robust set of libraries can make it easier for developers to perform complex tasks without rewriting many lines of code.
One of Python’s greatest assets is its extensive set of libraries.Machine learning is largely based upon mathematics. Specifically, mathematical optimization, statistics and probability. Python libraries help researchers/mathematicians who are less equipped with developer knowledge to easily “do machine learning”.
### Below are some of the most commonly used libraries in machine learning:
![l1](https://user-images.githubusercontent.com/42317258/51082414-55620d80-172c-11e9-9f92-69879f2bd67d.PNG)

# 1.Numpy (Numerical Python)
  It's the fundamental package for Numerical computation with Python,it contains a powerful N-dimensional array object.Numeric,the ancestor of numpy,was developed by JIM HUGUNIN.Another package Numarray was also developed having some additional functionalities.In 2005
  TRAVIS OLIPHANT created Numpy package by incorporating the features of numarray into Numeric package.
  NumPy = Numeric + Numarray  
[l2.pdf](https://github.com/VijayPrakashReddy-k/Libraries/files/2752874/l2.pdf)
![l2](https://user-images.githubusercontent.com/42317258/51082653-8bee5700-1731-11e9-8a34-665639d7f8ee.PNG)
NumPy targets the CPython reference implementation of Python, which is a non-optimizing bytecode interpreter. Mathematical algorithms written for this version of Python often run much slower than compiled equivalents. NumPy address the slowness problem partly by providing multidimensional arrays and functions and operators that operate efficiently on arrays, requiring rewriting some code, mostly inner loops using NumPy.
#### Numpy : https://en.wikipedia.org/wiki/NumPy

# 2.Pandas 
The name ‘Pandas’ is derived from the term “panel data”, an econometrics term for multidimensional structured data sets.
Pandas is a very popular library that provides high-level data structures which are simple to use as well as intuitive.
It has many inbuilt methods for grouping, combining data and filtering as well as performing time series analysis.
Pandas can easily fetch data from different sources like SQL databases, CSV, Excel, JSON files and manipulate the data to perform operations on it. 
### There are two main structures in the library:
![l3](https://user-images.githubusercontent.com/42317258/51082737-403cad00-1733-11e9-8983-384ab8bd3299.PNG)
#### Series:
A Series is a one-dimensional object that can hold any data type such as integers, floats and strings. Let’s take a list of items as an input argument and create a Series object for that list.
#### DataFrame:
A DataFrame is a two dimensional object that can have columns with potential different types. Different kind of inputs include dictionaries, lists, series, and even another DataFrame.It is the most commonly used pandas object.

[PandasPythonForDataScience.pdf](https://github.com/VijayPrakashReddy-k/Libraries/files/2752894/PandasPythonForDataScience.pdf)
![l4](https://user-images.githubusercontent.com/42317258/51082834-dae9bb80-1734-11e9-8072-802d52d71b5c.PNG)

[Python_Pandas_Cheat_Sheet_2.pdf](https://github.com/VijayPrakashReddy-k/Libraries/files/2752896/Python_Pandas_Cheat_Sheet_2.pdf)
#### Pandas : https://en.wikipedia.org/wiki/Pandas_%28software%29
## Data Visualization
# 3.Matplotlib
The best and most sophisticated ML is meaningless if you can’t communicate it to other people.

So how do you actually turn around value from all this data that you have? How do you inspire your business analysts and tell them “stories” full of “insights”?

This is where Matplotlib comes to the rescue. It is a standard Python library used by every data scientist for creating 2D plots and graphs. It’s pretty low-level, meaning it requires more commands to generate nice-looking graphs and figures than with some advanced libraries.

However, the flip side of that is flexibility. With enough commands, you can make just about any kind of graph you want with Matplotlib. You can build diverse charts, from histograms and scatterplots to non-Cartesian coordinates graphs.

It supports different GUI backends on all operating systems, and can also export graphics to common vector and graphic formats like PDF, SVG, JPG, PNG, BMP, GIF, etc.

[Python_Matplotlib_Cheat_Sheet.pdf](https://github.com/VijayPrakashReddy-k/Libraries/files/2752929/Python_Matplotlib_Cheat_Sheet.pdf)

![l5](https://user-images.githubusercontent.com/42317258/51083342-99f6a480-173e-11e9-926e-dcb50dab7068.PNG)

matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK+. There is also a procedural “pylab” interface based on a state machine (like OpenGL), designed to closely resemble that of MATLAB, though its use is discouraged.[2] SciPy makes use of matplotlib.

pyplot is a matplotlib module which provides a MATLAB-like interface.[6] matplotlib is designed to be as usable as MATLAB, with the ability to use Python, with the advantage that it is free.

#### Matplotlib : https://en.wikipedia.org/wiki/Matplotlib

# 4.Seaborn
Seaborn is a popular visualization library that builds on Matplotlib’s foundations. It is a higher-level library, meaning it’s easier to generate certain kinds of plots, including heat maps, time series, and violin plots.
Seaborn, which provides a high-level interface to draw statistical graphics.
As for Seaborn, you have two types of functions: **Axes-level functions** and **figure-level functions**. The ones that operate on the Axes level are, for example, regplot(), boxplot(), kdeplot(), …, while the functions that operate on the Figure level are lmplot(), factorplot(), jointplot() and a couple others.

This means that the first group is identified by taking an explicit ax argument and returning an Axes object, while the second group of functions create plots that potentially include Axes which are always organized in a “meaningful” way. The Figure-level functions will therefore need to have total control over the figure so you won’t be able to plot an lmplot onto one that already exists. When you call the Figure-level functions, you always initialize a figure and set it up for the specific plot it’s drawing.

[Statistical Data Visualization with seaborn.pdf](https://github.com/VijayPrakashReddy-k/Libraries/files/2752956/Statistical.Data.Visualization.with.seaborn.pdf)
![l6](https://user-images.githubusercontent.com/42317258/51083762-2b691500-1745-11e9-9127-72dff24b8533.PNG)

#### Seaborn : https://seaborn.pydata.org/

# 5.SciPy 
SciPy builds on the NumPy array object and is part of the NumPy stack which includes tools like Matplotlib, pandas and SymPy, and an expanding set of scientific computing libraries. This NumPy stack has similar users to other applications such as MATLAB, GNU Octave, and Scilab. The NumPy stack is also sometimes referred to as the SciPy stack.

[Python_SciPy_Cheat_Sheet_Linear_Algebra.pdf](https://github.com/VijayPrakashReddy-k/Libraries/files/2752972/Python_SciPy_Cheat_Sheet_Linear_Algebra.pdf)
![l7](https://user-images.githubusercontent.com/42317258/51083889-68cea200-1747-11e9-89a0-640290959b17.PNG)

#### SciPy : https://en.wikipedia.org/wiki/SciPy

# 6.Scikit-Learn
![l8](https://user-images.githubusercontent.com/42317258/51084113-d7612f00-174a-11e9-8fd3-4f5a19ea7c15.PNG)

Scikit-learn (formerly scikits.learn) is a free software machine learning library for the Python programming language. It features various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.
![l9](https://user-images.githubusercontent.com/42317258/51084116-daf4b600-174a-11e9-8e9f-ad34c0cae395.PNG)

[Scikit_Learn_Cheat_Sheet_Python.pdf](https://github.com/VijayPrakashReddy-k/Libraries/files/2752984/Scikit_Learn_Cheat_Sheet_Python.pdf)
![l10](https://user-images.githubusercontent.com/42317258/51084125-f233a380-174a-11e9-9ed0-f7db5a041d72.PNG)

Scikit-learn is one the most popular ML libraries. It supports many supervised and unsupervised learning algorithms. Examples include linear and logistic regressions, decision trees, clustering, k-means and so on.

It builds on two basic libraries of Python, NumPy and SciPy. It adds a set of algorithms for common machine learning and data mining tasks, including clustering, regression and classification. Even tasks like transforming data, feature selection and ensemble methods can be implemented in a few lines.

For a novice in ML, Scikit-learn is a more-than-sufficient tool to work with, until you start implementing more complex algorithms.

#### Scikit-Learn : https://en.wikipedia.org/wiki/Scikit-learn



