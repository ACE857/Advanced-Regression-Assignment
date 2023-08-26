# Project Name
> Housing price prediction with advanced regression(ridge and lasso)


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Repo contains advanced regression notebook for AI ML course advanced regression assignment.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Completed EDA, feature selection and model building.
- Tried simple regression but that performed very poorly
- Finally build a Ridge and Lasso model with following details.
  - Ridge
    - alpha = 50
    - train r2_score = 0.979970264382131
    - test r2_score = 0.9138819301661792
  - Lasso
    - alpha = 100
    - train r2_score = 0.9647170013944624
    - test r2_score = 0.9067626762425925

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
```commandline
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import warnings
import scipy
from sklearn.model_selection import train_test_split
from sklearn.feature_selection import RFE
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score
import statsmodels.api as sm
import warnings
from sklearn.preprocessing import MinMaxScaler
from sklearn.linear_model import Ridge, Lasso
from sklearn.model_selection import GridSearchCV
from sklearn.metrics import mean_squared_error
```