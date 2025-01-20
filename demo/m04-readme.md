
Numeric (Continuous) |  Categorical
----------------|--------------------
E.g. height or weight of individuals | E.g. day of week, month of year, gender, letter grade
Can take any value | Finite set of permissible values 
Predicted using regression  models | Predicted using classification models 
Always can be sorted on magnitude | Categories may or may not be sortable 

# 1.Numerical Data
- Discrete :
Cannot be measured but can be 
counted (e.g.: Number of visitors in an hour, number of heads 
when a coin is flipped 100 times)

- Continuous :
Cannot be counted but can be 
measured (e.g.:  Height of an individual, home prices, stock prices)

/!\ Machine learning algorithms 
typically do not work well 
with numeric data with 
different scales

## Feature Scaling
- 1.1 Scaling :
Numeric values are shifted and rescaled so all 
features have the same scale i.e. within the same 
minimum and maximum values

- 1.2 Standardization :
Centers data round the mean and divides each value by the 
standard deviation so all features have 0 mean and unit variance

## Categotical data
Categorical data can only draw from 
a specific, restricted set of values

Not meaningful to calculate mean, 
standard deviation, correlation

Fine to tabulate categorical data using 
count frequencies and percentages

- Ordinal data is categorical, but can 
still be ordered (E.g. month of the year, 
ratings on a scale of 1 to 5)

- Noaminal, Even less in common with numeric 
data - cannot even be ordered, nominal data are simply names (E.g. Brand names of cars)

/!\ Categorical data has to be 
numerically encoded before 
it can be used in ML models

- Label encoding : Numeric id for each category; 
single column suffices

- One-hot encoding : Separate column with 1 or 0 for presence/absence of each category