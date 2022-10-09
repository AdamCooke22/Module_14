# MODULE 14 CHALLENGE : Machine Learning Trading Bot


For this challenge we are assuming the role of a financial advisor at one of the top five financial advisory firms in the world. Our firm is constantly competing with other firms to manage and automatically trade assets in a highly dynamic environment. Our job is to improve the existing algorithmic trading systems to maintain the firms competitive advantage in the market. 

In the machine_learning_trading_bot.ipynb file we are tasked with implementing an algorithmic trading strategy that uses machine learning to automate the trading decisions. We are also tasked with adjusting the input parameters to optimize the trading algorithm. Lastly, we are to train a new machine learning model and compare its perfermance to that of the baseline model.

The attempt to optimize the baseline model ended up with a 3% lower accuracy score. The attempt had similar precision scores, and the recall/f1 scores improved and declined mildly in opposite categories. The attempy to optimize the model using linear regression was ultimately a fail.


---

## Technologies

This project leverages python 3.7 with the following packages:

* [Pandas](https://github.com/google/pandas) - Pandas is a powerfull tool for data analysis and manipulation. Pandas provides a plethora of useful functions that make it easy to express, analyze, and manipulate data.

* [scikit-learn](https://scikit-learn.org/stable/) - This is a machine learning library for the python programming language. This library allows for the use of multiple machine learning models, tools, and algorithms.

* [Hvplot](https://github.com/google/hvplot) - This Module provides a high-level potting API that allows for users to easily generate a wide array of plot types. HvPlot's main benefit is that it allows for very interactive visualizations.

* [Numpy](https://github.com/google/numpy) - This module offers comprehensive mathematical functions, used for working with arrays. Numpy allows for seamlessand speedy integration with a wide variety of databases.



---

## Installation Guide

Before running the application first install the following dependencies.

```
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.svm import SVC
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report

```

---

## Usage

To use the machine learning trading bot file simply clone the repository and open the machine_learning_trading_bot.ipynb file in jupyter notebook.

Upon opening the file you will have the option to run the whole note book and that will provide you with all of the calculations, evaluations, and visualizations for the analysis of the machine learing and trading data. Some screenshots of that in action can be seen below via this link below.

* [SCREENSHOTS](https://github.com/AdamCooke22/module_14/tree/main/screenshots) 

## Contributors

Completed by Adam Cooke

---

## License

MIT
