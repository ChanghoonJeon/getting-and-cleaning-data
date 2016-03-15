# Human Activity Recognition Using Smartphones Data Set 

First of all, we do merge. Cbind the file X_train.txt, subject_train.txt, y_train.txt and X_test.txt, subject_test.txt, y_test.txt for independant data set. And rbind these two. 

That will be like this.

┌───────────┐┌──────────────┐┌───────────┐
│_X_train.txt__││subject_train.txt││_y_train.txt__│
└───────────┘└──────────────┘└───────────┘
┌───────────┐┌──────────────┐┌───────────┐
│_X_test.txt___││subject_test.txt_││_y_test.txt___│
└───────────┘└──────────────┘└───────────┘
.........↓...............↓.................↓
.......561var..........1var..............1var

Get names of the variables from features.txt and name the variables.

And filter the variable with mean, std, subject, activity.
Change the number of activity to the discription. 

Revise the name of filtered variable name. 

And finally, to tidy messy data, you first identify the variables in your dataset, then use the tools provided by tidyr to move them into columns. 
