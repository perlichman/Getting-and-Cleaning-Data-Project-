This file describes how run_analysis.R script works.
First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  into your working directory
Make sure the data and the run_analysis.R script are both in the current working directory.
Nest, use source("run_analysis.R") command in RStudio.
You will find two output files are generated in the current working directory:
	◦	merged_data.txt contains a data frame called cleanedData 
	◦	tidy_Data.txt contains a data frame called result.
Lastly, use data <- read.table("data_with_means.txt") command in RStudio to read the file. Since we are required to get the average of each variable for each activity and each subject
