# Kaggle.New_Titanic

There was a disaster in space and several passengers from the Titanic spaceship were transported to another dimension.
The model aims to predict which passengers were transported.

For this, I first performed an analysis of the variables, analyzing their distributions and filling in the missing values with the most repeated value in each feature.
For that I used SimpleImputer from Sklearn.Impute.
In numerical variables, I applied data normalization via MinMaxScaler

The following classification models were tested :
* Decision Tree Classifier 
cross_val_score 0.732
f1_score 0.6743
precision_score 0.6921
recall_score 0.6799

* Random Forest Classifier
cross_val_score 0.788
f1_score 0.7066
precision_score 0.7167
recall_score 0.7094

* K Neighbors Classifier
cross_val_score 0.726
f1_score 0.5655
precision_score 0.6153
recall_score 0.5899

* Logistic Regression
cross_val_score 0.768
f1_score 0.5233
precision_score 0.5994
recall_score 0.5651

The best model was Random Forest
