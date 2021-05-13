# Perceptron Learning Algorithm
## Contents
This notebook demonstrates the Perceptron Learning Algorithm from scratch on the Iris dataset by using adjustment of random weights onto various inputs to be applied to all inputs. We effectively identify and classify different species of iris based on its sepal features by applying a single neuron network.

## Iris Dataset
This example uses the `iris` dataset from `RDatasets`. The data is loaded as a `DataFrame` with columns:
* `SepalLength`
* `SepalWidth`
* `PetalLength`
* `PetalWidth`
* `Species`

The intention is to classify data from the `iris` data, using PLA to predict the species of flower based off of measurements of sepal length and width.

## Software Requirements
To access this data set and run this notebook, we will need the following packages:
* Rdatasets [documentation](https://github.com/JuliaStats/RDatasets.jl)
* Plots [documentation](http://docs.juliaplots.org/latest/)
* Random [documentationra](https://docs.julialang.org/en/v1/stdlib/Random/)
