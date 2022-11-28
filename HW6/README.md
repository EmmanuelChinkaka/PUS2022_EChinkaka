It is predicted that the global urban population shall increase to about 6.4 billion residents by 2050. 
Since the urban population depend on energy for thier daily needs, the energy needs shall increase to about 730 EJ. 
This shall come with increased building development, which are the largest energy consumers in the cities. 
The paper examined the feasibility of using city-specific, public open data in order to benchmark two models 
and compare the results to the same models when using the Commercial Building Energy Consumption Survey (CBECS) dataset, the basis for Energy Star.

In this assigments, we use RandomForest Machine Learning model to predict the total energy consuption in cities
(I choose Chicago and DC). 
To do this. we firstly, gather the city data from https://github.com/Urban-Informatics-Lab/Open-Data-Benchmarking. 
And secondaly, do preprocessing by cleanining the data, apply one-hot-encoding on categorical variables and impute missing data using KNearestNeighors. 
Finally, run the RandomForest model and discuss the results.
