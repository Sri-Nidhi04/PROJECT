import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
data = pd.read_csv("C:\Users\SRINITHI\Downloads\archive\database.csv")
data.columns
data = data[['Date', 'Time', 'Latitude', 'Longitude', 'Depth', 'Magnitude']]
data.head()