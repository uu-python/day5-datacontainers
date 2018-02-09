# Exercises for Day 5
Using SciPy, Scikit-Learn and Pandas

## 1. Scipy

### Linear Algebra
Have a look at the ```scipy.linalg``` [module](https://docs.scipy.org/doc/scipy/reference/linalg.html)

#### a. Define a matrix A
```
[[1 2 3]
 [4 5 6]
 [7 8 9]]
```

#### b. Define a vector b
```
[1 2 3]
```

#### c. Solve the linear system of equations A x = b

#### d. Check that your solution is correct by plugging it into the equation

#### e. Repeat steps a-d using a random 3x3 matrix B (instead of the vector b)

#### f. Solve the eigenvalue problem for the matrix A and print the eigenvalues and eigenvectors

#### g. Calculate the inverse, determinant of A

#### h. Calculate the norm of A with different orders


### Statistics
Have a look at the ```scipy.stats``` [module](https://docs.scipy.org/doc/scipy/reference/stats.html)

#### a. Create a discrete random variable with poissonian distribution and plot its probability mass function (PMF), cummulative distribution function (CDF) and a histogram of 1000 random realizations of the variable

#### b. Create a continious random variable with normal distribution and plot its probability mass function (PMF), cummulative distribution function (CDF) and a histogram of 1000 random realizations of the variable

#### c. Test if two sets of (independent) random data comes from the same distribution
Hint: Have a look at the ```ttest_ind``` function


## 2. Scikit-Learn 
For this exercise you need to have scikit-learn installed (you can try to install it with pip)

Tutorials are taken from [https://github.com/justmarkham/scikit-learn-videos](https://github.com/justmarkham/scikit-learn-videos)

#### a. Download the jupyter notebook tutorial [03_getting_started_with_iris.ipynb](https://github.com/justmarkham/scikit-learn-videos/raw/master/03_getting_started_with_iris.ipynb) and familiarize yourself with the Iris dataset and the terminology of Machine Learning

#### b. Download the jupyter notebook tutorial [04_model_training.ipynb](https://github.com/justmarkham/scikit-learn-videos/raw/master/04_model_training.ipynb) and practice the K-nearest neighbors classification model

#### c. Download the jupyter notebook tutorial [05_model_evaluation.ipynb](https://github.com/justmarkham/scikit-learn-videos/raw/master/05_model_evaluation.ipynb) and use different evalutaion techniqies to compare machine learning models


## 3. Pandas
For this exercise you need to have Pandas installed (you can try to install it with pip)

Tutorials are taken from [https://github.com/guipsamora/pandas_exercises](https://github.com/guipsamora/pandas_exercises)

#### a. Download the notebook [food_facts.ipynb](food_facts.ipynb) and learn how to load and display data with Pandas

#### b. Download the notebook [army.ipynb](army.ipynb) and try yourself to use Pandas for filtering and sorting of data

#### c. Download the notebook [alcohol.ipynb](alcohol.ipynb) and try yourself to use Pandas for grouping of data


## Bonus. Publishing of Python code 

#### a. Take some piece of Python code (e.g. the ```simple_math.py``` module) and make it into a package.
A package should include a ```__init__.py``` inside all subdirectories, it should be able to import all the submodules from the top level, functions should have documentation (docstrings) and ideally there is a docs folder with Sphinx documentation. You should also include a small Readme.md file

#### b. Add a ```setup.py``` file to your package (following the instructions from the lecture notes)
Now you should be able to install your package using pip

```
pip install . --user
```

#### c. Upload your package to the TestPyPi repository
Follow the instructions from [here](https://packaging.python.org/guides/using-testpypi/)


