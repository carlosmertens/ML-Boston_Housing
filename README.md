# Project: Predicting Boston Housing Prices
## Content: Model Evaluation and Validation

### Project Overview
The Boston housing market is highly competitive, and we want to be the best real estate agent in the area. To compete with our peers, we decide to leverage a few basic machine learning concepts to assist you and a client with finding the best selling price for their home. Luckily, we’ve come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Our task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for your clients' homes.

### Project Highlights
This project is designed to get us acquainted with the many techniques for training, testing, evaluating, and optimizing models, available in sklearn.

Things you learned by completing this project:

How to explore data and observe features.
How to train and test models.
How to identify potential problems, such as errors due to bias or variance.
How to apply techniques to improve the model, such as cross-validation and grid search.

### Install

This project requires **Python 3** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

It is also required to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.

### Code

Template code was provided by Udacity, Inc. in the `boston_housing.ipynb` notebook file. To run the project, it will also be required to use the `visuals.py` Python file and the `housing.csv` dataset file which were provided by Udacity Inc. Note that the code in `visuals.py` is meant to be used out-of-the-box and not intended to be manipulated. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.
While some code had already been implemented to get it started, it was needed to implement additional functionality to successfully complete the project.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes

## Authors

* **Udacity, Inc.** - *Udacity Instructor* -
* **Carlos Mertens** - *Udacity Student* -

## Acknowledgments

* Udacity, Inc.
