# divided_visual_field_go-no-go_task
Creating an online divided visual field Go/No-Go Task and analyzing its data

In Data folder: contains the csv files of the data
  all-finished.csv containts all data without any exclusion criteria applied
  all-clean.csv contains the data after the exclusion criteria applied. This is the data used for the subsequent analysis
  
In Data_cleaning: there is the R scripts used to apply the exclusion criteria. The input of it is the all-finished.csv and it outputs the all-clean.csv
 
In Analysis folder: there are the R scripts used to analyze the data
  lmm_RT.Rmd contains the code for analyzing the RT data, using Linear Mixed Models
  logit_accuracy.Rmd contains the code for analyzing trial by trial accuracy scores using logistic regression
  
Experiment folder will soon have the demo version and the JsPsych code of the experiment.
