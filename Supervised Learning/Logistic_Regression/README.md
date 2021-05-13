# Logistic Regression
## Contents 
In this notebook, we will be using the dataset [SAheart](https://web.stanford.edu/~hastie/ElemStatLearn//datasets/SAheart.data), to predict if a person has coronary heart disease (CHD) based on some attributes using logistic regression from scratch.
## SAheart Data
The dataset comes from a retrospective sample of males in a heart-disease high-risk region of the Western Cape, South Africa. There are roughly two controls per case of CHD, thus this is our target variable, *y*. These data are taken from a larger dataset, described in  *Rousseauw et al, 1983, South African Medical Journal*. 

The dataset includes the following columns: 

* `sbp` = Systolic blood pressure
* `tobacco`	= Cumulative tobacco use (kg)
* `ldl` = Low densiity lipoprotein cholesterol
* `adiposity`
* `famhist` = Family history of heart disease (Present, Absent)
* `typea` = Type-A behavior
* `obesity`
* `alcohol` = Current alcohol consumption
* `age`	= Age at onset
* `chd` = *Target*, coronary heart disease (1, 0)

## Software Requirements
The following packages will be needed to run the code below: 

* CSV [documentation](https://csv.juliadata.org/stable/)
* DataFrames [documentation](https://dataframes.juliadata.org/stable/)
