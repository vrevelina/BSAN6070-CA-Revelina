# CA04.ipynb

CA04.ipynb is a jupyter notebook program for practice on Ensemble Models

## Installations

User should have Python3 and Jupyter Notebook installed into their system.

User should also have the following packages installed:
* sklearn
* pandas
* numpy
* matplotlib
* xgboost

## Dataset

The dataset is provided in a .csv file. It can also be retrieved from the following link: https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true

The dataset was obtained from the Census Bureau containing seven demographic variables and salaries of the corresponding individual. The following is a description of our dataset:
* Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]
* Number of attributes (Columns): 7
* Number of instances (Rows): 48,842

The dataset also contains a column named [flag] which indicates which rows to be used as training data and testing data.

## Instructions

User can open CA04.ipynb through jupyter notebook or the Google Colab environment. Run all cells as needed.

In order to be able to run the program successfully, please be sure that all the packages listed above are installed in the chosen environment. 

## Usage

The purpose of CA04 is to analyze the performance of various Ensemble Models, namely:
* Random Forest Classifier
* AdaBoost Classifier
* Gradient Boost Classifier
* XGB Classifier

We do this by visualizing each classifier's behaviors in terms of accuracy score, with respect to the number of estimators specified in the hyperparameter. Then we select the best performing number of estimators and instantiate each classifier with the same hyperparameters to see the model's performance.



