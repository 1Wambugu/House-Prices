# House Price Prediction Project
This project aims to explore and analyze the dataset related to house prices. The following points outline the key aspects covered in this analysis:

## Importing Libraries:

import pandas as pd: Imports the Pandas library and assigns it the alias pd. Pandas is a powerful library for data manipulation and analysis.
import numpy as np: Imports the NumPy library and assigns it the alias np. NumPy is used for numerical operations on arrays and matrices.
import matplotlib.pyplot as plt: Imports the pyplot module from the Matplotlib library and assigns it the alias plt. Matplotlib is a popular plotting library.
import seaborn as sns: Imports the Seaborn library and assigns it the alias sns. Seaborn is built on top of Matplotlib and provides a high-level interface for statistical graphics.
Reading Data:

train_data = pd.read_csv('train.csv'): Reads the data from a CSV file named 'train.csv' and stores it in a Pandas DataFrame named train_data. This assumes that the training data is stored in a CSV file.
test_data = pd.read_csv('test.csv'): Reads the data from a CSV file named 'test.csv' and stores it in a Pandas DataFrame named test_data. This assumes that the test data is stored in a CSV file.

# 1. Explore Data Distribution
### SalePrice
Summary statistics, visualizations, and interpretive text describing the distribution of SalePrice.

### TotRmsAbvGrd
Summary statistics, visualizations, and interpretive text describing the distribution of TotRmsAbvGrd.

### OverallCond
Summary statistics, visualizations, and interpretive text describing the distribution of OverallCond.

# 2. Explore Differences between Subsets
### OverallCond Impact on SalePrice
Separate the data into subsets based on OverallCond.
Demonstrate how this split impacts the distribution of SalePrice.

# 3. Explore Correlations
### Correlation with SalePrice
Identify features with the strongest positive and negative correlations with SalePrice.
Produce plots representing these relationships.

# 4. Engineer and Explore a New Feature
### Age Feature
Create a new feature "Age" representing the difference between the year sold and the year built.
Plot the relationship between age and sale price.

# 5. Visualization
Includes three polished visualizations of relevant findings.

# 6. Code Quality
Code is all runnable, easy to read, non-repetitive, and properly cited.