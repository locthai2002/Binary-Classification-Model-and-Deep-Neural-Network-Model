# Binary-Classification-Model-and-Deep-Neural-Network-Model
Use deep neural network to create a binary classification model to predict whether Alphabet Soup funding applicants will be successful.

Specifically, the business team has given you a CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The CSV file contains a variety of information about each business, including whether or not it ultimately became successful. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business.

The steps for this project are divided into the following sections:

1. Import the Data 
2. Preprocess data for a neural network model.
3. Use the model-fit-predict pattern to compile and evaluate a binary classification model.
4. Optimize the model.


---

## Technologies

This project leverages Anaconda and JupyterLab with Python 3.9:

* [Anaconda](https://www.anaconda.com/products/individual) 

Need to import the following libraries and dependencies:

```
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings
warnings.filterwarnings('ignore')
```

---

## Installation Guide

Before running the application first install the following dependencies.

1. Install [Anaconda](https://www.anaconda.com/products/individual) from link 
2. Open up GitBash(Windows) or Terminal(Mac)
3. Type ```conda update conda``` to update Conda
4. Type ```conda update anaconda``` to update Anaconda
5. Type ```conda create -n dev python=3.9 anaconda```
6. Type ```conda activate dev``` to activate conda
7. Install a dev environment kernel by typing ```python -m ipykernel install --user --name dev```
8. Install a node environment by typing ```conda install -c conda-forge nodejs```
9. Launch JupyterLab by typing ```jupyter lab```

Open a terminal window, and then activate your ```dev``` virtual environment by running the following command:
```
conda activate dev 
```
Install imbalance-learn by running the following command:

```
conda install -c conda-forge imbalanced-learn 
```
Install PyDotPlus by running the following command:

```
conda install -c conda-forge pydotplus
```
---

## Usage

You will need to clone the repo so that you can run the application:

```
 https://github.com/locthai2002/Credit-Risk-Resampling.git

```

Here are some screenshots from running the application:

## Import the Data

![Import the Data](images/1.png)

## Split the Data into Training and Testing Sets

![Split the Data into Training and Testing Sets](images/2.png)
![Split the Data into Training and Testing Sets](images/3.png)

## Create a Logistic Regression Model with the Original Data

![Create a Logistic Regression Model with the Original Data](images/4.png)
![Create a Logistic Regression Model with the Original Data](images/5.png)

## Predict a Logistic Regression Model with Resampled Training Data

![Predict a Logistic Regression Model with Resampled Training Data](images/6.png)

## Write a Credit Risk Analysis Report

![Write a Credit Risk Analysis Report](images/7.png)


---

## Contributors

Loc Thai -- www.linkedin.com/in/loc-thai-69b8a2141
Phone: 415.400.9998

---

## License

MIT
