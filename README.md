# Boston Housing Project

Goal is to build a trained model on [Boston Hosing Data](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/) that predicts monetary value given three input attributes; total number of rooms, neighborhood poverty level, and student-teacher ratio of nearby schools

## How to read the files in this project?

Any steps to a model is to understand data, please refer to 'housing.csv' and use this [UCI link](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.names) to learn more about the data and its history.

Next, you could reference boston_project.ipny to understand the actions I took from downloading, understanding, and partioning the data for the model to developing, training, and validating the model to testing on a sample of data to evaluate model performance. 

Technically, you need certain python libraries such as [numpy](https://github.com/numpy/numpy), [pandas](https://github.com/pandas-dev/pandas), visuals.py (provided), [matplotlib](), [sklearn / scikit-learn](https://github.com/scikit-learn/scikit-learn)

Need a software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. 

For main sauce of files click on this [Udacity ML GitHub](https://github.com/udacity/machine-learning/tree/master/projects/boston_housing)

## **Why does this all matter?**

This was the 1st project from Udacity's machine learning nanodegree course which sets you to familarize how the rest of the course will go to this readMe on github. This helped me also understand the syntax and various important libs to python in deploying a model.


## What is this visuals.py file?

Your guess was as best as mine when I started this project so I won't share the secret just yet. No really, this was a supplementary file with the project. Peak inside boston_project.ipny as to why this matters and here is the hint it imports supplementary visualizations.

## FAQ

**What if boston_housing.ipny is not loading?**
> Try downloading the file and running Jupyter Notebook.

**How do I read housing.csv?**
> There are 489 rows and 4 columns in this file. The last column is the target variable and the top 3 are attributes. 
> - RM: average number of rooms per dwelling
> - LSTAT: percentage of population considered lower status
> - PTRATIO: pupil-teacher ratio by town
> - MEDV: median value of owner-occupied homes
