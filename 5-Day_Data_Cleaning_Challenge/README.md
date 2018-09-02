# 5 Day Data Cleaning Challenge by Kaggle 
  
  
#### __This folder contains all the cource code and notes regarding Data Cleaning.__ 
  
  
## Notes 
 
### Day 1: Handling missing values 
* [`df.sample()`](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.sample.html) 
* `nfl_data.isnull().sum().sum()` 
* [`df.dropna()`](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.dropna.html#pandas.DataFrame.dropna)
* [`subset_nfl_data.fillna()`](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.fillna.html#pandas.DataFrame.fillna) 
* `subset_nfl_data.fillna(method = 'bfill', axis=0).fillna(0)` 
* 