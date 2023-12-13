**#PROJECT TITLE:**
HI-2022-Final- HI 2022 Final Exploring Caesarian Section Predictive Models and Visualizations


**#DATA SOURCE:**
Amin,Muhammad and Ali,Amir. (2018). Caesarian Section Classification Dataset. UCI Machine Learning Repository. https://doi.org/10.24432/C5N59X.


**#DESCRIPTION:**
This dataset contains information about caesarian section results of 80 pregnant women with the most important characteristics of delivery problems in the medical field",().


**#ADDITIONAL VARAIBLE INFORMATION:**
We choose age, delivery number, delivery time, blood pressure and heart status.
We classify delivery time to Premature, Timely and Latecomer. As like the delivery time we consider blood pressure in three statuses of Low, Normal and High moods. Heart Problem is classified as apt and inept.


@attribute 'Age' { 22,26,28,27,32,36,33,23,20,29,25,37,24,18,30,40,31,19,21,35,17,38 } 
@attribute 'Delivery number' { 1,2,3,4 }
@attribute 'Delivery time' { 0,1,2 } -> {0 = timely , 1 = premature , 2 = latecomer}
@attribute 'Blood of Pressure' { 2,1,0 } -> {0 = low , 1 = normal , 2 = high }
@attribute 'Heart Problem' { 1,0 } -> {0 = apt, 1 = inept }

@attribute Caesarian { 0,1 } -> {0 = No, 1 = Yes }


**#DESCREPENCIES:**
The feature type states integer, but the data type returned as object during data exploration. Also, the repetitive reloading and decoding code snippet before the third data visualization is due to a code in the 2nd data visualization that disrupts the code flow. 


**#USAGE:**
This "HI 2022 Final Exploring Caesarian Section Predictive Models and Visualizations" project provides a foundation for understanding the predictive capacities, but further research and exploration is needed in order to build an accuracte and fucntional model.


**#COMPARATIVE ANALYSIS:**
Mock Caesarian Section Decision Tree Model:
Accuracy: 0.44
Precision: 0.57
Recall: 0.40

Mock Caesarian Section Naive Bays Model:
Accuracy: 0.69
Precision: 0.73
Recall: 0.80

The Naive Bayes Predictive Model demonstrated the best performace. This model displayed the highest accuracy, precision, and had an recall of 0.80. An indication that the model recalled 80% of positive cases within the dataset. 


**#LIMITATION:**
Constraints includes lack of data quantity, lack of data quality, limited attribute selection, and limited model exploration or analysis.


**#LICENSE:**
This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.
This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.
