#Project - Crisis 2008: Could we predict it earlier?
Prediction of 2008 crisis using Regression Techniques
===============================================================================

Usage instructions:
==================

(1) R markdown 
 
	#Import the rmd file to RStudio

	#Place the data files in folder 'data' of current Directory
	
	#Install the packages for the following libraries
	1. library('corrplot')
	2. library(car)
	3. library(leaps)
	4. library(psych)
	
	#Run the code and preview the R output
	
(2) Code Summary
	# We have the correlation plots for all data
	# From Regsubset and by anlysing the VIF values we have come up with 4 Regression models
		1. AIG~XLF+FNMA+RATE
		2. SPY~AIG+FNMA
		3. AIG~SPY+RATE
		4. SPY~RATE

  # Please note that the data is read from the following  directory 'data' under the current working directory.
  1. data
     Contains data in Microsoft Excel Comma Separated Values File (.csv) .
	
  # Please also note that the r code was run in a windows environment

(3) Preview HTML
        # The stats_project.nb.html file contains a preview of the code and the corresponding output for each
        # chunk. Please open this in any browser.
