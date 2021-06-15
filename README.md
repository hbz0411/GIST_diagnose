# GIST_diagnose
xgboost model for GIST diagnosis

Download the ZIP file and unfold it.
open the R file named "plumber.R" with Rstudio version 4.0 or higher. 
install the packages needed which have been listed on the top
run the first three lines, like: 

modellist <- readRDS("xgbmodel.rds")
modelMatrix = modellist$modelMartix
bst.train = modellist$bst.train

After that, you can click the button "Run API" and use the model
