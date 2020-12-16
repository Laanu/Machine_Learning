For this assignment, i initially completed the resampling using all the colomns. I struggled with identifying which features in the data was important. after completing my credit risk ensemble i was able to use the output of the features importance to rerun my analysis. 


#### Resampling

Use the above to answer the following:

> Which model had the best balanced accuracy score?
	> Oversampling balanced accuracy = 0.581 
	>SMOTE Oversampling = 0.837
	>Undersampling = 0.837
	>Combination = 0.777
    both SMOTE Oversampling and Understampling have the same accuracy score so both have the best score.
> Which model had the best recall score?
	>Oversampling balanced accuracy = 0.65
	>SMOTE Oversampling = 0.65
	>Undersampling = 0.55
	>Combination = 0.66
> Which model had the best geometric mean score?
	>Oversampling balanced accuracy = 0.78
	>SMOTE Oversampling = 0.78
	>Undersampling = 0.67
	>Combination = 0.79



#### Ensemble Learning

Use the above to answer the following:

> Which model had the best balanced accuracy score?
	>Balanced Random Forest Classifier = 0.8311
	>Easy Ensemble Classifier = 0.8311
This two model's balance accuracy scores are identical 
> Which model had the best recall score?
	> Balanced Random Forest Classifier = 0.88
	
> Which model had the best geometric mean score?
	> Balanced Random Forest Classifier = 0.89
> What are the top three features?
 	>’total_pymnt_inv'= 0.098
 	>’total_pymnt' =.0934
 	>’total_rec_prncp = .0856