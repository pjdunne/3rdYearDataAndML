# Week 4 - Fitting 

Listed on options fair handout as "Fitting - parameter estimation with iminuit, using the language of ML". I originally though this would be "How to Formulate Your Problem" but this seems to have become a stand alone section.

It appears that this draws heavily on the previous two weeks material.  However the later material does not seem to depend on weeks 2, 3, and 4 heavily. There are parallels and links but I can not see any detailed connections e.g. `iminuit` is used only for this week.


## Issues


* Unclear why `iminuit` rather than standard packages is needed at this level except it simplifies transfer from MRes material.
* Need to ensure material and documentation for `iminuit` is clearly signposted.
* Parts will be a review of material known to students from years 1 and 2. The new aspect is putting these methods in the wider context and langauge of Statistics and ML.
* Find some interesting examples
	- power law distribution from networks project is challenging
	
## Fitting

* Least squares, chi-square	
* `iminuit`. Keep discussion of package-specific issues to a minimum. 
	* Provide alternative code perhaps with standard python packages?
* Over fitting, under fitting, standard polynomial or something more interesting?
* Goodness of fit
	* AIC, BIC criteria
* Uncertainty in parameter estimates.
* Example showing estimates for gaussian parameters, 
	* variation in estimates of $\hat{\mu}$ and $\hat{\sigma}$ with number of samples $N$, 
	* standard error of mean $\hat{\sigma}/\sqrt{N}$ vs standard deviation $\hat{\sigma}$, i.e.\ uncertainty in mean vs single measurement.
* Examples of other fitting criteria to show options 
	* link to cost functions in ML
	* KS test as prime example
* Try to find some more interesting examples for lecture or student exercises
	* Power-law distributions e.g. from Complexity (earthquake size distribution, rainfall), Network Science
	* Evolution of records (Record dynamics, time difference between new records goes as $\ln(t)$) e.g. use time of new world record for long jump etc.


