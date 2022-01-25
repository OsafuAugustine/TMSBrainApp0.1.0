## TMSBrainApp
TMSBrainApp is an R Package for TMS brain mapping, adopting a Bayesian spatial statistical technique.
Please, follow the instructions on how to install the package on the R interface.

## How to install TMSBrainApp on R
Prerequisites
- Ensure that your machine has R (>=3.5.0) installed. Otherwise, download and install from https://cran.r-project.org/.
-Ensure that "Rtools" is installed. Otherwise, download from https://cran.r-project.org/bin/windows/Rtools/rtools40.html
- Manually install R-INLA from its repository. (https://www.r-inla.org/download-install)

Step 1. On R interface, install "devtools" package from CRAN repository.
		R > install.packages("devtools")
Step 2. Intall TMSBrainApp.
		R > install_github("OsafuAugustine/TMSBrainApp0.1.0")
Step 3. To execute the TMSBrainApp interface;
		R > library(TMSBrainApp)
		R > TMSapp.run()
