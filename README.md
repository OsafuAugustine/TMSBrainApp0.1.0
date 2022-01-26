## TMSBrainApp
TMSBrainApp is an R Package for TMS brain mapping, adopting a Bayesian spatial statistical technique. The package houses a shiny user interface, where one could perform Brain mapping in R without writing codes.  

Please, follow the instructions on how to install the package on the R interface.

### How to install TMSBrainApp on R
Required tools

- Ensure that your machine has R (>=3.5.0) installed. Otherwise, download and install from https://cran.r-project.org/.  
- For Windows users, please ensure that "Rtools" is installed. Otherwise, download from https://cran.r-project.org/bin/windows/Rtools/rtools40.html.  
- Manually install R-INLA (version 21.11.22 or more recent) from its repository. (https://www.r-inla.org/download-install).  

Step 1. On R interface, install "devtools" package from CRAN repository.  
```
		R > install.packages("devtools")  
```
Step 2. Intall TMSBrainApp.  
```
		R > install_github("eosafu/TMSBrainApp0.1.0")  
```
Step 3. To execute the TMSBrainApp interface;  
```
		R > library(TMSBrainApp)  
		R > TMSapp.run()  
```

Navigate through the interface by clicking on the appropriate tabs.  A sample of TMS Brain data is available for practice.

One can as well choose to work on a web browser rather than the R shiny interface.  To do this: on the R shiny interface, cick on "Open in Browser".
