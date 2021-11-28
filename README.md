# HW_8_ML_Conf_Imb_U11
Unit 11 Homework - Risky Business - ML w Imbalanced Lib and Confusion Matrix

# Resampling model process

I examined the LendingClub data with multiple algorithms, to determine which worked best for this data set. 

The these included a _simple logistic regression_, which yielded the following results:
balanced accuracy score: 98%
Confusion Matrix: 615, 10; 102, 18657

Also an oversampling process: _naive random oversampler_ 
Confusion Matrix: 622, 3; 111, 18648

Also oversampled with _Smote_
Confusion Matrix: 622, 3; 110, 18649

Then I did an undersampling process with ClusterCentroids, and the result was:
balanced accuracy score of 99.4%
confusion matrix: 620,5; 102,18657

Finally I did a combination (over and under) sampling process using the smoteen algorithm:
balanced accuracy score: 99.32%
confusion matrix: 622, 3; 110, 18649

The best accuracy score was the undersampled one. 



# Ensemble Learning

I applied the Balanced Random Forest Classifier and the Easy Ensemble Classifier to predict loan risk and evaluate each model.



# Technical Notes

## Libraries
This Jupyter Lab notebook utilizes the following libraries:

 --   path

 --   collections

 --   sklearn
 
 --   imblearn

 --   pandas

 --   Numpy

 --   Pathlib

 --   matplotlib


# Acknowledgements

I would like to first acknowledge the guidance and teaching of our FinTech Boot Camp Instructor, Garth Mortensen, our TA, Alejandro Esquivel, and out Student Success Manager, Angelica Baraona. I also found the collective Stack Overflow wisdom (especially the Quantitative Finance community) essential as ever. Regarding Time Series and Machine Learning overall I utilized information from the geeksforgeeks.org (again) website, as well as Jason Brownlee's '11 Classical Time Series Forecasting Methods in Python (Cheat Sheet)' page, 'Time Series Analysis in Python - A Comprehensive Guide with Examples' from the Machine_Learning_+ website, and the Dataquest website's tutorial 'Time Series Analysis with Pandas'; as well as the tech website collective in general. The Pandas books section on Time Series were helpful. 
