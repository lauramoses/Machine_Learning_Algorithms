# K-Nearest Neighbors

This project demonstrates the use of K-Nearest Neighbors on the Iris dataset. The intention is to classify data from the iris data, using KNN to predict the species of flower based on various features. An optimal K is determined to attain maximum accuracy for the algorithm. 

Algorithm concepts used in this model:
  * Selecting data for KNN representation
  * Visualizating the data that is being selected
  * Understanding the distance of the Euclidean formulas for two points
  * Apply and correctly classifying the point selected to the right class
  * Find a k value that produces the lowest error margin as a result

## Iris Dataset
This example uses the iris dataset from `RDatasets`. The data is loaded as a DataFrame with columns:
* `SepalLength`
* `SepalWidth`
* `PetalLength`
* `PetalWidth`
* `Species`
 
## Software Requirements
For this notebook, the current stable release of `Julia` was used:
* [Julia v1.5.3](https://julialang.org/downloads/#current_stable_release)

The following packages are required to run the code: 
* [RDatasets](https://github.com/JuliaStats/RDatasets.jl)
* [Plots](http://docs.juliaplots.org/latest/)
* [Random](https://docs.julialang.org/en/v1/stdlib/Random/)
* [CSV](https://csv.juliadata.org/stable/)

Also, knowledge of Julia `DataFrames` will be necessary:
* [DataFrames](https://dataframes.juliadata.org/stable/)
