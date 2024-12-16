## Exploratory Data Analysis on a heart disease dataset
This project is a EDA on heart disease dataset, the dataset is located in the data folder.
The data contains information on heart health indicators, including demographic, clinical, 
and lifestyle variables.

The EDA is done in a jupyter notebook called eda.ipynb


## Task 1
### Data Loading and Inspection 
In this task, the python libraries were imported as alias.
The data was inspected with the pandas.

## Task 2
### Handle Misrepresented Data in columns
_Found the ? in the ca column, replace it the mode of the ca column and casted the data type to a float_ 
_Found the ? in the thal column, replace it the mode of the thal column and casted the data type to a float_ 

### Duplicates
*There were no duplicates in the data*


## Task 3
In Task 3, the heart_disease column was edited to be in 0 and 1 
Where *0* = no heart disease
and *1* = heart disease 

This will make heart_disease column easy to analyze and draw conclusions.


## Task 4
### The conclusion drawn from this correlation matrix is that, there are low correlation between the age, sex and the heart disease. But there are slightly higher correlation between cp, exang, oldpeak, ca and thal to the heart disease on this a *_conclusion can be drawn that heart disease is more dependent on the lifestyle instead of the age and sex._*

### Pandas CrossTab 
_The conclusion draw from the crosstab shown that there is a chance of a male getting a heart disease than a female_

## Task 5
In this pair plot, we are looking for patterns between the two color groups. Looking at the density plots along the diagonal, there are no features that cleanly separate the groups (age has the most separation). However, looking at the scatterplot for age and thalach (maximum heart rate from an exercise test), there is more clear separation. It appears that patients who are old and have low thalach are more likely to be diagnosed with heart disease than patients who are young and have high thalach. This suggests that we want to make sure both of these features are included in our model.