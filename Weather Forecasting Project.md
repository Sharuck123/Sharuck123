# importing the dataset
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
# reading the dataset
data=pd.read_csv("world_population.csv")
data.head()
# shaping the data
data.shape
# information of the data
data.info()
# describes all the data
data.describe()
# Minimum & Maximum Population in 2010
data['2010 Population'].min()
data['2010 Population'].max()
# Total Population in 2015
data['2015 Population'].sum()
# How Many countries are there in the dataset
data['Country'].count()
# Total Growth rate in Dataset
data['Growth Rate'] == '2022 Population'
