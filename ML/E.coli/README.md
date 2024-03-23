E.coli Protein Localisation Sites 
The protein localisation data set contains a set of 5 features describing the
properties of proteins found in the bacteria Escherichia coli. The location of the
proteins within the cell is also known. Our aim is to develop a model that can predict
the location of a protein based on the features. The data are sourced from the UC
Irvine Machine Learning Repository, Nakai,Kenta. (1996). Ecoli. UCI Machine
Learning Repository. https://doi.org/10.24432/C5388M.

The columns in the file are:
• X1 to X5 - Features of the proteins
• C – Class. This is the location of the protein. A value of 0 refers to proteins
located in the inner membrane, whereas proteins in the perisplasm are
labelled as 1.
with the target being the Class feature in the last column. 
Our aim is to apply and evaluate classification methods on this data using a Naïve
Bayes model, and a logistic regression model, to predict the class (protein location)
based on the features.