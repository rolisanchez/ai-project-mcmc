# ai-project-mcmc

Markov Chain Monte Carlo Project for Artificial Intelligence class.

Based on: http://bugra.github.io/work/notes/2014-05-23/simple-bayesian-network-via-monte-carlo-markov-chain-mcmc-pymc/

For this project we are modeling an error detection system for a residential building.

The factors that we are are taking as problems are:

	- No water on the building
	- No power
	- No internet
	- Heating/cooling off
	- Alarm went on

And then building the factors that could lead to these problems.


## Requirements: 

Python 2.7

daft (http://daft-pgm.org, might need to install manually on anaconda)

	conda install -c andywocky daft=0.0.3

pymc

matplotlib

numpy

ggplot (https://github.com/yhat/ggplot, might need to install manually on anaconda)

	conda install -c conda-forge ggplot

pandas
