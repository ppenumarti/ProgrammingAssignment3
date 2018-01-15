This repository ProgrammingAssignment3 explains how to use an R Script called run_analysis.
The purpose of this script is to merge training and test data sets of a variety of observations over Human Activity Recognition and focus on the mean and standard deviation of each measurement.

Pre-requisites to run the script run_analysis.R
1) Access to internet from your computer.
2) A package called plyr installed in your R-environment. plyr is an R-package that allows the script to apply methods to split and combine dataframes. Install this package from any CRAN mirror site of your choice. 
3) Atleast 300MB diskspace. This space will be used by the script to store the downloaded data. 

Ensuring the above pre-requisites are satisfied in your R-Environment run the below function without providing any arguments.
runAnalysis()

Running the above method creates a work folder by name "UCI HAR Dataset" on your computer. You may want to delete this folder after analyzing the results. 

This script produces an output file called tidyMeans.txt
This file can be read as a table in R-environment.
CodeBook.md file explains the data and variables of the file tidyMeans.txt
