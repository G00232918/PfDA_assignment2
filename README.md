# PfDA_assignment2

#### Author - James Connolly
#### Student_Number - G00232918
#### Module - Programming for Data Analysis

### Problem statement

This project will investigate the Wisconsin Breast Cancer dataset. The following list presents the requirements of the project:
- Undertake an analysis/review of the dataset and present an overview and background.
- Provide a literature review on classifiers which have been applied to the dataset and compare their performance
- Present a statistical analysis of the dataset
- Using a range of machine learning algorithms, train a set of classifiers on the dataset (using SKLearn etc.) and present classification performance results. Detail your rationale for the parameter selections you made while training the classifiers.
- Compare, contrast and critique your results with reference to the literature
- Discuss and investigate how the dataset could be extended – using data synthesis of new tumour datapoints
- Document your work in a Jupyter notebook. 
- As a suggestion, you could use Pandas, Seaborn, SKLearn, etc. to perform your analysis. 
- Please use GitHub to demonstrate research, progress and consistency

## 1. Overview and background

#### Sources -
- The dataset summary.


- Read in the csv file and se the headers to have shorter names.
- Change the Diagnosis values
- Check datatypes
- Change object datatype to an integer type
- Check the shape
- Remove the rows with null values.
- Check is there any null values.
- Show the first 10 rows to ensure the data is correct.
- Check the last 10 rows.
- Show the count of values within each column
- Describe to tranpose the data.

#### Sources -
- https://towardsdatascience.com/deep-learning-in-winonsin-breast-cancer-diagnosis-6bab13838abd - Example of reading in the dataset.
- https://www.geeksforgeeks.org/ml-kaggle-breast-cancer-wisconsin-diagnosis-using-knn/ - reference to change Diagnosis value
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dtypes.html - Check the datatypes.
- https://stackoverflow.com/questions/15891038/change-column-type-in-pandas -Change column type in pandas dataframe.
- https://stackoverflow.com/questions/13413590/how-to-drop-rows-of-pandas-dataframe-whose-value-in-a-certain-column-is-nan - Remove rows wih nan value reference code
- https://stackoverflow.com/questions/26266362/how-do-i-count-the-nan-values-in-a-column-in-pandas-dataframe - Reference to check the columns for nan values
- https://stackoverflow.com/questions/32589829/
how-to-get-value-counts-for-multiple-columns-at-once-in-pandas-dataframe - Get the value counts for multiple columns at once
- Lecture notes.

## 2 Literature review on classifiers

## 2.1 XGBoost
### Sources
- https://www.researchgate.net/publication/349507044_An_Evaluation_of_the_Wisconsin_Breast_Cancer_Dataset_using_Ensemble_Classifiers_and_RFE_Feature_Selection_Technique -The study reviewed for XGBoost and Random Forest.
- https://en.wikipedia.org/wiki/Gradient_boosting - Definition of XGBoost.
- https://towardsdatascience.com/a-beginners-guide-to-xgboost-87f5d4c30ed7 - Reviewing the process of how the data is validated.
- https://towardsdatascience.com/a-beginners-guide-to-xgboost-87f5d4c30ed7 - Image

## 2.2 Random Forest
### Sources
- https://en.wikipedia.org/wiki/Random_forest - Definiition of Random Forest.
- https://www.ibm.com/cloud/learn/random-forest#toc-benefits-a-VrBNAC3d - Understanding the characteristics of Random Forest.
- https://www.youtube.com/watch?v=v6VJ2RO66Ag - Get more information on Random Forest. 
- Image - https://www.ibm.com/cloud/learn/random-forest#toc-benefits-a-VrBNAC3d

## 2.3 Study Conclusion

## 2.4 K-nearest Neighbours Algorithm (KNN)

- https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761 - Get examples of classfication and regression problems. 
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.value_counts.html - Value count reference.


### 2.4.1 Elbow method
- Give the reasoning why to use the method.
- Explain how the Elbow method works

### Sources
- https://www.scikit-yb.org/en/latest/api/cluster/elbow.html#:~:text=The%20elbow%20method%20runs%20k,point%20to%20its%20assigned%20center. - Elbow method explanation. 

### 2.4.2 Lazy learners vs Eager learners

### Sources 
- https://www.i2tutorials.com/why-knn-algorithm-is-called-as-lazy-learner/ - Lazy learner description. 

## 2.5 Naive Bayes

### Sources 
- https://www.linkedin.com/pulse/naive-bayes-algorithm-explained-simranjeet-singh - Definiition of Naive Bayes
- https://www.geeksforgeeks.org/naive-bayes-classifiers/ - Describing the feature matrix and response vector.


### 3. Statisical Analysis
- Check the frequency class
- Percentage of frequency distribution class
- Histograms for distribution
- Correlation
- Heatmap

#### Sources
- https://pandas.pydata.org/docs/user_guide/visualization.html - Histogram reference
- https://www.geeksforgeeks.org/how-to-create-a-seaborn-correlation-heatmap-in-python/ - Heatmap reference code.

## Classifiers to be applied

### 4.1 Train the classifiers
- Setting the target variable
- Splitting the target
- Get the shape of the split

#### Sources
- https://h2o.ai/wiki/target-variable/ - Setting the target and the reasoning.
- https://www.v7labs.com/blog/train-validation-test-set - Reference for training and testing data. 

### 4.2 Random forest 
### Sources 
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesClassifier.html - Reference code for Random Forest classifier.

### 4.3 Decision Tree
### Sources 
- https://scikit-learn.org/stable/modules/tree.html - Reference code

### 4.4 KNN
### Sources
- https://scikit-learn.org/0.15/modules/generated/sklearn.neighbors.KNeighborsClassifier.html - Reference code.

### 4.5 Naive Bayes
### Sources
- https://scikit-learn.org/stable/modules/naive_bayes.html - Reference code

## 5. Comparing results of classifiers

### 5.1 Comparing visually 
- Bar chart with matplotlib

### Source
- https://www.tutorialspoint.com/matplotlib/matplotlib_bar_plot.htm - Reference code.

### 5.2 Comparing Results
- Commentary provided on the results.

## 6. How this dataset counld be extended

### Source
- https://towardsdatascience.com/top-3-python-packages-to-generate-synthetic-data-33a351a5de0c