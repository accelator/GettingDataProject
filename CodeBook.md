If you process my script, you can get some data sets. Here, I will describe the variables of my data.

In the 1st part of my script, I don't offer names to the different variables. So most names of the column and row are defaults.I just make use of 
rbind functioin and then transform the data set into a dataframe.

In the second part of this project,my final result is named of getdata. Because, for convenience, I first finish question 4 and endow the data set
columns with names in features.txt, in the getdata, you will find the variable names are professional ones from features.txt. However, since the question here require us to extract the measurements related to mean and standard variation. The variables in the getdata are merely part of the complete ones. 

Based on the questions before, here, I just add two variables into my final data set. The first variable is from y_train.txt and y_test.txt files
which are used to reflect the kind of activities. (I call this variable activity_num.) The second variable is called "activity".It's the mapping
activity of the variable "activity account".

In the fifth question, I still cite the variable names in features.txt. For the row names, the "mean for activity i" refer to the mean value of  certain column for certain activity i, where i is from 1 to 6. The "mean for subject i" refer to the mean value of certain column for some subject.