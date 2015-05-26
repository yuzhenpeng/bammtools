BAMMtools
=========

BAMMtools is an R package for analysis of BAMM results

Installation
---------------
Stable versions of ```BAMMtools``` are available for installation from within R:

	install.packages("BAMMtools");

Bleeding-edge versions can be obtained as follows.

Install Hadley Wickham's ```devtools```:

	install.packages("devtools", dependencies=TRUE);

Note: this may require the installation of several non-R dependencies. Missing dependencies are (for the most part) reported in error messages generated.


Then, install ```BAMMtools```:

	require(devtools);
	install_github("macroevolution/bammtools/BAMMtools");

Fin.
