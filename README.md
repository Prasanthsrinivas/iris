# iris ---https://colab.research.google.com/drive/1rnrYUawl_3rlMz0a4cfquEDlf_Kb0chh

import seaborn as sns
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

#load dataset frm seaborn
data = sns.load_dataset("iris")
data

data.head()
data.tail()
data.species.unique()
data.info()
data.describe()
data.corr()
data.species.value_counts()

#datacleaning /duplicated values
data.isnull().sum() 



