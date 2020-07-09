# classification-of-breast-cancer
This dataset has numbers describing each of the feature that are monitored when trying to detect breast cancer. There are 30 features that are monitored . 
The objective of this study is to build a predictive model that will improve the accuracy of breast cancer diagnosis by classification analysis. 
As result we have achieved 94% accuracy to detect malignant or benign breast cancer.
Abstract
This dataset has numbers describing each of the feature that are monitored
when trying to detect breast cancer. There are 30 features that are
monitored .
The objective of this study is to build a predictive model that will improve the
accuracy of breast cancer diagnosis by classification analysis.
As result we have achieved 94% accuracy to detect malignant or benign
breast cancer.
Motivation
Worldwide, breast cancer is the most common type of cancer in women and the
second highest in terms of mortality rates.Diagnosis of breast cancer is performed
when an abnormal lump is found (from self-examination or x-ray) or a tiny speck of
calcium is seen (on an x-ray). After a suspicious lump is found, the doctor will
conduct a diagnosis to determine whether it is cancerous and, if so, whether it has
spread to other parts of the body.
The objective of this study is to build a predictive model that will improve the
accuracy of breast cancer diagnosis by classification analysis.
Dataset
The dataset has 569 rows and 33 columns. Amongst the 33 columns, the first two
are ID number and Diagnosis (M=malignant, B = benign). And the last column is an
unnamed column with only NaN values, so it is removed right away. Other 30
features are use to predict diagnosis is benign or malignant , example:
● radius (mean of distances from center to points on the perimeter)
● texture (standard deviation of gray-scale values)
● perimeter
● area
● smoothness (local variation in radius lengths)
● compactness (perimeter^2 / area - 1.0)
● concavity (severity of concave portions of the contour),etc
Data Preparation and Cleaning
At high level before analysis the preparation and data cleaning performed :
● Mapping of Diagnosis variable is done which is our Target variable to 0,1 : 1
for Malignant 0: Benign.
● Checked and cleaned out the null values.
● Checked the correlation among different features and target variable
diagnosis.
● Create a list of potential Features to measure correlation.
● Visualization of important features in relation to target variable diagnosis to
see on which features it is more related.
● Plotting the correlation coefficients of each feature with "diagnosis".
● Visualization of important features in relation to target variable diagnosis to
see on which features it is more related.
Research Question(s)
Question: Can you do classification analysis on diagnosis in breast cancer dataset
and predict the accuracy percentage?
Methods
● Mapping of Diagnosis variable is done which is our Target variable to 0,1 : 1
for Malignant 0: Benign, further used for classification analysis
● Checked the correlation among different features and target variable
diagnosis.
● Create a list of potential Features to measure correlation.
● Visualization of important features in relation to target variable diagnosis to
see on which features it is more related.
● Plotting the correlation coefficients of each feature with "diagnosis".
● Visualization of important features in relation to target variable diagnosis to
see on which features it is more related.
● split training and testing dataset using sklearn to X_train, X_test,y_train,y_test
● Predict the accuracy by using sklearn
Findings
● The objective of this study is to build a predictive model that will improve the
accuracy of breast cancer diagnosis by classification analysis.
● Visualization has been done to achieve this objective , Important features in
relation to target variable diagnosis has been plotted to see on which features
it is more related
Graph to show the correlation values and column names.
Conclusion
● Classification of this dataset lead us to achieved 94% accuracy to detect
malignant or benign breast cancer in women.
Acknowledgements
● I have this data from kaggle.
● I have done this work by myself and no one has given me any feedback.
Reference
https://www.kaggle.com/nsaravana/breast-cancer
