# exploratory_data_analysis

## Import Librarys
Import packages that use to work with in a ML/AI projects
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inlinepd.__version__
```

## Read CSV Files with Pandas
We have the read_csv the Pandas and record on the df object:
```
df = pd.read_csv('path_to_csv_file.csv')
```

## Check Types
We can see the DataFrame type
```
print(type(df))<class'pandas.core.frame.DataFrame'>
```

## View Data
The first column is the index created automatically by Pandas, the other columns were collected from the dataset loaded.
```
df.head(10)
```

## Check Data Types
Let’s see how Pandas determined the types of each column when loading them
```
df.dtypes
```

## Check Columns
Returns a list of columns we have
```
df.columns
```

## Adjust column name
Adjust the name of the columns of the dataframe.
```
cols = ['col1', 'col2', 'col3']
df.columns = cols # columns receive cols
```

## Check indexes
Starts at 0 and ends at 81, jumping 1 in 1.
```
df.index
RangeIndex(start=0, stop=81, step=1)
```
