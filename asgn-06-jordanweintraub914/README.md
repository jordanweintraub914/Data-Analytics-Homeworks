# Assignment 6 (Spring 2021)
### *Jordan Weintraub*

## Topics Covered 
- Exploring Data Analysis
    - using the golden rules 
- Regression analysis
    - understanding what alpha, Beta, p_value and R2 mean in context
    - differece between discrete, continuous and categorical data 

### Function used for 90% of the Homework
sm_ols('DEPENDENT VARIABLE  ~  INDEPENDENT VARIABLE ', data=DATASET).fit().summary()

### Useful tips to know
- pd.get_dummies function will categorize binary data into groups that will be used for multiple linear regression on discrete data

### Necessary packages to import
- import pandas as pd
- import numpy as np
- import seaborn as sns
- from statsmodels.formula.api import ols as sm_ols
- from statsmodels.iolib.summary2 import summary_col
