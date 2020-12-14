# Machine-Learning-and-Statistics-2020-Tasks

## Student: Niamh O'Leary
## ID: G00376339

## Contents of Github Repository
1. README file
2. Tasks.ipynb - Jupyter Notebook containing four tasks, pyhon code and references. 
3. Assessment.pdf - pdf document outlining the tasks
4  iris.csv - data used in Task 4
5. Images folder - containing images used in the tasks


## Overview of Tasks

### Task 1 - Square Root 

Write a Python function called sqrt2 that calculates and
prints to the screen the square root of 2 to 100 decimal places. Your code should
not depend on any module from the standard library1 or otherwise. You should
research the task first and include references and a description of your algorithm.

### Task 2 - Chi Squared

The Chi-squared test for independence is a statistical
hypothesis test like a t-test. It is used to analyse whether two categorical variables
are independent. The Wikipedia article gives the table below as an example [4],
stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats
to verify this value and calculate the associated p value. You should include a short
note with references justifying your analysis in a markdown cell.


### Task 3 Standard Deviation

The standard deviation of an array of numbers x is calculated using numpy 
as np.sqrt(np.sum((x - np.mean(x))**2)/len(x))

However, Microsoft Excel has two different versions of the standard deviation
calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above
calculation but in the STDEV.S calculation the division is by len(x)-1 rather
than len(x) . Research these Excel functions, writing a note in a Markdown cell
about the difference between them. Then use numpy to perform a simulation
demonstrating that the STDEV.S calculation is a better estimate for the standard
deviation of a population when performed on a sample. Note that part of this task
is to figure out the terminology in the previous sentence.


### Task 4 - K-Means 

Use scikit-learn to apply k-means clustering to
Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might
be, and then explain how your model could be used to make predictions of species of iris.
 
## Getting started
Download and install Python and Anaconda All files associated with this project are available at https://github.com/NiamhOL/Machine-Learning-and-Statistics-2020-Tasks 

## Packages used in this project

The following packages were used to run statistical analysis and draw grpahs for this project.

* Python https://www.python.org/downloads/
* Anaconda https://www.anaconda.com/distribution/ - is the easiest way to perfrom Python data science machine learning on Linux, Windows and Mac OS.
* iPython https://ipython.org/ - it an interactive command-line terminal for Python.
* Numpy http://www.numpy.org/ - is the fundamental package for scientific computing within Python.
* Jupyter Notebook https://jupyter.org/ - is an open-source web application that allows the creation and sharing of documents that contains live code, equations, visualisations    and narriative text

## Python libraries used in this project for statistical analysis and to generate plots
* import pandas as pd https://pandas.pydata.org/
* import scipy.stats as stats https://docs.scipy.org/doc/scipy/reference/stats.html
* import matplotlib.pylab as plt https://matplotlib.org/
* from sklearn.model_selection import ....https://scikit-learn.org/stable/



