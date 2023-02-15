# Data-Science-and-Big-Data-Analytics
DSBAL Parcticals
# Practical 2

import pandas as pd

df=pd.read_csv('dirtydata.csv')

df

df.shape

df.info()

df.head()

df.head(10)

df.tail()

df.tail(10)

df.loc[0]

df.loc[[0,5]]

df[['Calories']]

df[['Date']]

df.iloc[[0,1,2,3,4],[0,1,2,4]]

df[['Calories']].mean()

df[['Duration']].mean()



df[['Pulse']].mean()

df[['Duration']].min()

df[['Duration']].max()

df[['Pulse']].max()

df[['Pulse']].min()



