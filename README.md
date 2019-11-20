# OSES2019

This repo contains the source code from the paper: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8867348

Start by running the notebook Plotting_UK_demand_data. 
The folder IntermediateData contains a file called generationMatrix.pickle which contains the generation by type data fro the UK in 2015

Plotting_UK_demand_data will build the dispatch function and try and explain the logic behind it

The notebook pyomo_MILP then requires the [pyomo package](http://www.pyomo.org/) and a solver.

I used [CPLEX](https://www.ibm.com/uk-en/analytics/cplex-optimizer) as the solver. 

You will have to choose your own solver an specify the path to the executable after defining the concrete model in Pyomo.

