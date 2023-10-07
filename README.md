PANDAS
<br>
Pandas: An Introduction <br>
Wes McKinney created pandas for the first time in 2008. Pandas is an <b>open-source library </b>in Python. It provides the various data structures and operations for manipulating the numerical data and time series.It has the function of analyzing, cleaning, exploring, and manipulating the data. Pandas cleans up messy data sets and makes them readable and relevant.
<br>
<br>
<b>Why pandas... </b>
<br>
1. Fast and efficient for manipulating and analyzing data.<br>
2. Data from the different file objects can be easily loaded.<br>
3. High performance and merging the data
4. Columns from the data structure can be deleted and inserted.
<br>
<b> DATA STRUCTURES OF PANDAS</b>
<br>
Pandas have basically three structures:
1. Series<br>
2. DataFrame <br>
3. Panel <br>

<b>1. Series: </b> A Pandas series is like a column in a table.A series is a one-dimensional array-like structure with homogenous data. <br>
**Creating a Series:-<br>
In the real world, a Pandas series will be created by loading the datasets from existing storage, which can be a SQL database, a CSV file, or an Excel file. Pandas Series can be created from lists, dictionaries, scalar values, etc.
<br>
<b>example</b>
<br>
import pandas as pd 
import numpy as np 

# Creating empty series 
ser = pd.Series() 
print("Pandas Series: ", ser) 

# simple array 
data = np.array(['g', 'e', 'e', 'k', 's']) 
	
ser = pd.Series(data) 
print("Pandas Series:\n", ser)


