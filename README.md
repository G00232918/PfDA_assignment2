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

### 1. Overview and background

#### Sources -
- The dataset summary.

### 2. Review of Classifiers and Performance
- Read in the csv file and se the headers to have shorter names.
- Check is there any null values.
- Show the first 10 rows to ensure the data is correct.
- Check the last 10 rows.
- Check the datatypes.
- Describe to tranpose the data.

#### Sources -
- https://towardsdatascience.com/deep-learning-in-winonsin-breast-cancer-diagnosis-6bab13838abd - Example of reading in the dataset.
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.isnull.html - How to check is there any null values.
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.tail.html - Check the last 10 rows of data.
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dtypes.html - Check the datatypes.
- https://stackoverflow.com/questions/15891038/change-column-type-in-pandas -Change column type in pandas dataframe.
- https://stackoverflow.com/questions/32589829/
how-to-get-value-counts-for-multiple-columns-at-once-in-pandas-dataframe - Get the value counts for multiple columns at once.
- Lecture notes.

### Review of Classifiers and Performance
- https://www.researchgate.net/publication/349507044_An_Evaluation_of_the_Wisconsin_Breast_Cancer_Dataset_using_Ensemble_Classifiers_and_RFE_Feature_Selection_Technique -The study reviewed for XGBoost and Random Forest.
- https://en.wikipedia.org/wiki/Gradient_boosting - Definition of XGBoost.
- https://towardsdatascience.com/a-beginners-guide-to-xgboost-87f5d4c30ed7 - Reviewing the process of how the data is validated.
- https://towardsdatascience.com/a-beginners-guide-to-xgboost-87f5d4c30ed7 - Image
- https://en.wikipedia.org/wiki/Random_forest - Definiition of Random Forest.
- https://www.ibm.com/cloud/learn/random-forest#toc-benefits-a-VrBNAC3d - Understanding the characteristics of Random Forest.
- https://www.youtube.com/watch?v=v6VJ2RO66Ag - Get more information on Random Forest. 
- Image - https://www.ibm.com/cloud/learn/random-forest#toc-benefits-a-VrBNAC3d

### 3. Classifier applied
- https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761 - Get examples of classfication and regression problems. 
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.value_counts.html - Value count reference.
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.hist.html - PLotting histograms.

### 4. Statisical Analysis
- Check the frequency class
- Percentage of frequency distribution class
- Histograms for distribution
- Correlation
- Heatmap

#### Sources
- https://pandas.pydata.org/docs/user_guide/visualization.html - Histogram reference
- https://www.geeksforgeeks.org/how-to-create-a-seaborn-correlation-heatmap-in-python/ - Heatmap reference code.

### Machine Learning - KNN

### 51 Setting the target 
- Why I picked KNN.
- Setting the target variable
- Splitting the target
- Get the shape of the split

#### Sources
- https://h2o.ai/wiki/target-variable/ - Setting the target and the reasoning. 





