# bnp-paribas-cardif-claims-management-
The given data have multicollinearity so i used random forest for the model.
First of all convert the target as.factor.
NA values cannot be used in model so i removed them by na.roughfix command.
Applying model for ntree=250 because data is huge takes lots of time in compiling and i also use do.trace for stepwise output.
