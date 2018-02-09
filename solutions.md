# Exercises for Day 5
Using SciPy, Scikit-Learn and Pandas

## 1. Scipy

### Linear Algebra
Have a look at the ```scipy.linalg``` [module](https://docs.scipy.org/doc/scipy/reference/linalg.html)

See the [Scipy](Scipy.ipynb) notebook for the solution

### Statistics
Have a look at the ```scipy.stats``` [module](https://docs.scipy.org/doc/scipy/reference/stats.html)

See the [Scipy](Scipy.ipynb) notebook for the solution

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
See the [army_solution](army_solution.ipynb) notebook for the solution

#### c. Download the notebook [alcohol.ipynb](alcohol.ipynb) and try yourself to use Pandas for grouping of data
See the [alcohol_solution](alcohol_solution.ipynb) notebook for the solution

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
