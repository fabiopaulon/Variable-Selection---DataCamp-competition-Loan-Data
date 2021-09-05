# Variable-Selection---DataCamp-competition-Loan-Data

This project was submitted for a competition by DataCamp on September, 3rd, 2021 by me. The files were downloaded directly from the DataCamp workspace, so there is a possibility for small bugs. Please feel free to contact me in case you find any problems.

## Abstract

This dataset provides information on loans taken from LendingClub, a p2p plataform to connect individual investors with borrowers. The original source is the Kaggle link below: 
https://www.kaggle.com/itssuru/loan-data/code

However, in this competition, we are free to create a challenge and try to solve it using data visualization and other Data Science techniques. I have chosen to explore the different loan purpose categories and what were the variables in that dataset that helped to predict it.

I deployed some basic visualizations with seaborn, such as boxplots and violinplots and a heatmap to look for correlations between variables, PCA, but found little success. I used a phik correlation coefficient and algorithms to understand the importance of each variable into the prediction results of the algorithms.

I applied Standardization and oversampling because of the different scales and imbalanced regarding the 7 loan purpose categories. Ultimately, I used Random Forests and Decision Trees in a iterative process, investigating the coefficients and trying again with fewer variables, to select the 3 main attributes. By using those 3 variables, I had a classification accuracy similar to that of the same algorithms when trained with all 12 variables.

## Keywords 

Feature Selection, Multiclass Classification, Decision Tree Classifier, Random Forest Classifier, PCA, Oversampling, Imbalanced Classes,
