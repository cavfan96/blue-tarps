# Blue Tarp Project

This project was completed during 2nd semester (Fall 2020) at UVA’s MS in Data Science Program to fulfill the SYS6018 “Deep Mining” requirements.

The project uses R and develops a classifier for discerning “blue tarps” from "non-blue tarps" in a hypothetical scenario related to the 2010 Haiti Earthquake in which the classifier is intended to quicken response and recovery for survivors.

Multiple statistical models are developed and evaluated including logistic regression, SVM, random forest, discriminant analysis, etc.

## Table of Contents

1. Code
- Rproj file that includes a wrapper for the code, uploading the dataframes, models, etc., into memory.
- rmd file which builds the html file 
- html file resulting from the rmd file
2. Data in csv files
- file 1 "haiti pixels" csv, which is a smaller data file used to train the models
- file 2 "fho csv zip", which contains a larger csv file used to train/test and validate models
3. Packages
- Main packages are tidyverse (for data manipulation/visualization), and caret (for the models).

## Conclusion

If you are new at using statistical models for a classifier, this will provide you quite a bit of ideas on how to proceed. Analysis is also included, which will at least show you some more in-depth thought on the quality of the models and how they might be useful in the scenario given.
