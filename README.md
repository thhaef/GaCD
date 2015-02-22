#Getting and Cleaning Data Course Project

Download the Data (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder (Working directory) on your local drive.

Put run_analysis.R into Working directory\\UCI HAR Dataset\\

Set the working directory: setwd("C:\\Working directory\UCI HAR Dataset\") and source the code: source("run_analysis.R")

Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.