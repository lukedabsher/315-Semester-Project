import pandas as pd 
from scipy.stats import pointbiserialr

# Luke Absher
# 7/19/2022
# CPTS 315
# Project Report

# loading data into a dataframe 
df = pd.read_csv("ProjectData.csv")    
print(df)

# creating lists from dataframe columns
winner = df['WINNER'].tolist()
kill_difference = df['KILL_DIFFERENCE'].tolist()

# generating point biserial value
point_biserial = pointbiserialr(winner,kill_difference)
print(point_biserial)
