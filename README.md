# GIST_diagnose
xgboost model for GIST diagnosis

Download the ZIP file and unfold it.

open the R file named "plumber.R" with Rstudio version 4.0 or higher. 

Install the packages needed which have been listed on the top.

Run the first three lines, like: 

modellist <- readRDS("xgbmodel.rds")
modelMatrix = modellist$modelMartix
bst.train = modellist$bst.train

After that, you can click the button "Run API" and use the model

click" try it out" to input the data.

Here, 1 means Yes and 0 means No. 

Lymphcyte count is calculated by ×10^9/L. For example, if one's lymphcyte is 1.3×10^9/L, you just need to input "1.3". 
