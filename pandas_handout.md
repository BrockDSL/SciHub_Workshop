# Python and Pandas

*Pandas is a python tool to analyze data. We load a CSV file into a dataframe*

To use
`import pandas as pd`
`data = pd.read_csv("file.csv")`

Some useful functions

- `.head()` display the first lines of the dataframe
- `.count()` how many items are in the dataframe
- `.nunique()` how many unique items are in a dataframe
- `.unique()` the actual unique values seen in a dataframe 
- `.value_counts()` the frequency of the unique values found
- `.groupby()` collects data based on repeating values seen in a column
- `.sort_values( by = "column name" ascending=True)` sorts dataframe based on a column called "column name"
- `.mean()` arithmetic mean of dataframe values
- `.max()` highest value seen in a dataframe
- `.min()` lowest value seen in a dataframe
- `.tolist()` makes a Python list out of a portion of dataframe, useful for graphing
- `.loc["search"]` will locate all items in dataframe that match "search"


