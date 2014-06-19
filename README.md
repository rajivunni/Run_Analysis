Run_Analysis
============

Getting and Cleaning Data Course Project 

This is a repository for the course project of the online course Getting and Cleaning Data from Coursera.

You can find information about the data in CodeBook.md.

The R code is for creating a new tidy data set with the average of each variable for each activity and each subject from the raw data.

After downloading the data from:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Extract it into the data directory under your R working directory.

You can run R code run_analysis.R or source it. It will generate a text file named "CompleteData.txt". This is the required data set.


====================
## Source

Information about used data in: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Used data set: [zip file](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) 

====================
## Dependencies

`run_analysis.R` depends on `reshape2` and `plyr` libraries (NOTE: The R script created will install and load them if necessary).
