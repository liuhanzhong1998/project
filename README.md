Machine Learning and Transportation

Project:titanic_survival_exploration

1.Dataset:

In total, we used dataset of titanic_survival_exploration prediction. The first dataset we used could be download at https://github.com/udacity/machine-learning/tree/master/projects . 
There were 12 features and 1 target variable 'Survived', which had 892 data points for each column. We would like to know the infulence of the dataset on the fit results by comparing the accuracy and error of the two datasets under different methods separately.

2.Method and Summary:

2.1 Data reading and data pre-processing: After importing packages, we used pd.read_csv() to read datasets, and we used data.head() to check whether the data was read correctly. 
We supposed X as the feature columns and y as the target variable, and we set the test_size to be 0.2 that meant 80% of the data were used to train and 20% of the data were used to test.
Then we used StandardScaler() to standardize the features because the accuracy of the fit results was improved when it was standardized.We used four methods, and I was responsible for two of them.

2.2 Regression: We have used 4 based methods to fit the datasets.and I was responsible for two of them.The process of regression was simple. First, import packages. 
Second, use the fit function to train data and the predict function to compare with the test set. At last, use r2_score to calculate the accuracy of the method. 
After writing the code, we compared the prediction accuracy of the four methods, and we found that the prediction accuracy of the four methods seemed to be relatively close, but the  KNeighborsClassifier accuracy seemed to be higher.
Our programming skills are limited, so we spend most of our time writing and correcting code.

3.Drawing and visualization:

We have totally used list to show the results.My teammates used lists to show the results intuitively. I wanted to use charts to show the results, but my code always reported errors and could not run, 
so I put the code of the unfinished output chart into the homework and continued to modify after class.
