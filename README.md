# Jobathon_Loan-Prediction
The first step conducted was some basic exploratory data analysis with some visualisations 
such as heatmap for checking the correlation. 
• Python modules namely sea born and matplolib was been used to conduct the visualisation. 
• The basic package such as pandas and numpy was used for analysis. 
• After that I checked for the null values in the datasets, dropped and removed the null values. 
• Then checked for the dataset whether it is balanced or not. After analysis, I observed that 
the dataset was imbalanced and biased towards the lead=0. 
• Then I used the label encoder which is used to transform non-numerical labels to numerical 
labels to the 10 columns in the dataset. 
• From the train dataset dropped the ID and the IS_Lead and made the IS_Leas as the target 
variable(y) 
• For making my machine learning model, I used sklearn library. 
• Initialliy tried with logistic regression, random forest, gradient boost, Light gbm boost. 
• Finally after testing, CATBOOST gave me the highest ROC with 0.8047 score.
