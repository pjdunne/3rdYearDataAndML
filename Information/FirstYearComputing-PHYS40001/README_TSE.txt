#Notes on Year 1 Computing

Tim Evans


## Lecture 1

Session 1 Learning 
* Create variables and carry out arithmetic
operations on them.
* Import packages (e.g. NumPy, Matplotlib).
* Create and manipulate arrays, and do basic
statistics on them.
* Read in a data file and save your data to an
output file.
* Create line plots and scatter plots.
* Amend the plot format to create a figure of a
publishable standard.
* Commenting your code.

Oddly the worksheets are in jupyter notesbooks but sypder ide is used next lecture. 

## Lecture 2

Learning *
* Plot a histogram of a 1D data set
* Plot error bars on scatter plots
* Fit a linear model to your data and plot both
fit and data
* Find the uncertainties on your fit parameters

All seems to be using numpy e.g. linear fits in lecture 2 including overfitting.
numpy.polyfit to fit and and numpy.loadtxt to load data
In fit, weights are 1/errors. It does appear that this is weight is applied to the unsquared difference before taking the square and it is the sum of these weighted difference all aquared that is minimised, i.e. it is a chi-square measure but that is not made very clear. 
Lecture also uses covariance matrix output to estimate error on parameters.

Colour scheme for essential and optional exercises
"Complete all green exercises before attempting ANY optional (yellow) exercises. This will involve initially
skipping optional exercises."

## Lecture 3

* Using the Spyder IDE
* Writing functions
* Using for, if and while statements to control
program flow
* Writing longer programs to achieve a specific
task

Two mentimeter Q
"How difficult was the work?"
"Was the worksheet easier or harder than last week's worksheet?"

Sypder IDE, basic code.


## Lecture 4

Topics covered:
* Solving equations - roots(), fsolve()
* Optimisation - fmin()
* Differentiation and Integration - quad(), dblquad()
* Ordinary Differential Equation solving - odeint()

Optimisation, scipy.optimize.fmin, ODE, integrate