# Dynamical Systems Approach to Immmune Response Modeling (DSAIRM) 



## To-do
* Continue streamlining code base to make it more general/modular/flexible
* Continue implementing unit tests using the testthat package
* Improve error messages when simulation failed: Add a failure flag to each underlying simulator, have calling function check the failure status and process accordingly
* Possibly add checks to parameter settings, don't allow unreasonable (e.g. negative) ones
* Consider changing placement of inputs/outputs/instructions
* Add a 'reset' button that sets inputs back to default values
* Update all solutions 
* Add learning objectives to each overview tab
* Clean up diagrams as needed

* look into R consortium package certification
* Maybe submit for Ropensci review: https://github.com/ropensci/onboarding
* Get best practices badge: https://bestpractices.coreinfrastructure.org/en


## Further apps that could be implemented
* More complicated HCV PK/PD (SISMID-U4-3/4)
* U/S analysis using regression instead of correlation (U6-us3)
* models with memory/dummy compartments (U9-memory)
* discrete-time model with noise (U9-noise)
* fitting of multiple datasets and types of data, e.g. Pawelek 2016 model
* fitting of multiple-condition datasets, e.g. with and without drug present (find old R code for this) 
* fitting using different likelihood approaches (instead of just SSR)
* co-infection model

## General thoughts and comments

* Hashtags on twitter when promoting app: #rstats, #dynamicalsystems #immunology #infectiousdisease
