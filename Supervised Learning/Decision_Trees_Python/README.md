# Decision Trees
## Contents
In this notebook, we will be using a **classification tree** on the Titanic dataset in order to predict the target variable `survived`, whether or not a passenger survived the Titanic crash. Decision trees uses a tree-like model of decisions to make predictions. Growing a tree involves deciding on which features to choose and what conditions to use for splitting, along with knowing when to stop as to not *overfit* the data, thus a trim process is needed.

## Software Requirements
The following packages will be needed to run this notebook: 

* `numpy` [documentation](https://numpy.org/doc/)
* `pandas` [documentation](https://pandas.pydata.org/docs/)
* `sklearn` [documentation](https://scikit-learn.org/stable/)

The following data is used in this notebook:
* Titanic [available here](https://data.world/nrippner/titanic-disaster-dataset#__sid=js0)
